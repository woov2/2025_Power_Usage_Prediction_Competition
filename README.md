## 2025 전력사용량 예측 AI 경진대회
[경진대회] 전력사용량 예측 AI 모델 개발

## Environment_01
```
Windows 11 Home
CPU: 8th Gen Intel(R) Core(TM) i5-8300H
RAM: 8GB
GPU: NVIDIA GeForce GTX 1060
```
## Environment_02
```
Windows 11 Home
CPU: AMD Ryzen 9 5950X 16-Core Processor
RAM: 64GB
GPU: NVIDIA GeForce GTX 3090(x2)
```

## Library_01
```
pandas 1.5.2
numpy 1.21.6
matplotlib 3.5.2
seaborn 0.11.2
scikit-learn 1.1.3
xgboost 1.7.2
lightgbm version 3.3.5
```

## Library_02
```
requirements.txt
```

## Directory
```
├── data
│   ├── building_info.csv
│   ├── train.csv
│   └── test.csv
├── submission
│   ├── LGBM_info_3.csv
│   ├── LGBM_log_ensemble_test.csv
│   └── XGB_byb_final.csv
│   └── ag_tabular_final.csv
│   └── ag_ts_ChronosFineTuned[bolt_small]_FULL.csv
│   └── Final.csv
├── LGBM_log_ensemble.ipynb
├── LGBM_info_3.ipynb
├── XGB_byb_final.ipynb
├── Ensemble.ipynb
├── ag_tabular_final.ipynb
└── ag_ts_final.ipynb
└── data_preprocessing.ipynb
└── sample_submission.csv
└── requirements.txt
└── README.md
```

## Order
```
### Environment_01
1. LGBM_log_ensemble.ipynb
2. XGB_byb_final.ipynb
3. LGBM_info_3.ipynb

### Environment_02
4. data_preprocessing.ipynb
5. ag_tabular_final.ipynb
6. ag_ts_final.ipynb

### Environment_01
7. Ensemble.ipynb
