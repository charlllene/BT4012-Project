# BT4012 Fraud Analytics — Group 21

Bank account fraud detection under temporal distribution shift, comparing logistic regression, decision tree, random forest, LightGBM, and XGBoost across the Base, Variant IV, and Variant V datasets.

## Project files

- `BT4012_Fraud_Project.ipynb`: data preparation, exploratory analysis, model tuning, evaluation, and age-group comparisons.
- `outputs/`: generated evaluation tables in CSV format.

## Running the notebook

1. Download `Base.csv`, `Variant IV.csv`, and `Variant V.csv` from the [Bank Account Fraud dataset suite](https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022) and place them in a local `data/` directory.
2. Install Jupyter, NumPy, pandas, Matplotlib, and scikit-learn. Install LightGBM and XGBoost to include those models; the notebook skips them if unavailable.
3. Open `BT4012_Fraud_Project.ipynb` and run its cells in order from the project directory.

Raw dataset CSVs are excluded from Git because they exceed GitHub's 100 MB per-file limit. The notebook uses months 0–3 for training, 4–5 for validation, and 6–7 for out-of-time testing.
