# Financial Risk Analysis with Python – BlackRock

## Project Overview

This project focuses on analyzing customer financial behavior and identifying risk patterns using transactional data. With increasing digital transactions, financial institutions need to monitor customer activity, detect anomalies, and reduce financial risks.

The goal of this project is to use Python-based data analysis to uncover transaction trends, segment customers, and identify high-risk financial behavior.


## Objective

To build a data-driven financial analysis system that:

* Analyzes customer transaction behavior
* Identifies high-risk accounts and anomalies
* Segments customers based on activity and balance
* Provides insights to reduce financial risk and improve decision-making


## Dataset Description

The dataset contains customer financial transaction details, including:

* Account information (Account Type, Customer ID)
* Transaction details (Credit/Debit, Amount, Date)
* Account balance after transactions
* Risk score and credit rating
* Customer tenure and regional information


## Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib / Seaborn
* Statistical Analysis (Z-score, IQR, Hypothesis Testing)



## Project Workflow

### Data Cleaning & Preparation

* Removed invalid and inconsistent financial entries
* Converted transaction amounts into numerical format
* Standardized date formats and categories

### Transaction Analysis

* Calculated monthly and yearly transaction trends
* Compared credit vs debit patterns over time
* Identified top and bottom performing accounts
* Detected dormant accounts based on inactivity


### Customer Segmentation

* Grouped customers into High, Medium, and Low activity levels
* Segmented based on transaction volume and average balance
* Identified:

  * High net inflow accounts
  * Low balance high-frequency accounts
  * Risk-prone accounts with negative balances


### Financial Risk Identification

* Detected accounts with frequent large withdrawals
* Analyzed balance volatility using statistical measures
* Identified anomalies using Z-score and IQR methods
* Highlighted suspicious or irregular transaction behavior


### Visualization & Analysis

* Created visualizations for transaction trends and patterns
* Compared customer segments and risk profiles
* Conducted exploratory data analysis for insights


### Hypothesis Testing

* Tested whether high transaction volume accounts have higher balances
* Performed statistical validation of customer segmentation


## Key Insights

* High transaction activity does not always indicate high account balance
* Certain accounts show irregular transaction behavior, indicating potential risk
* Dormant accounts can be identified using inactivity patterns
* Customers with high volatility in balance are more prone to financial risk
* Credit and debit trends vary significantly across customer segments


## Recommendations

* Monitor high-risk accounts using anomaly detection models
* Improve customer segmentation for targeted financial strategies
* Implement alerts for unusual transaction behavior
* Encourage engagement for dormant accounts
* Use data-driven insights to strengthen risk management policies


## Conclusion

This project demonstrates how Python-based data analysis can be used to understand customer financial behavior, detect risks, and support better financial decision-making using data-driven insights.
