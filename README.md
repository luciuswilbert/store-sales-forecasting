# Store Sales Forecasting (Kaggle)

This project tackles the **Kaggle Store Sales – Time Series Forecasting** competition, predicting 16 days of sales for Corporación Favorita stores in Ecuador.

## Notebooks

All notebooks are in the `notebooks/` folder:

- `01-eda-store-sales.ipynb` – Exploratory data analysis on train, test, stores, oil, holidays, and transactions.
- `02-data-preprocessing.ipynb` – Feature engineering and preprocessing, saving train/validation/test artifacts.
- `03-model-training.ipynb` – CatBoost, LightGBM, and XGBoost training, validation, ensembling, and submission generation.

## Models & Results

- Best single-model validation RMSLE: about **0.5869** (XGBoost).
- Ensemble validation RMSLE: about **0.5881**.

## Dataset

- Kaggle competition: **Store Sales – Time Series Forecasting**.
