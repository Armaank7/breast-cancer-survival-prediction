# Data

The dataset isn't included in this repository.

It's a version of the SEER Breast Cancer dataset, which covers women diagnosed with breast cancer in the US and comes from the National Cancer Institute's SEER cancer registry. The public version is on [Kaggle](https://www.kaggle.com/datasets/reihanenamdari/breast-cancer). The version used here has some extra columns and data quality problems, which notebook 1 finds and fixes.

The notebooks expect a file called `breast_cancer.csv` in this folder with these columns:

| Column | Description |
|---|---|
| Patient_ID | Patient identifier |
| Month_of_Birth | Month the patient was born (1 to 12) |
| Age | Age at diagnosis |
| Sex | Female or Male |
| Occupation | Patient's job (mostly empty) |
| T_Stage | Tumour stage, T1 to T4 |
| N_Stage | Lymph node stage, N1 to N3 |
| 6th_Stage | Overall stage (AJCC 6th edition), IIA to IIIC |
| Differentiated | How abnormal the cancer cells look |
| Grade | Tumour grade, 1 to 4 |
| A_Stage | Regional or Distant spread |
| Tumor_Size | Tumour size in millimetres |
| Estrogen_Status | Positive or Negative |
| Progesterone_Status | Positive or Negative |
| Regional_Node_Examined | Number of lymph nodes examined |
| Reginol_Node_Positive | Number of lymph nodes with cancer (misspelt in the source) |
| Survival_Months | Months from diagnosis to death or last follow-up |
| Mortality_Status | Alive or Dead |
