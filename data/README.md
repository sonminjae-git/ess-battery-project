# data/

원본 `.mat` 파일은 용량(약 7.7GB)이 커서 저장소에 포함하지 않습니다.

1. Kaggle에서 데이터셋을 내려받습니다: https://www.kaggle.com/datasets/itshpark/data-driven-prediction-of-battery-cycle
2. 압축을 풀어 아래 위치에 둡니다.

```
data/archive/
├── 2017-05-12_batchdata_updated_struct_errorcorrect.mat   # Batch 1 (학습)
├── 2018-02-20_batchdata_updated_struct_errorcorrect.mat   # Batch 2 (테스트)
├── 2018-04-03_varcharge_batchdata_updated_struct_errorcorrect.mat   # extra (분석 제외)
└── 2018-04-12_batchdata_updated_struct_errorcorrect.mat   # Batch 3 (추가 테스트)
```

원본 데이터: Severson et al., *Nature Energy* 4, 383–391 (2019) · https://data.matr.io/1/
