# Customer Churn Prediction

A machine learning project to predict customer churn using Logistic Regression, built on the IBM Telco Customer Churn dataset.

## Overview

Customer churn is one of the biggest challenges for telecom companies. This project identifies customers who are likely to churn by analyzing their usage patterns, contract type, and billing information — helping businesses take proactive retention steps.

## Dataset

**IBM Telco Customer Churn Dataset**
- 7,043 customer records
- 20 features including tenure, monthly charges, contract type, internet service, and payment method
- Target variable: `Churn` (Yes / No)

## Project Workflow

| Step | Description |
|------|-------------|
| 1 | Import libraries (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn) |
| 2 | Load dataset |
| 3 | Inspect data and check for null values |
| 4 | Data cleaning and preprocessing |
| 5 | Exploratory Data Analysis (EDA) |
| 6 | Encode categorical features |
| 7 | Define independent (X) and dependent (y) variables |
| 8 | Train-Test split (80/20) |
| 9 | Feature scaling and Logistic Regression training |
| 10 | Model prediction |
| 11 | Model evaluation |
| 12 | Insights |

## Exploratory Data Analysis

Three key visualizations to identify churn patterns:
- **Churn Distribution** — overall churn vs non-churn count
- **Tenure vs Churn** — how long customers stay before churning
- **Monthly Charges vs Churn** — pricing impact on churn behavior

## Model

- **Algorithm:** Logistic Regression
- **Preprocessing:** Missing value handling, `pd.get_dummies()` for categorical encoding, `StandardScaler` for feature scaling
- **Split:** 80% training / 20% testing

## Results

| Metric | Score |
|--------|-------|
| Accuracy | 78.7% |
| Precision (Churn) | 0.62 |
| Recall (Churn) | 0.52 |
| F1-Score (Churn) | 0.56 |

Evaluation includes accuracy score, classification report, and confusion matrix.

## Key Insights

- Customers with **high monthly charges** are more likely to churn
- Customers with **low tenure** tend to churn more
- **Contract type** significantly influences churn behavior — month-to-month contracts churn the most

## Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Author

**Rachamalla Adithya**  
B.Tech CSE (AI/ML Minor) — CVR College of Engineering, Hyderabad  
[LinkedIn](https://linkedin.com) • [GitHub](https://github.com/Adithya181) • [LeetCode](https://leetcode.com)
