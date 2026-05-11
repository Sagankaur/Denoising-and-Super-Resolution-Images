## submission_1
rmse: 41.8

{'scale': 4,
 'full_hr_ratio': 4.006410256410256,
 'lr_patch': 64,
 'hr_patch': 256,
 'batch_size': 12,
 'epochs': 20,
 'lr': 0.0001,
 'weight_decay': 1e-06,
 'grad_clip': 1.0,
 'num_workers': 2,
 'val_ratio': 0.1,
 'amp': True,
 'max_val_images': 60}

Epoch 01 | loss=0.2199 | val_rmse=0.18523 | time=50.8s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 02 | loss=0.1617 | val_rmse=0.17443 | time=13.4s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 03 | loss=0.1556 | val_rmse=0.16978 | time=13.5s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 04 | loss=0.1500 | val_rmse=0.16632 | time=13.7s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 05 | loss=0.1506 | val_rmse=0.16444 | time=13.2s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 06 | loss=0.1469 | val_rmse=0.16045 | time=13.0s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 07 | loss=0.1451 | val_rmse=0.15973 | time=13.5s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 08 | loss=0.1429 | val_rmse=0.15977 | time=13.2s
Epoch 09 | loss=0.1436 | val_rmse=0.15844 | time=13.3s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 10 | loss=0.1450 | val_rmse=0.15796 | time=13.3s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 11 | loss=0.1422 | val_rmse=0.15859 | time=13.1s
Epoch 12 | loss=0.1434 | val_rmse=0.16037 | time=13.1s
Epoch 13 | loss=0.1417 | val_rmse=0.15762 | time=13.4s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 14 | loss=0.1422 | val_rmse=0.15796 | time=13.4s
Epoch 15 | loss=0.1409 | val_rmse=0.15798 | time=13.0s
Epoch 16 | loss=0.1429 | val_rmse=0.15671 | time=13.5s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 17 | loss=0.1425 | val_rmse=0.15685 | time=13.0s
Epoch 18 | loss=0.1429 | val_rmse=0.15633 | time=13.3s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 19 | loss=0.1417 | val_rmse=0.15615 | time=13.6s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 20 | loss=0.1416 | val_rmse=0.15612 | time=13.0s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt

------------------
## submission_2
rmse: 18.8

{'scale': 4,
 'full_hr_ratio': 4.006410256410256,
 'lr_patch': 72,
 'hr_patch': 288,
 'batch_size': 8,
 'grad_accum_steps': 2,
 'epochs': 45,
 'lr': 0.0002,
 'min_lr': 2e-06,
 'weight_decay': 1e-06,
 'grad_clip': 1.0,
 'num_workers': 2,
 'val_ratio': 0.1,
 'amp': True,
 'max_val_images': 80,
 'base_channels': 64,
 'jpeg_quality': 100,
 'jpeg_subsampling': 0,
 'use_tta': True}

Epoch 01 | loss=0.1425 | val_rmse=0.16496 | val_comp_rmse=40.976 | time=65.8s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 02 | loss=0.1409 | val_rmse=0.16487 | val_comp_rmse=40.948 | time=26.3s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 03 | loss=0.1385 | val_rmse=0.16439 | val_comp_rmse=40.763 | time=26.3s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 04 | loss=0.1387 | val_rmse=0.16411 | val_comp_rmse=40.513 | time=24.8s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 05 | loss=0.1371 | val_rmse=0.16274 | val_comp_rmse=39.981 | time=25.9s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 06 | loss=0.1363 | val_rmse=0.16132 | val_comp_rmse=39.559 | time=26.3s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 07 | loss=0.1352 | val_rmse=0.15917 | val_comp_rmse=38.968 | time=26.1s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 08 | loss=0.1345 | val_rmse=0.15683 | val_comp_rmse=38.383 | time=25.6s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 09 | loss=0.1338 | val_rmse=0.15590 | val_comp_rmse=38.134 | time=26.0s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 10 | loss=0.1315 | val_rmse=0.16673 | val_comp_rmse=40.324 | time=27.6s
Epoch 11 | loss=0.1323 | val_rmse=0.14845 | val_comp_rmse=36.391 | time=27.0s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 12 | loss=0.1286 | val_rmse=0.14872 | val_comp_rmse=36.552 | time=26.9s
Epoch 13 | loss=0.1291 | val_rmse=0.14800 | val_comp_rmse=36.413 | time=26.5s
Epoch 14 | loss=0.1256 | val_rmse=0.14615 | val_comp_rmse=35.837 | time=27.0s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 15 | loss=0.1279 | val_rmse=0.15064 | val_comp_rmse=37.399 | time=26.1s
Epoch 16 | loss=0.1240 | val_rmse=0.14264 | val_comp_rmse=35.049 | time=27.0s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 17 | loss=0.1243 | val_rmse=0.14059 | val_comp_rmse=34.668 | time=26.5s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 18 | loss=0.1214 | val_rmse=0.14477 | val_comp_rmse=35.954 | time=26.6s
Epoch 19 | loss=0.1209 | val_rmse=0.13798 | val_comp_rmse=34.144 | time=26.4s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 20 | loss=0.1180 | val_rmse=0.13678 | val_comp_rmse=33.592 | time=26.1s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 21 | loss=0.1199 | val_rmse=0.13766 | val_comp_rmse=34.041 | time=26.6s
Epoch 22 | loss=0.1174 | val_rmse=0.14461 | val_comp_rmse=36.141 | time=26.0s
Epoch 23 | loss=0.1174 | val_rmse=0.14365 | val_comp_rmse=35.813 | time=26.3s
Epoch 24 | loss=0.1167 | val_rmse=0.13742 | val_comp_rmse=34.065 | time=26.5s
Epoch 25 | loss=0.1144 | val_rmse=0.13548 | val_comp_rmse=33.392 | time=26.7s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 26 | loss=0.1160 | val_rmse=0.13667 | val_comp_rmse=33.766 | time=26.3s
Epoch 27 | loss=0.1131 | val_rmse=0.14257 | val_comp_rmse=35.487 | time=26.8s
Epoch 28 | loss=0.1140 | val_rmse=0.13762 | val_comp_rmse=34.270 | time=26.5s
Epoch 29 | loss=0.1143 | val_rmse=0.14357 | val_comp_rmse=35.925 | time=26.5s
Epoch 30 | loss=0.1147 | val_rmse=0.13790 | val_comp_rmse=34.234 | time=26.6s
Epoch 31 | loss=0.1145 | val_rmse=0.14229 | val_comp_rmse=35.475 | time=26.9s
Epoch 32 | loss=0.1144 | val_rmse=0.14076 | val_comp_rmse=35.003 | time=26.6s
Epoch 33 | loss=0.1114 | val_rmse=0.14735 | val_comp_rmse=37.069 | time=27.1s
Epoch 34 | loss=0.1154 | val_rmse=0.14634 | val_comp_rmse=36.600 | time=26.8s
Epoch 35 | loss=0.1158 | val_rmse=0.14551 | val_comp_rmse=36.502 | time=26.3s
Epoch 36 | loss=0.1128 | val_rmse=0.14513 | val_comp_rmse=36.337 | time=26.8s
Epoch 37 | loss=0.1124 | val_rmse=0.14413 | val_comp_rmse=36.072 | time=26.9s
Epoch 38 | loss=0.1132 | val_rmse=0.14275 | val_comp_rmse=35.707 | time=26.5s
Epoch 39 | loss=0.1151 | val_rmse=0.14356 | val_comp_rmse=35.945 | time=26.8s
Epoch 40 | loss=0.1117 | val_rmse=0.14421 | val_comp_rmse=36.104 | time=27.5s
Epoch 41 | loss=0.1097 | val_rmse=0.14395 | val_comp_rmse=36.020 | time=26.8s
Epoch 42 | loss=0.1134 | val_rmse=0.14298 | val_comp_rmse=35.768 | time=26.2s
Epoch 43 | loss=0.1135 | val_rmse=0.14371 | val_comp_rmse=35.974 | time=26.7s
Epoch 44 | loss=0.1147 | val_rmse=0.14314 | val_comp_rmse=35.832 | time=26.3s
Epoch 45 | loss=0.1125 | val_rmse=0.14351 | val_comp_rmse=35.926 | time=26.7s

-------------
## submission_3:
rmse:27.3
It learns how the 100 scored GT pixels change when the low-light input changes across same-scene train exposure pairs.

{'scale': 4,
 'full_hr_ratio': 4.006410256410256,
 'lr_patch': 72,
 'hr_patch': 288,
 'batch_size': 8,
 'grad_accum_steps': 2,
 'epochs': 45,
 'lr': 0.0002,
 'min_lr': 2e-06,
 'weight_decay': 1e-06,
 'grad_clip': 1.0,
 'num_workers': 2,
 'val_ratio': 0.1,
 'amp': True,
 'max_val_images': 80,
 'base_channels': 64,
 'jpeg_quality': 100,
 'jpeg_subsampling': 0,
 'use_tta': True}

CKPT_PATH = /kaggle/input/datasets/sagandeep/best-pt-18-nppe3/best_model_18.pt

Best competition-style val RMSE: 33.391793119907376
Gray calibration: gain=0.9956, bias=4.7789, val_comp 35.371 -> 35.099

Scene prior validation coverage: 80/120 | sampled RMSE=0.188
Used train-GT scene prior for 226/300 test images
Saved predictions: 300

Fitted input-delta alpha from 1144 same-scene ordered train pairs
Global input-position train RMSE: 53.3818473815918
global_input_position     | coverage=120/120 | sampled_rmse=51.252
closest                  | scene_coverage= 80/120 | full_val_sampled_rmse=17.261
mean                     | scene_coverage= 80/120 | full_val_sampled_rmse=17.261
median                   | scene_coverage= 80/120 | full_val_sampled_rmse=17.261
trimmed_mean             | scene_coverage= 80/120 | full_val_sampled_rmse=17.261
closest_input_adjusted   | scene_coverage= 80/120 | full_val_sampled_rmse=17.261
mean_input_adjusted      | scene_coverage= 80/120 | full_val_sampled_rmse=17.261
median_input_adjusted    | scene_coverage= 80/120 | full_val_sampled_rmse=17.261
trimmed_mean_input_adjusted | scene_coverage= 80/120 | full_val_sampled_rmse=17.261
Selected sampled-pixel predictor: closest {'rmse': 17.260810820261636, 'coverage': 80, 'method': 'closest', 'adjusted': False}
Rows from scene predictor: 226; rows from global input predictor: 74; rows from model fallback: 0

## submission_4
rmse: 18.7
{'scale': 4,
 'full_hr_ratio': 4.006410256410256,
 'lr_patch': 72,
 'hr_patch': 288,
 'batch_size': 8,
 'grad_accum_steps': 2,
 'epochs': 45,
 'lr': 0.0002,
 'min_lr': 2e-06,
 'weight_decay': 1e-06,
 'grad_clip': 1.0,
 'num_workers': 2,
 'val_ratio': 0.1,
 'amp': True,
 'max_val_images': 80,
 'base_channels': 64,
 'jpeg_quality': 100,
 'jpeg_subsampling': 0,
 'use_tta': True}

 Epoch 01 | loss=0.1425 | val_rmse=0.16496 | val_comp_rmse=40.977 | time=65.4s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 02 | loss=0.1409 | val_rmse=0.16487 | val_comp_rmse=40.946 | time=26.0s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 03 | loss=0.1385 | val_rmse=0.16440 | val_comp_rmse=40.766 | time=26.1s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 04 | loss=0.1387 | val_rmse=0.16411 | val_comp_rmse=40.515 | time=25.5s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 05 | loss=0.1371 | val_rmse=0.16274 | val_comp_rmse=39.982 | time=26.2s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 06 | loss=0.1363 | val_rmse=0.16132 | val_comp_rmse=39.555 | time=26.9s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 07 | loss=0.1352 | val_rmse=0.15919 | val_comp_rmse=38.976 | time=25.8s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 08 | loss=0.1345 | val_rmse=0.15686 | val_comp_rmse=38.380 | time=26.6s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 09 | loss=0.1338 | val_rmse=0.15586 | val_comp_rmse=38.131 | time=27.3s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 10 | loss=0.1313 | val_rmse=0.15617 | val_comp_rmse=38.305 | time=28.5s
Epoch 11 | loss=0.1323 | val_rmse=0.14671 | val_comp_rmse=36.001 | time=27.5s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 12 | loss=0.1264 | val_rmse=0.14819 | val_comp_rmse=36.475 | time=27.3s
Epoch 13 | loss=0.1270 | val_rmse=0.14496 | val_comp_rmse=35.755 | time=27.2s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 14 | loss=0.1219 | val_rmse=0.14170 | val_comp_rmse=34.884 | time=27.8s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 15 | loss=0.1228 | val_rmse=0.14749 | val_comp_rmse=36.712 | time=27.4s
Epoch 16 | loss=0.1196 | val_rmse=0.13967 | val_comp_rmse=34.265 | time=27.5s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 17 | loss=0.1194 | val_rmse=0.14176 | val_comp_rmse=35.145 | time=27.0s
Epoch 18 | loss=0.1189 | val_rmse=0.14686 | val_comp_rmse=36.691 | time=27.2s
Epoch 19 | loss=0.1193 | val_rmse=0.13756 | val_comp_rmse=33.984 | time=27.0s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 20 | loss=0.1171 | val_rmse=0.13776 | val_comp_rmse=33.886 | time=27.5s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 21 | loss=0.1182 | val_rmse=0.14081 | val_comp_rmse=34.918 | time=27.5s
Epoch 22 | loss=0.1163 | val_rmse=0.15095 | val_comp_rmse=37.836 | time=27.3s
Epoch 23 | loss=0.1169 | val_rmse=0.14444 | val_comp_rmse=36.126 | time=27.5s
Epoch 24 | loss=0.1162 | val_rmse=0.14020 | val_comp_rmse=34.912 | time=27.4s
Epoch 25 | loss=0.1136 | val_rmse=0.13683 | val_comp_rmse=33.725 | time=27.4s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 26 | loss=0.1155 | val_rmse=0.13886 | val_comp_rmse=34.346 | time=28.1s
Epoch 27 | loss=0.1126 | val_rmse=0.14283 | val_comp_rmse=35.612 | time=28.1s
Epoch 28 | loss=0.1135 | val_rmse=0.13962 | val_comp_rmse=34.806 | time=27.8s
Epoch 29 | loss=0.1141 | val_rmse=0.14437 | val_comp_rmse=36.150 | time=27.7s
Epoch 30 | loss=0.1145 | val_rmse=0.13878 | val_comp_rmse=34.453 | time=27.5s
Epoch 31 | loss=0.1142 | val_rmse=0.14369 | val_comp_rmse=35.892 | time=27.6s
Epoch 32 | loss=0.1142 | val_rmse=0.14186 | val_comp_rmse=35.292 | time=27.9s
Epoch 33 | loss=0.1111 | val_rmse=0.14852 | val_comp_rmse=37.377 | time=27.3s
Epoch 34 | loss=0.1151 | val_rmse=0.14746 | val_comp_rmse=36.929 | time=27.8s
Epoch 35 | loss=0.1156 | val_rmse=0.14718 | val_comp_rmse=36.977 | time=27.1s
Epoch 36 | loss=0.1126 | val_rmse=0.14668 | val_comp_rmse=36.758 | time=27.7s
Epoch 37 | loss=0.1121 | val_rmse=0.14493 | val_comp_rmse=36.265 | time=27.3s
Epoch 38 | loss=0.1131 | val_rmse=0.14399 | val_comp_rmse=36.022 | time=27.3s
Epoch 39 | loss=0.1149 | val_rmse=0.14476 | val_comp_rmse=36.263 | time=27.2s
Epoch 40 | loss=0.1116 | val_rmse=0.14508 | val_comp_rmse=36.342 | time=28.0s
Epoch 41 | loss=0.1096 | val_rmse=0.14476 | val_comp_rmse=36.238 | time=27.2s
Epoch 42 | loss=0.1133 | val_rmse=0.14376 | val_comp_rmse=35.960 | time=27.4s
Epoch 43 | loss=0.1133 | val_rmse=0.14429 | val_comp_rmse=36.113 | time=27.4s
Epoch 44 | loss=0.1144 | val_rmse=0.14385 | val_comp_rmse=35.997 | time=27.3s
Epoch 45 | loss=0.1123 | val_rmse=0.14431 | val_comp_rmse=36.124 | time=27.3s
Best competition-style val RMSE: 33.724684023857115
Gray calibration: gain=0.9993, bias=2.3786, val_comp 35.596 -> 35.516

Scene prior validation coverage: 80/120 | sampled RMSE=0.188
Used train-GT scene prior for 226/300 test images
Saved predictions: 300

Fitted input-delta alpha from 1144 same-scene ordered train pairs
Global input-position train RMSE: 53.3818473815918
model_fallback           | coverage=120/120 | sampled_rmse=33.308
global_input_position    | coverage=120/120 | sampled_rmse=51.252
closest                  | scene_coverage= 80/120 | full_val_sampled_rmse=11.574
mean                     | scene_coverage= 80/120 | full_val_sampled_rmse=11.574
median                   | scene_coverage= 80/120 | full_val_sampled_rmse=11.574
trimmed_mean             | scene_coverage= 80/120 | full_val_sampled_rmse=11.574
closest_input_adjusted   | scene_coverage= 80/120 | full_val_sampled_rmse=11.574
mean_input_adjusted      | scene_coverage= 80/120 | full_val_sampled_rmse=11.574
median_input_adjusted    | scene_coverage= 80/120 | full_val_sampled_rmse=11.574
trimmed_mean_input_adjusted | scene_coverage= 80/120 | full_val_sampled_rmse=11.574
Selected sampled-pixel predictor: closest {'rmse': 11.574351660410564, 'coverage': 80, 'method': 'closest', 'adjusted': False}
Direct submission saved: /kaggle/working/nppe3_outputs/submission.csv
Submission shape: (300, 101)
Rows from scene predictor: 226; rows from global input predictor: 0; rows from model fallback: 74


## submission_5

{'scale': 4,
 'full_hr_ratio': 4.006410256410256,
 'lr_patch': 72,
 'hr_patch': 288,
 'batch_size': 8,
 'grad_accum_steps': 2,
 'epochs': 45,
 'lr': 0.0002,
 'min_lr': 2e-06,
 'weight_decay': 1e-06,
 'grad_clip': 1.0,
 'num_workers': 2,
 'val_ratio': 0.1,
 'amp': True,
 'max_val_images': 80,
 'base_channels': 64,
 'jpeg_quality': 100,
 'jpeg_subsampling': 0,
 'use_tta': True}
 Epoch 01 | loss=0.1425 | val_rmse=0.16496 | val_comp_rmse=40.976 | time=64.5s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 02 | loss=0.1409 | val_rmse=0.16487 | val_comp_rmse=40.948 | time=26.1s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 03 | loss=0.1385 | val_rmse=0.16440 | val_comp_rmse=40.765 | time=26.0s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 04 | loss=0.1387 | val_rmse=0.16411 | val_comp_rmse=40.518 | time=25.4s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 05 | loss=0.1371 | val_rmse=0.16274 | val_comp_rmse=39.985 | time=26.2s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 06 | loss=0.1363 | val_rmse=0.16132 | val_comp_rmse=39.552 | time=26.2s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 07 | loss=0.1352 | val_rmse=0.15918 | val_comp_rmse=38.978 | time=26.1s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 08 | loss=0.1345 | val_rmse=0.15685 | val_comp_rmse=38.383 | time=27.3s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 09 | loss=0.1337 | val_rmse=0.15580 | val_comp_rmse=38.114 | time=26.5s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 10 | loss=0.1312 | val_rmse=0.15834 | val_comp_rmse=38.591 | time=28.2s
Epoch 11 | loss=0.1324 | val_rmse=0.14913 | val_comp_rmse=36.639 | time=27.4s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 12 | loss=0.1279 | val_rmse=0.14817 | val_comp_rmse=36.451 | time=27.0s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 13 | loss=0.1292 | val_rmse=0.14407 | val_comp_rmse=35.435 | time=27.3s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 14 | loss=0.1240 | val_rmse=0.14449 | val_comp_rmse=35.550 | time=27.1s
Epoch 15 | loss=0.1248 | val_rmse=0.15544 | val_comp_rmse=38.856 | time=27.4s
Epoch 16 | loss=0.1214 | val_rmse=0.14109 | val_comp_rmse=34.675 | time=26.8s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 17 | loss=0.1209 | val_rmse=0.14113 | val_comp_rmse=34.875 | time=26.9s
Epoch 18 | loss=0.1194 | val_rmse=0.14737 | val_comp_rmse=36.746 | time=27.0s
Epoch 19 | loss=0.1199 | val_rmse=0.13627 | val_comp_rmse=33.603 | time=26.8s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 20 | loss=0.1177 | val_rmse=0.13736 | val_comp_rmse=33.743 | time=26.3s
Epoch 21 | loss=0.1189 | val_rmse=0.14139 | val_comp_rmse=35.103 | time=26.7s
Epoch 22 | loss=0.1166 | val_rmse=0.14754 | val_comp_rmse=36.892 | time=27.2s
Epoch 23 | loss=0.1175 | val_rmse=0.14451 | val_comp_rmse=36.101 | time=27.3s
Epoch 24 | loss=0.1165 | val_rmse=0.14174 | val_comp_rmse=35.333 | time=27.3s
Epoch 25 | loss=0.1141 | val_rmse=0.13618 | val_comp_rmse=33.564 | time=27.6s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 26 | loss=0.1159 | val_rmse=0.13763 | val_comp_rmse=34.016 | time=27.8s
Epoch 27 | loss=0.1130 | val_rmse=0.14125 | val_comp_rmse=35.170 | time=27.1s
Epoch 28 | loss=0.1141 | val_rmse=0.13954 | val_comp_rmse=34.789 | time=27.2s
Epoch 29 | loss=0.1144 | val_rmse=0.14409 | val_comp_rmse=36.178 | time=27.7s
Epoch 30 | loss=0.1151 | val_rmse=0.13872 | val_comp_rmse=34.465 | time=26.8s
Epoch 31 | loss=0.1143 | val_rmse=0.14339 | val_comp_rmse=35.821 | time=27.2s
Epoch 32 | loss=0.1145 | val_rmse=0.13975 | val_comp_rmse=34.730 | time=27.2s
Epoch 33 | loss=0.1113 | val_rmse=0.14764 | val_comp_rmse=37.152 | time=27.4s
Epoch 34 | loss=0.1154 | val_rmse=0.14509 | val_comp_rmse=36.337 | time=27.0s
Epoch 35 | loss=0.1159 | val_rmse=0.14988 | val_comp_rmse=37.733 | time=27.8s
Epoch 36 | loss=0.1128 | val_rmse=0.14573 | val_comp_rmse=36.531 | time=27.2s
Epoch 37 | loss=0.1124 | val_rmse=0.14580 | val_comp_rmse=36.537 | time=27.4s
Epoch 38 | loss=0.1132 | val_rmse=0.14499 | val_comp_rmse=36.334 | time=27.1s
Epoch 39 | loss=0.1152 | val_rmse=0.14527 | val_comp_rmse=36.436 | time=26.9s
Epoch 40 | loss=0.1117 | val_rmse=0.14518 | val_comp_rmse=36.395 | time=27.1s
Epoch 41 | loss=0.1099 | val_rmse=0.14432 | val_comp_rmse=36.151 | time=27.6s
Epoch 42 | loss=0.1134 | val_rmse=0.14377 | val_comp_rmse=35.990 | time=27.5s
Epoch 43 | loss=0.1136 | val_rmse=0.14432 | val_comp_rmse=36.157 | time=27.7s
Epoch 44 | loss=0.1147 | val_rmse=0.14432 | val_comp_rmse=36.160 | time=27.1s
Epoch 45 | loss=0.1125 | val_rmse=0.14489 | val_comp_rmse=36.315 | time=27.2s

Fitted input-delta alpha from 1144 same-scene ordered train pairs
Global input-position train RMSE: 53.3818473815918
model_only               | full_val_sampled_rmse=33.206
global_input_position    | full_val_sampled_rmse=51.252
knn1_only                | full_val_sampled_rmse=21.039
knn3_only                | full_val_sampled_rmse=21.776
knn5_only                | full_val_sampled_rmse=22.854
knn9_only                | full_val_sampled_rmse=24.539
closest_model                      | scene_coverage= 80/120 | full_val_sampled_rmse=11.476
mean_model                         | scene_coverage= 80/120 | full_val_sampled_rmse=11.476
median_model                       | scene_coverage= 80/120 | full_val_sampled_rmse=11.476
trimmed_mean_model                 | scene_coverage= 80/120 | full_val_sampled_rmse=11.476
closest_model_input_adjusted       | scene_coverage= 80/120 | full_val_sampled_rmse=11.476
mean_model_input_adjusted          | scene_coverage= 80/120 | full_val_sampled_rmse=11.476
median_model_input_adjusted        | scene_coverage= 80/120 | full_val_sampled_rmse=11.476
trimmed_mean_model_input_adjusted  | scene_coverage= 80/120 | full_val_sampled_rmse=11.476
closest_knn1                       | scene_coverage= 80/120 | full_val_sampled_rmse=21.039
mean_knn1                          | scene_coverage= 80/120 | full_val_sampled_rmse=21.039
median_knn1                        | scene_coverage= 80/120 | full_val_sampled_rmse=21.039
trimmed_mean_knn1                  | scene_coverage= 80/120 | full_val_sampled_rmse=21.039
closest_knn1_input_adjusted        | scene_coverage= 80/120 | full_val_sampled_rmse=21.039
mean_knn1_input_adjusted           | scene_coverage= 80/120 | full_val_sampled_rmse=21.039
median_knn1_input_adjusted         | scene_coverage= 80/120 | full_val_sampled_rmse=21.039
trimmed_mean_knn1_input_adjusted   | scene_coverage= 80/120 | full_val_sampled_rmse=21.039
closest_knn3                       | scene_coverage= 80/120 | full_val_sampled_rmse=18.423
mean_knn3                          | scene_coverage= 80/120 | full_val_sampled_rmse=18.423
median_knn3                        | scene_coverage= 80/120 | full_val_sampled_rmse=18.423
trimmed_mean_knn3                  | scene_coverage= 80/120 | full_val_sampled_rmse=18.423
closest_knn3_input_adjusted        | scene_coverage= 80/120 | full_val_sampled_rmse=18.423
mean_knn3_input_adjusted           | scene_coverage= 80/120 | full_val_sampled_rmse=18.423
median_knn3_input_adjusted         | scene_coverage= 80/120 | full_val_sampled_rmse=18.423
trimmed_mean_knn3_input_adjusted   | scene_coverage= 80/120 | full_val_sampled_rmse=18.423
closest_knn5                       | scene_coverage= 80/120 | full_val_sampled_rmse=17.405
mean_knn5                          | scene_coverage= 80/120 | full_val_sampled_rmse=17.405
median_knn5                        | scene_coverage= 80/120 | full_val_sampled_rmse=17.405
trimmed_mean_knn5                  | scene_coverage= 80/120 | full_val_sampled_rmse=17.405
closest_knn5_input_adjusted        | scene_coverage= 80/120 | full_val_sampled_rmse=17.405
mean_knn5_input_adjusted           | scene_coverage= 80/120 | full_val_sampled_rmse=17.405
median_knn5_input_adjusted         | scene_coverage= 80/120 | full_val_sampled_rmse=17.405
trimmed_mean_knn5_input_adjusted   | scene_coverage= 80/120 | full_val_sampled_rmse=17.405
closest_knn9                       | scene_coverage= 80/120 | full_val_sampled_rmse=16.596
mean_knn9                          | scene_coverage= 80/120 | full_val_sampled_rmse=16.596
median_knn9                        | scene_coverage= 80/120 | full_val_sampled_rmse=16.596
trimmed_mean_knn9                  | scene_coverage= 80/120 | full_val_sampled_rmse=16.596
closest_knn9_input_adjusted        | scene_coverage= 80/120 | full_val_sampled_rmse=16.596
mean_knn9_input_adjusted           | scene_coverage= 80/120 | full_val_sampled_rmse=16.596
median_knn9_input_adjusted         | scene_coverage= 80/120 | full_val_sampled_rmse=16.596
trimmed_mean_knn9_input_adjusted   | scene_coverage= 80/120 | full_val_sampled_rmse=16.596
Selected sampled-pixel predictor: closest_model {'rmse': 11.475534391403198, 'coverage': 80, 'method': 'closest', 'adjusted': False, 'fallback': 'model'}
Direct submission saved: /kaggle/working/nppe3_outputs/submission.csv
Submission shape: (300, 101)
Predictor=closest_model; rows from scene=226; rows from fallback=74
Direct submission saved: /kaggle/working/nppe3_outputs/submission_model_only.csv
Submission shape: (300, 101)
Predictor=model_only; rows from scene=0; rows from fallback=300
Direct submission saved: /kaggle/working/nppe3_outputs/submission_knn1_only.csv
Submission shape: (300, 101)
Predictor=knn1_only; rows from scene=0; rows from fallback=300
Direct submission saved: /kaggle/working/nppe3_outputs/submission_knn3_only.csv
Submission shape: (300, 101)
Predictor=knn3_only; rows from scene=0; rows from fallback=300
Direct submission saved: /kaggle/working/nppe3_outputs/submission_knn5_only.csv
Submission shape: (300, 101)
Predictor=knn5_only; rows from scene=0; rows from fallback=300
Direct submission saved: /kaggle/working/nppe3_outputs/submission_closest_knn1.csv
Submission shape: (300, 101)
Predictor=closest_knn1; rows from scene=226; rows from fallback=74
Direct submission saved: /kaggle/working/nppe3_outputs/submission_closest_knn3.csv
Submission shape: (300, 101)
Predictor=closest_knn3; rows from scene=226; rows from fallback=74
Direct submission saved: /kaggle/working/nppe3_outputs/submission_closest_knn5.csv
Submission shape: (300, 101)
Predictor=closest_knn5; rows from scene=226; rows from fallback=74


Submission and RMSE:

submission_model_only.csv
18.87765

submission_knn5_only.csv
32.00082

submission_knn1_only.csv
36.67244

submission_closest_knn5.csv
28.88892

submission_closest_knn1.csv
33.52173

submission_5.csv
18.87695


## submission_6
{'scale': 4,
 'full_hr_ratio': 4.006410256410256,
 'lr_patch': 72,
 'hr_patch': 288,
 'batch_size': 8,
 'grad_accum_steps': 2,
 'epochs': 45,
 'lr': 0.0002,
 'min_lr': 2e-06,
 'weight_decay': 1e-06,
 'grad_clip': 1.0,
 'num_workers': 2,
 'val_ratio': 0.1,
 'amp': True,
 'max_val_images': 80,
 'base_channels': 64,
 'jpeg_quality': 100,
 'jpeg_subsampling': 0,
 'use_tta': True,
 'group_val_by_scene': True,
 'train_sr_model': False,
 'use_saved_sr_if_available': True,
 'train_direct_sample_model': True,
 'direct_base_channels': 32,
 'direct_batch_size': 16,
 'direct_epochs': 30,
 'direct_lr': 0.0003,
 'direct_min_lr': 1e-05,
 'direct_weight_decay': 0.0001,
 'direct_grad_clip': 1.0,
 'direct_blend_with_sr': True,
 'make_legacy_sample_candidates': False}

 Training full-image SR model. This is slower than the direct sampled-pixel model below.
Epoch 01 | loss=0.1421 | val_rmse=0.16256 | val_comp_rmse=38.979 | time=66.5s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 02 | loss=0.1399 | val_rmse=0.16126 | val_comp_rmse=38.492 | time=28.5s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 03 | loss=0.1402 | val_rmse=0.16092 | val_comp_rmse=38.397 | time=27.1s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 04 | loss=0.1396 | val_rmse=0.15709 | val_comp_rmse=37.302 | time=26.8s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 05 | loss=0.1374 | val_rmse=0.16074 | val_comp_rmse=38.247 | time=26.9s
Epoch 06 | loss=0.1368 | val_rmse=0.15433 | val_comp_rmse=36.429 | time=26.1s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 07 | loss=0.1339 | val_rmse=0.15125 | val_comp_rmse=35.960 | time=26.6s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 08 | loss=0.1335 | val_rmse=0.14998 | val_comp_rmse=35.663 | time=27.4s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 09 | loss=0.1346 | val_rmse=0.14701 | val_comp_rmse=34.904 | time=27.6s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 10 | loss=0.1328 | val_rmse=0.14562 | val_comp_rmse=34.579 | time=29.3s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 11 | loss=0.1311 | val_rmse=0.14562 | val_comp_rmse=34.474 | time=28.6s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 12 | loss=0.1271 | val_rmse=0.14130 | val_comp_rmse=33.133 | time=28.5s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 13 | loss=0.1265 | val_rmse=0.14717 | val_comp_rmse=34.993 | time=28.6s
Epoch 14 | loss=0.1234 | val_rmse=0.13970 | val_comp_rmse=32.865 | time=28.6s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 15 | loss=0.1211 | val_rmse=0.14333 | val_comp_rmse=33.541 | time=28.6s
Epoch 16 | loss=0.1214 | val_rmse=0.14025 | val_comp_rmse=32.964 | time=28.5s
Epoch 17 | loss=0.1202 | val_rmse=0.13892 | val_comp_rmse=32.561 | time=27.9s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 18 | loss=0.1229 | val_rmse=0.13507 | val_comp_rmse=31.388 | time=28.4s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 19 | loss=0.1206 | val_rmse=0.13718 | val_comp_rmse=31.969 | time=28.8s
Epoch 20 | loss=0.1180 | val_rmse=0.13725 | val_comp_rmse=32.075 | time=29.0s
Epoch 21 | loss=0.1185 | val_rmse=0.14076 | val_comp_rmse=33.136 | time=28.8s
Epoch 22 | loss=0.1186 | val_rmse=0.13686 | val_comp_rmse=31.861 | time=28.1s
Epoch 23 | loss=0.1191 | val_rmse=0.13434 | val_comp_rmse=31.107 | time=28.6s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 24 | loss=0.1163 | val_rmse=0.13809 | val_comp_rmse=32.153 | time=29.0s
Epoch 25 | loss=0.1184 | val_rmse=0.13387 | val_comp_rmse=30.976 | time=28.9s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 26 | loss=0.1167 | val_rmse=0.13663 | val_comp_rmse=31.706 | time=29.0s
Epoch 27 | loss=0.1155 | val_rmse=0.13333 | val_comp_rmse=31.013 | time=28.5s
Epoch 28 | loss=0.1155 | val_rmse=0.13507 | val_comp_rmse=31.352 | time=28.9s
Epoch 29 | loss=0.1143 | val_rmse=0.13483 | val_comp_rmse=31.431 | time=29.6s
Epoch 30 | loss=0.1153 | val_rmse=0.13273 | val_comp_rmse=30.804 | time=28.6s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 31 | loss=0.1152 | val_rmse=0.13501 | val_comp_rmse=31.401 | time=28.4s
Epoch 32 | loss=0.1162 | val_rmse=0.13282 | val_comp_rmse=30.782 | time=28.9s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 33 | loss=0.1153 | val_rmse=0.13749 | val_comp_rmse=32.045 | time=27.7s
Epoch 34 | loss=0.1147 | val_rmse=0.13425 | val_comp_rmse=31.170 | time=28.7s
Epoch 35 | loss=0.1141 | val_rmse=0.13573 | val_comp_rmse=31.517 | time=29.2s
Epoch 36 | loss=0.1142 | val_rmse=0.13547 | val_comp_rmse=31.548 | time=28.4s
Epoch 37 | loss=0.1168 | val_rmse=0.13627 | val_comp_rmse=31.715 | time=28.6s
Epoch 38 | loss=0.1130 | val_rmse=0.13584 | val_comp_rmse=31.556 | time=29.1s
Epoch 39 | loss=0.1134 | val_rmse=0.13472 | val_comp_rmse=31.295 | time=27.2s
Epoch 40 | loss=0.1129 | val_rmse=0.13640 | val_comp_rmse=31.747 | time=28.5s
Epoch 41 | loss=0.1129 | val_rmse=0.13631 | val_comp_rmse=31.741 | time=28.8s
Epoch 42 | loss=0.1161 | val_rmse=0.13552 | val_comp_rmse=31.501 | time=28.4s
Epoch 43 | loss=0.1138 | val_rmse=0.13649 | val_comp_rmse=31.771 | time=27.6s
Epoch 44 | loss=0.1140 | val_rmse=0.13621 | val_comp_rmse=31.710 | time=28.0s
Epoch 45 | loss=0.1142 | val_rmse=0.13614 | val_comp_rmse=31.706 | time=27.5s


Direct target image size: (1250, 1250) | LR size: (312, 312)
First sampled HR points: [(0, 0), (12, 782), (25, 315), (37, 1098), (50, 631)]
Direct epoch 01 | loss=0.08083 | val_sample_rmse=47.018 | time=32.0s
Saved best direct checkpoint -> /kaggle/working/nppe3_outputs/best_direct_sample_model.pt
Direct epoch 02 | loss=0.04829 | val_sample_rmse=32.421 | time=15.9s
Saved best direct checkpoint -> /kaggle/working/nppe3_outputs/best_direct_sample_model.pt
Direct epoch 03 | loss=0.03417 | val_sample_rmse=31.185 | time=16.0s
Saved best direct checkpoint -> /kaggle/working/nppe3_outputs/best_direct_sample_model.pt
Direct epoch 04 | loss=0.03243 | val_sample_rmse=30.730 | time=16.0s
Saved best direct checkpoint -> /kaggle/working/nppe3_outputs/best_direct_sample_model.pt
Direct epoch 05 | loss=0.03131 | val_sample_rmse=30.058 | time=16.0s
Saved best direct checkpoint -> /kaggle/working/nppe3_outputs/best_direct_sample_model.pt
Direct epoch 06 | loss=0.03062 | val_sample_rmse=29.893 | time=15.8s
Saved best direct checkpoint -> /kaggle/working/nppe3_outputs/best_direct_sample_model.pt
Direct epoch 07 | loss=0.03021 | val_sample_rmse=29.368 | time=16.2s
Saved best direct checkpoint -> /kaggle/working/nppe3_outputs/best_direct_sample_model.pt
Direct epoch 08 | loss=0.02992 | val_sample_rmse=29.461 | time=16.2s
Direct epoch 09 | loss=0.02977 | val_sample_rmse=28.955 | time=16.0s
Saved best direct checkpoint -> /kaggle/working/nppe3_outputs/best_direct_sample_model.pt
Direct epoch 10 | loss=0.02923 | val_sample_rmse=29.012 | time=16.2s
Direct epoch 11 | loss=0.02884 | val_sample_rmse=28.628 | time=16.0s
Saved best direct checkpoint -> /kaggle/working/nppe3_outputs/best_direct_sample_model.pt
Direct epoch 12 | loss=0.02871 | val_sample_rmse=28.775 | time=15.9s
Direct epoch 13 | loss=0.02845 | val_sample_rmse=29.198 | time=16.0s
Direct epoch 14 | loss=0.02832 | val_sample_rmse=28.251 | time=16.0s
Saved best direct checkpoint -> /kaggle/working/nppe3_outputs/best_direct_sample_model.pt
Direct epoch 15 | loss=0.02812 | val_sample_rmse=28.232 | time=15.8s
Saved best direct checkpoint -> /kaggle/working/nppe3_outputs/best_direct_sample_model.pt
Direct epoch 16 | loss=0.02804 | val_sample_rmse=28.300 | time=16.0s
Direct epoch 17 | loss=0.02786 | val_sample_rmse=28.249 | time=16.1s
Direct epoch 18 | loss=0.02777 | val_sample_rmse=28.114 | time=16.0s
Saved best direct checkpoint -> /kaggle/working/nppe3_outputs/best_direct_sample_model.pt
Direct epoch 19 | loss=0.02777 | val_sample_rmse=28.205 | time=16.1s
Direct epoch 20 | loss=0.02755 | val_sample_rmse=27.912 | time=16.0s
Saved best direct checkpoint -> /kaggle/working/nppe3_outputs/best_direct_sample_model.pt
Direct epoch 21 | loss=0.02765 | val_sample_rmse=27.862 | time=16.0s
Saved best direct checkpoint -> /kaggle/working/nppe3_outputs/best_direct_sample_model.pt
Direct epoch 22 | loss=0.02759 | val_sample_rmse=27.909 | time=16.0s
Direct epoch 23 | loss=0.02756 | val_sample_rmse=27.998 | time=16.1s
Direct epoch 24 | loss=0.02745 | val_sample_rmse=27.863 | time=16.0s
Direct epoch 25 | loss=0.02744 | val_sample_rmse=27.838 | time=16.0s
Saved best direct checkpoint -> /kaggle/working/nppe3_outputs/best_direct_sample_model.pt
Direct epoch 26 | loss=0.02736 | val_sample_rmse=27.912 | time=15.9s
Direct epoch 27 | loss=0.02736 | val_sample_rmse=27.796 | time=16.0s
Saved best direct checkpoint -> /kaggle/working/nppe3_outputs/best_direct_sample_model.pt
Direct epoch 28 | loss=0.02735 | val_sample_rmse=27.884 | time=16.2s
Direct epoch 29 | loss=0.02730 | val_sample_rmse=27.829 | time=15.9s
Direct epoch 30 | loss=0.02736 | val_sample_rmse=27.808 | time=16.1s

Training full-image SR model. This is slower than the direct sampled-pixel model below.
Epoch 01 | loss=0.1421 | val_rmse=0.16256 | val_comp_rmse=38.979 | time=66.5s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 02 | loss=0.1399 | val_rmse=0.16126 | val_comp_rmse=38.492 | time=28.5s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 03 | loss=0.1402 | val_rmse=0.16092 | val_comp_rmse=38.397 | time=27.1s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 04 | loss=0.1396 | val_rmse=0.15709 | val_comp_rmse=37.302 | time=26.8s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 05 | loss=0.1374 | val_rmse=0.16074 | val_comp_rmse=38.247 | time=26.9s
Epoch 06 | loss=0.1368 | val_rmse=0.15433 | val_comp_rmse=36.429 | time=26.1s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 07 | loss=0.1339 | val_rmse=0.15125 | val_comp_rmse=35.960 | time=26.6s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 08 | loss=0.1335 | val_rmse=0.14998 | val_comp_rmse=35.663 | time=27.4s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 09 | loss=0.1346 | val_rmse=0.14701 | val_comp_rmse=34.904 | time=27.6s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 10 | loss=0.1328 | val_rmse=0.14562 | val_comp_rmse=34.579 | time=29.3s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 11 | loss=0.1311 | val_rmse=0.14562 | val_comp_rmse=34.474 | time=28.6s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 12 | loss=0.1271 | val_rmse=0.14130 | val_comp_rmse=33.133 | time=28.5s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 13 | loss=0.1265 | val_rmse=0.14717 | val_comp_rmse=34.993 | time=28.6s
Epoch 14 | loss=0.1234 | val_rmse=0.13970 | val_comp_rmse=32.865 | time=28.6s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 15 | loss=0.1211 | val_rmse=0.14333 | val_comp_rmse=33.541 | time=28.6s
Epoch 16 | loss=0.1214 | val_rmse=0.14025 | val_comp_rmse=32.964 | time=28.5s
Epoch 17 | loss=0.1202 | val_rmse=0.13892 | val_comp_rmse=32.561 | time=27.9s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 18 | loss=0.1229 | val_rmse=0.13507 | val_comp_rmse=31.388 | time=28.4s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 19 | loss=0.1206 | val_rmse=0.13718 | val_comp_rmse=31.969 | time=28.8s
Epoch 20 | loss=0.1180 | val_rmse=0.13725 | val_comp_rmse=32.075 | time=29.0s
Epoch 21 | loss=0.1185 | val_rmse=0.14076 | val_comp_rmse=33.136 | time=28.8s
Epoch 22 | loss=0.1186 | val_rmse=0.13686 | val_comp_rmse=31.861 | time=28.1s
Epoch 23 | loss=0.1191 | val_rmse=0.13434 | val_comp_rmse=31.107 | time=28.6s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 24 | loss=0.1163 | val_rmse=0.13809 | val_comp_rmse=32.153 | time=29.0s
Epoch 25 | loss=0.1184 | val_rmse=0.13387 | val_comp_rmse=30.976 | time=28.9s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 26 | loss=0.1167 | val_rmse=0.13663 | val_comp_rmse=31.706 | time=29.0s
Epoch 27 | loss=0.1155 | val_rmse=0.13333 | val_comp_rmse=31.013 | time=28.5s
Epoch 28 | loss=0.1155 | val_rmse=0.13507 | val_comp_rmse=31.352 | time=28.9s
Epoch 29 | loss=0.1143 | val_rmse=0.13483 | val_comp_rmse=31.431 | time=29.6s
Epoch 30 | loss=0.1153 | val_rmse=0.13273 | val_comp_rmse=30.804 | time=28.6s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 31 | loss=0.1152 | val_rmse=0.13501 | val_comp_rmse=31.401 | time=28.4s
Epoch 32 | loss=0.1162 | val_rmse=0.13282 | val_comp_rmse=30.782 | time=28.9s
Saved best checkpoint -> /kaggle/working/nppe3_outputs/best_model.pt
Epoch 33 | loss=0.1153 | val_rmse=0.13749 | val_comp_rmse=32.045 | time=27.7s
Epoch 34 | loss=0.1147 | val_rmse=0.13425 | val_comp_rmse=31.170 | time=28.7s
Epoch 35 | loss=0.1141 | val_rmse=0.13573 | val_comp_rmse=31.517 | time=29.2s
Epoch 36 | loss=0.1142 | val_rmse=0.13547 | val_comp_rmse=31.548 | time=28.4s
Epoch 37 | loss=0.1168 | val_rmse=0.13627 | val_comp_rmse=31.715 | time=28.6s
Epoch 38 | loss=0.1130 | val_rmse=0.13584 | val_comp_rmse=31.556 | time=29.1s
Epoch 39 | loss=0.1134 | val_rmse=0.13472 | val_comp_rmse=31.295 | time=27.2s
Epoch 40 | loss=0.1129 | val_rmse=0.13640 | val_comp_rmse=31.747 | time=28.5s
Epoch 41 | loss=0.1129 | val_rmse=0.13631 | val_comp_rmse=31.741 | time=28.8s
Epoch 42 | loss=0.1161 | val_rmse=0.13552 | val_comp_rmse=31.501 | time=28.4s
Epoch 43 | loss=0.1138 | val_rmse=0.13649 | val_comp_rmse=31.771 | time=27.6s
Epoch 44 | loss=0.1140 | val_rmse=0.13621 | val_comp_rmse=31.710 | time=28.0s
Epoch 45 | loss=0.1142 | val_rmse=0.13614 | val_comp_rmse=31.706 | time=27.5s

Submission and rmse:
submission_direct_raw.csv
26.76811

submission_direct_calibrated.csv
27.20079

submission_6.csv
27.00202

submission_6.csv
27.00202

submission_direct_sr_blend.csv
27.00202

