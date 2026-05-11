# Low-Light Image Restoration: Denoising and 4x Super-Resolution

_competetion link: https://www.kaggle.com/competitions/dlp-jan-2026-nppe-3/_
It implements an iterative deep learning pipeline for restoring and upscaling low-light images from the **RELLISUR dataset**.

## Project Overview

Low-light images are characterized by high noise levels, low spatial resolution, and poor illumination. Traditional sensor noise in these environments is **non-Gaussian (heteroscedastic)**, which simple upscaling often amplifies.

This project jointly learns denoising, illumination correction, and **4x super-resolution** using a custom U-Net based architecture to reconstruct high-frequency textures while removing sensor-specific noise.

## Performance Tracking

The model underwent iterative refinements, resulting in a significant reduction in competition-grade RMSE:

| Submission | Key Enhancements | RMSE (Private) |
|---|---|---|
| **Baseline (v1)** | Initial SRUNet + Charbonnier Loss | 41.8 |
| **Iteration 2** | TTA (Test-Time Augmentation) + Larger Architecture | 18.8 |
| **Iteration 4** | **Gray Calibration** + Scene Prior Validation | **18.7** |
| **Final (v6)** | Mixed Loss (Charbonnier + Edge) + Optimized Post-Processing | 18.7 (Top-Tier) |

## Iterative Development Journey

1.  **Exploratory Data Analysis (`kaggle-eda.ipynb`)**:
    *   Analyzed intensity mappings and noise distributions in the RELLISUR dataset.
    *   Validated the 4x scaling factor and estimated brightness offsets between Input and GT pairs.
2.  **Baselines (`train-codex-v1`)**:
    *   Implemented the core **SRUNet** architecture with **PixelShuffle** for sub-pixel reconstruction.
3.  **Refinement (`train-codex-v2` to `v5`)**:
    *   Integrated **Edge Loss** to preserve structural details.
    *   Introduced **Test-Time Augmentation (TTA)** (averaging 8 views) for robust inference.
    *   Optimized hyperparameters: AdamW optimizer, Cosine Annealing, and Mixed Precision (AMP).
4.  **Final Pipeline (`train-codex-v6.ipynb`)**:
    *   Developed **Gray Calibration**: A post-processing linear regression step to align predicted pixel distributions with target distributions.
    *   Adopted **Scene-Aware Validation** to prevent data leakage and ensure environmental generalization.

## Key Technical Features

- **Joint Restoration**: One-pass denoising, illumination correction, and 4x upscaling.
- **SRUNet Architecture**: 
    - **Encoder-Decoder (U-Net)** structure for multi-scale feature extraction.
    - **PixelShuffle**: Efficient sub-pixel convolutional upscaling to 4x resolution.
    - **Refinement Layer**: Final convolutions to polish textures.
- **Combined Loss Function**: `0.9 * CharbonnierLoss` + `0.1 * EdgeLoss`.
- **Advanced Post-Processing**: Gray Calibration (gain/bias adjustment) applied to match competition target statistics.

## Notebooks Summary

- `kaggle/kaggle-eda.ipynb`: Data exploration and noise analysis.
- `kaggle/train-codex-v6.ipynb`: Best-performing production script (RMSE 18.7).
- `kaggle/train-codex-v1`: Initial SRUNet baseline (RMSE 41.8).
- `kaggle/train-codex-v2` to `v5`: Incremental updates (TTA, hypers, loss functions).
