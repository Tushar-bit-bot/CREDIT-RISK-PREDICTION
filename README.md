# Credit Risk Analysis and Loan Default Prediction

An in-progress data science project exploring borrower and loan data as the first step toward predicting loan defaults.

## Project Goal

The goal is to prepare a dataset for a machine-learning model that predicts whether a borrower will default on a loan. This is a supervised binary classification problem.

The target column is `loan_status`:

- `0` — no default
- `1` — default

## Work Completed

- Loaded and inspected the dataset.
- Explored missing values, target balance, numerical summaries, possible outliers, and correlations.
- Removed duplicate records and applied initial data-quality filters.
- Separated the features from the target.
- Created a stratified 80/20 train-test split.

## Dataset

The dataset contains borrower and loan information, including age, income, employment length, loan purpose, loan amount, interest rate, and credit history.

Place `credit_risk_dataset.csv` in the same folder as the notebook before running it.

## Run the Notebook

Install the required packages:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn jupyter
```

Open Jupyter Notebook, then open and run `creadit.ipynb`.

## Project Status

This project is still in progress. Planned next steps include handling missing values, building preprocessing pipelines, training classification models, and evaluating their performance.

## Tools

Python, pandas, NumPy, Matplotlib, Seaborn, and scikit-learn.
