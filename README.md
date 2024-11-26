# Paisabazaar Banking Fraud EDA

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) of banking data to identify patterns, trends, and potential fraud risks. The dataset includes financial and behavioral data about customers, which can be used to assess their creditworthiness and detect anomalies that may indicate fraudulent activities.

## Dataset Information

- **Number of Records:** 54,618
- **Number of Columns:** 28
- **File Size:** ~11.7 MB

### Data Columns:

| Column Name                 | Data Type | Description                              |
|-----------------------------|-----------|------------------------------------------|
| ID                          | int64     | Unique transaction identifier            |
| Customer_ID                 | int64     | Unique identifier for customers          |
| Month                       | int64     | Month of transaction                     |
| Name                        | object    | Customer's name                          |
| Age                         | float64   | Age of the customer                      |
| SSN                         | float64   | Customer's Social Security Number        |
| Occupation                  | object    | Occupation type                          |
| Annual_Income               | float64   | Yearly income of the customer            |
| Monthly_Inhand_Salary       | float64   | Monthly salary received                  |
| Num_Bank_Accounts           | float64   | Number of active bank accounts           |
| Num_Credit_Card             | float64   | Number of credit cards held              |
| Interest_Rate               | float64   | Interest rate on loans                   |
| Num_of_Loan                 | float64   | Number of loans taken                    |
| Type_of_Loan                | object    | Loan types availed                       |
| Delay_from_due_date         | float64   | Days delayed in payment                  |
| Num_of_Delayed_Payment      | float64   | Total number of delayed payments         |
| Changed_Credit_Limit        | float64   | Frequency of credit limit changes        |
| Num_Credit_Inquiries        | float64   | Number of credit inquiries made          |
| Credit_Mix                  | object    | Credit mix quality (e.g., Good/Bad)      |
| Outstanding_Debt            | float64   | Amount of outstanding debt               |
| Credit_Utilization_Ratio    | float64   | Credit utilization percentage            |
| Credit_History_Age          | float64   | Age of credit history in years           |
| Payment_of_Min_Amount       | object    | Whether minimum payment is made          |
| Total_EMI_per_month         | float64   | Total monthly EMI amount                 |
| Amount_invested_monthly     | float64   | Monthly investment amount                |
| Payment_Behaviour           | object    | Behavioral description of payment habits |
| Monthly_Balance             | float64   | Balance at the end of the month          |
| Credit_Score                | object    | Credit score category (e.g., High/Low)   |

## Objectives

1. Understand the data structure and ensure its integrity.
2. Analyze financial patterns and behavioral trends.
3. Detect and visualize anomalies or patterns indicative of fraud.
4. Derive actionable insights from the data to assist in fraud detection.

## Steps to Perform

1. **Data Loading and Cleaning:**
   - Handle missing values (e.g., `Interest_Rate`, `Num_of_Loan`).
   - Ensure proper data types and correct any inconsistencies.

2. **Exploratory Data Analysis:**
   - Descriptive statistics for numerical and categorical columns.
   - Visualizations to understand distributions, correlations, and trends.
   - Analyze relationships between features like income, credit score, and loan performance.

3. **Anomaly Detection:**
   - Identify outliers in numeric data (e.g., Monthly Balance, Credit Utilization Ratio).
   - Check for unusual patterns in payment behavior and delayed payments.

4. **Insights and Recommendations:**
   - Summarize findings from EDA.
   - Suggest preventive measures or further steps for fraud detection.

## Tools and Libraries

- **Python Libraries:**
  - pandas, NumPy for data manipulation
  - Matplotlib, Seaborn, Plotly for visualizations
  - scikit-learn for anomaly detection
- **Environment:**
  - Jupyter Notebook or any Python IDE

## Conclusion

This project aims to leverage EDA techniques to uncover valuable insights from the Paisabazaar banking dataset, helping identify fraudulent activities and improve decision-making processes in financial services.
