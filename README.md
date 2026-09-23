# Customer Churn Data Preparation & EDA

## 📌 Project Overview

This project focuses on preparing and exploring a Telecom Customer Churn dataset.

The goal is to clean the customer data, perform feature engineering, analyze customer churn patterns, and identify important insights through exploratory data analysis (EDA).

## 🎯 Objectives

- Understand the customer churn dataset
- Clean missing and inconsistent data
- Perform feature engineering
- Encode categorical variables
- Analyze customer churn patterns
- Create meaningful visualizations
- Generate a cleaned dataset for further analysis

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Dataset

The project uses the Telecom Customer Churn dataset.

The dataset contains customer information such as:

- Customer demographics
- Tenure
- Contract type
- Internet services
- Monthly charges
- Total charges
- Churn status

## 🔧 Data Preparation

The following preprocessing steps were performed:

1. Loaded and inspected the dataset
2. Converted `TotalCharges` to numeric format
3. Handled missing values
4. Created tenure groups
5. Created an average monthly spending feature
6. Converted Yes/No values into numerical values
7. Applied one-hot encoding to categorical variables

## 📈 Exploratory Data Analysis

The following analyses were performed:

- Churn distribution
- Contract type vs. churn
- Correlation heatmap
- Monthly charges by churn status

## 🔍 Top 5 Insights

1. After data cleaning, the dataset contains 7,032 customers.
2. 1,869 customers churned, while 5,163 customers did not churn.
3. The overall observed churn rate is approximately 26.57%.
4. Customers who churned had higher average monthly charges than customers who did not churn.
5. Month-to-month contract customers had a higher observed churn percentage than customers with one-year or two-year contracts.

## 📁 Project Structure

```text
Customer_Churn_EDA/
│
├── Customer_Churn_EDA.ipynb
│
├── output/
│   └── customer_churn_cleaned.csv
│
└── README.md