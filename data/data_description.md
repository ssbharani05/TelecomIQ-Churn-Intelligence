# Dataset Information

## Source
- **Name:** IBM Telco Customer Churn
- **Source:** Kaggle
- **Link:** https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## Dataset Overview
- **Records:** 7,043 customers
- **Features:** 21 columns
- **Target Variable:** Churn (Yes/No)

## Key Columns
| Column | Description |
|---|---|
| customerID | Unique customer identifier |
| gender | Male/Female |
| SeniorCitizen | 1 = Senior, 0 = Not senior |
| tenure | Months with company |
| Contract | Month-to-month, One year, Two year |
| PaymentMethod | Electronic check, Mailed check, Bank transfer, Credit card |
| MonthlyCharges | Monthly bill amount |
| TotalCharges | Total amount charged |
| Churn | Yes = Left, No = Stayed |
| Churn_Probability | ML model churn probability score |
| Risk_Level | High/Medium/Low risk segment |

## Files
- `telco_churn.csv` — Original raw dataset
- `telco_churn_scored.csv` — Scored dataset with ML predictions
