# Telco Customer Churn Analysis

Exploratory analysis of customer churn for a telecom company, in Python (Pandas, Seaborn).

**Data:** [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) (Kaggle), 7,043 customers and 21 columns. The CSV is not included here, download it from Kaggle.

## What I did

- Converted `TotalCharges` to numeric and filled the 11 empty values
- Dropped the customer id and created a numeric churn flag
- Built four charts: overall churn rate, churn by contract type, churn by internet service, and tenure distribution for churned vs retained customers

## Findings

- Overall churn rate: **26.5%**
- Customers on **month-to-month contracts churn at 42.7%**, much more than customers on longer contracts

## Limitations and next steps

- Empty `TotalCharges` values belong to new customers (tenure 0), so filling them with 0 would be more accurate than the median
- Add recommendations for retention and a simple churn prediction model

## How this was built

This is a learning project. I built it with help from an AI assistant and studied the code. The notebook comments and chart titles are partly in Azerbaijani.

## Author

Ali Karimov | [LinkedIn](https://www.linkedin.com/in/ali-karimov-505409367)
