# Dataset

This project uses the **Credit Card Fraud Detection** dataset from the Machine Learning Group at Université Libre de Bruxelles (ULB).

## Download

The dataset can be downloaded from Kaggle:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Instructions

1. Download the dataset from Kaggle.
2. Extract the ZIP file.
3. Place the file

```text
creditcard.csv
```

inside this directory.

## Notes

The dataset file is not included in this repository because of its size and GitHub's file size recommendations. Users should download the dataset separately and place it in this folder before running the analysis.

The dataset contains:

- 284,807 transactions
- 31 columns
- 492 fraudulent transactions

Features `V1` through `V28` are principal components obtained through PCA to preserve confidentiality. The only features that have not been transformed are:

- `Time`
- `Amount`

The target variable is:

- `Class = 0` → legitimate transaction
- `Class = 1` → fraudulent transaction