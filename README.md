# Telecom Customer Churn Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Telecom Customer Churn dataset to understand customer behavior and identify the key factors that contribute to customer churn.

The analysis explores customer demographics, subscription services, contract types, payment methods, tenure, monthly charges, and additional telecom services to uncover meaningful business insights that can help reduce customer churn.


## Business Problem

Customer churn is a major challenge for telecom companies because losing existing customers leads to decreased revenue, higher customer acquisition costs, and slower business growth.

The primary objective of this project is to identify customers who are likely to churn and understand the factors influencing their decision. These insights can help telecom companies improve customer retention through personalized offers, better customer service, optimized pricing strategies, and enhanced service quality.

This project answers business questions such as:

* Which customers are more likely to churn?
* Does contract type influence customer retention?
* How does customer tenure affect churn?
* Which internet service has the highest churn rate?
* Do monthly charges impact customer churn?
* Which payment methods are associated with higher churn?
* What are the major factors contributing to customer churn?


## Dataset Information

The dataset contains information about **7,043 telecom customers**, including:

* Customer ID
* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Phone Service
* Multiple Lines
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies
* Contract Type
* Paperless Billing
* Payment Method
* Monthly Charges
* Total Charges
* Churn


## Project Workflow

1. Data Understanding
2. Data Cleaning
3. Univariate Analysis
4. Bivariate Analysis
5. Business Problem Analysis
6. Business Recommendations


## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook


## Key Analysis Performed

### Data Understanding

* Dataset Overview
* Data Types
* Statistical Summary
* Missing Value Analysis

### Data Cleaning

* Handling Missing Values
* Data Type Conversion
* Duplicate Check
* Data Consistency Verification

### Univariate Analysis

* Churn Distribution
* Gender Distribution
* Contract Type Distribution
* Internet Service Distribution
* Payment Method Distribution
* Monthly Charges Distribution
* Tenure Distribution

### Bivariate Analysis

* Contract Type vs Churn
* Internet Service vs Churn
* Monthly Charges vs Churn
* Tenure vs Churn
* Payment Method vs Churn
* Gender vs Churn
* Senior Citizen vs Churn
* Online Security vs Churn
* Tech Support vs Churn

### Business Analysis

* Overall Customer Churn Rate
* Average Monthly Charges by Churn
* Average Tenure by Churn
* Service-wise Churn Analysis
* Contract-wise Churn Analysis
* High-Risk Customer Identification


## Project Outcome

This analysis identifies the major factors responsible for customer churn and provides actionable insights that can help telecom companies improve customer retention, increase customer satisfaction, and make data-driven business decisions.


## Business Recommendations

* Encourage customers to choose longer-term contracts through attractive offers.
* Improve customer support services to enhance customer satisfaction.
* Promote Online Security and Tech Support services to reduce churn.
* Focus on retaining new customers during their initial months.
* Review pricing strategies for customers with high monthly charges.
* Launch personalized retention campaigns for customers at high risk of churn.


## How to Run This Project

### The Quick Way (No Git Required)

1. Click the green **Code** button on this GitHub repository.
2. Select **Download ZIP**.
3. Extract the ZIP file.
4. Ensure the dataset (`Telco-Customer-Churn.csv`) is in the project folder.
5. Open Command Prompt or Terminal and run:

```bash
pip install pandas numpy matplotlib seaborn notebook
jupyter notebook
```

6. Open the notebook and run all cells.


## Project Structure

```
Telco-Customer-Churn-EDA/
│
├── README.md
├── Telco_Customer_Churn_EDA.ipynb
├── Telco-Customer-Churn.csv
├── requirements.txt
└── Business_Recommendations.md
```


## Author

Priya Patel 
Aspiring Data Analyst

📧 Email: patelpriya18217@gmail.com  
💻 GitHub: https://github.com/priyapatel96140


If you found this project useful, don't forget to give it a **Star**!
