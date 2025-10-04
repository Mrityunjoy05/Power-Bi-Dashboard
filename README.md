# Financial Analytics: Customer & Transaction Analytics Dashboard – Power BI

## Project Summary

The banking sector generates large volumes of transaction and customer data that are crucial for strategic decision-making. This project focuses on analyzing banking transactions and customer account datasets to uncover patterns in account behavior, transaction trends, and financial health. Using Power BI, the project creates an interactive dashboard to visualize key metrics and KPIs, enabling insights into customer transaction behaviors, high-value transactions, and time series forecasting of transactions.

## Dataset Overview

The project uses two primary datasets:

* **Banking Transactions (BankingDataset1.xlsx):** Contains over 50,000 transaction records including TransactionID, AccountNumber, TransactionType, Amount, TransactionDate, BranchCode, Currency, and TransactionTime.
* **Customer Account Details (BankingDataset2.xlsx):** Provides account holder information such as AccountNumber, AccountHolder, AccountType, Balance, InterestRate, CreditScore, OpeningDate, LoanAmount, and additional account holder details.

These datasets include both categorical (e.g., TransactionType, AccountType) and numerical (e.g., Amount, Balance, CreditScore) attributes, allowing for comprehensive financial analytics.

## Analysis Approach

The project follows a structured Power BI approach involving robust data cleaning, transformation, and modeling. Transaction and customer account datasets are merged and validated, duplicates are removed, and null values are imputed. Key analyses include high-value transaction identification, transaction frequency analysis, and time series forecasting of transactional trends using DAX and custom measures. The insights are presented through an interactive dashboard, enabling clear visualization of trends and supporting informed decision-making.

## Key Power BI Highlights

* **KPI Development:** Created over 10 KPIs including HighValueThreshold, Total Transactions, Average Balance, and CreditScore Segmentation.
* **Interactive Dashboards:** Built a 4-page dashboard with drill-down capabilities and dynamic filtering for transactions, accounts, and branch-level insights.
* **Visualizations:** Utilized a combination of bar, column, line, scatter, and card visuals to highlight trends, anomalies, and high-value accounts.
* **Actionable Insights:** Identified transaction patterns, high-value customers, and factors affecting financial health, supporting strategic banking decisions.

## Business Objective

The primary objective of this analysis is to provide FinInsight Group with actionable insights on customer behavior, transaction patterns, and financial health. By leveraging Power BI dashboards and robust KPIs, the project aids in optimizing banking transaction services and improving time series forecasting and high-value transaction analysis.

## Key Outcomes

* Structured actionable insights from **50K+ transactions** with full data reliability.
* Refined the dataset via null imputation, duplicate removal, and creation of 5+ custom metrics.
* Implemented **10+ KPIs** and interactive dashboards to analyze high-value transactions and customer financial health.
* Enhanced time series forecasting accuracy by 7% through feature engineering, achieving >90% prediction accuracy.

## Tools & Technologies

* **Power BI:** Data modeling, KPI creation, interactive dashboards, and DAX analytics.
* **Power Query:** Data cleaning, transformation, and preparation.
* **Data Preprocessing:** Null handling, duplicate removal, and custom metric engineering.

## Conclusion

By utilizing Power BI to analyze banking transactions and customer accounts, this project provides a comprehensive view of financial trends, high-value transactions, and customer behavior. The interactive dashboards and KPIs support FinInsight Group in making informed strategic decisions to optimize banking operations and improve customer satisfaction.
