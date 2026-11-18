# Credit Card Fraud Pattern Explorer

An exploratory data analysis notebook for finding patterns in a synthetic credit-card transaction dataset. The analysis uses pandas, SQLite, Matplotlib, and seaborn.

[Notebook](Creditcardfraud.ipynb) · [Dataset](credit_card_fraud_10k.csv) · [Quick start](#quick-start)

## What the notebook covers

- Inspect transaction fields, data types, and the fraud label distribution.
- Clean the data and use the interquartile range to check transaction amount outliers.
- Load the data into three related SQLite tables and query them from the notebook.
- Use charts and grouped summaries to explore patterns in transactions marked as fraudulent.

## Quick start

Run the commands from the repository root so the notebook can read the CSV using its relative path.

```bash
python -m pip install jupyter pandas numpy matplotlib seaborn
jupyter notebook Creditcardfraud.ipynb
```

The synthetic dataset comes from the [Credit Card Fraud Detection Dataset on Kaggle](https://www.kaggle.com/datasets/miadul/credit-card-fraud-detection-dataset).
