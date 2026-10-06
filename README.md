# Customer Churn & Retention Analytics

## 📌 Project Overview

This project analyzes customer churn for a telecommunications company to understand **why customers leave, which customer segments are more likely to churn, and how businesses can improve customer retention**.

The project combines **Python, Machine Learning, and Power BI** to turn customer data into actionable business insights.

## 🎯 Business Problem

Customer churn directly impacts revenue and customer lifetime value.

The key questions addressed in this project are:

* Which customers are more likely to churn?
* What factors are associated with customer churn?
* What are the most common reasons customers leave?
* Can machine learning help identify churn patterns?
* How can businesses use these insights to improve retention?

## 🛠️ Tools & Technologies

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Logistic Regression
* Power BI

## 📊 Analysis Performed

* Customer churn distribution
* Churn by contract type
* Churn by internet service
* Churn by payment method
* Churn by tenure
* Churn by monthly charges
* Churn reasons
* Customer demographic analysis
* Churn score analysis

## 🤖 Machine Learning

A **Logistic Regression** model was developed to predict customer churn.

The workflow included:

* Data preprocessing
* Categorical variable encoding
* Missing-value handling
* Train-test split
* Model training
* Churn prediction
* Model evaluation
* Feature importance analysis

## 📈 Power BI Dashboard

An interactive Power BI dashboard was created to monitor:

* Total Customers
* Churned Customers
* Churn Rate
* Average Monthly Charges
* Churn by Contract
* Churn by Internet Service
* Churn by Payment Method
* Top Churn Reasons
* Churn Trend by Tenure
* Interactive Contract and Internet Service filters

## 💡 Key Business Insights

* Month-to-month customers show higher churn compared with customers on longer-term contracts.
* Customers with shorter tenure are more likely to churn.
* Monthly charges show a relationship with customer churn.
* Churn behavior varies across payment methods and internet service types.
* Churn reasons can help businesses identify areas where retention strategies can be improved.

## 📂 Project Structure

```text
Customer-Churn-Retention-Analytics
│
├── Data
│   ├── Telco_customer_churn.xlsx
│   └── customer_churn_powerbi.csv
│
├── python
│   └── customer_churn_analysis.ipynb
│
├── PowerBI
│   └── Customer-Churn-Retention-Analytics.pbix
│
└── README.md
```

## 📌 Dataset

IBM Telco Customer Churn dataset containing customer demographics, services, contract information, charges, churn status, and churn reasons.

## ⚠️ Disclaimer

This project is created for educational and portfolio purposes using a public fictional telecom dataset.
