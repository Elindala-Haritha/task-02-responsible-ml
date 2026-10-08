# Customer Churn Prediction — Task 02

## Project Overview

This project develops a baseline machine-learning model for predicting customer churn.

The project includes exploratory data analysis, ML problem framing, responsible data documentation, risk assessment, model training, and evaluation.

## Dataset

The dataset contains 12 customer records and 7 columns.

Features include:

- tenure_months
- support_tickets
- monthly_spend_inr
- last_login_days
- plan_type

The target variable is:

- churned

Where:
- 0 = did not churn
- 1 = churned

## Data Quality

The dataset was checked for:

- Missing values
- Duplicate rows
- Data types
- Target class distribution

No missing values or duplicate rows were identified.

## Baseline

A majority-class baseline was created by predicting the majority class for every customer.

The majority class in the dataset is 0.

## Machine Learning Model

A Logistic Regression classifier was trained using:

- tenure_months
- support_tickets
- monthly_spend_inr
- last_login_days
- plan_type

The customer_id column was excluded from the model because it is an identifier.

## Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score

The model was also compared with the majority-class baseline.

## Limitations

The dataset contains only 12 records, so the evaluation results are highly uncertain.

The model should therefore be considered an educational and exploratory baseline rather than a production-ready model.

A larger and more representative dataset would be required for reliable real-world evaluation.

## Responsible Use

The model should be used as a decision-support tool.

Predictions should not be used as the sole basis for high-impact decisions about customers.

## Files

- `customer-churn-training.csv` — dataset
- `Task_02_Baseline.ipynb` — analysis and machine-learning notebook
- `README.md` — project documentation

