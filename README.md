
#  Customer Churn Prediction & Analysis

An end-to-end Customer Churn Analysis and Prediction project using the Telco Customer Churn dataset.

The goal of this project is to understand **why customers leave**, identify the most important factors affecting churn, and build a machine learning model capable of predicting customer churn.

---

##  Project Overview

Customer churn is one of the biggest challenges for subscription-based businesses.

This project focuses on:

- Understanding customer demographics
- Identifying churn patterns
- Performing Exploratory Data Analysis (EDA)
- Building machine learning models
- Predicting whether a customer is likely to churn
- Generating business insights for customer retention

---

## 📂 Dataset

Dataset Used:

**Telco Customer Churn Dataset**

The dataset contains information about:

- Customer demographics
- Internet services
- Phone services
- Contract type
- Payment methods
- Monthly charges
- Total charges
- Customer tenure
- Churn status

### Dataset Features

| Category | Features |
|----------|----------|
| Demographics | Gender, SeniorCitizen, Partner, Dependents |
| Services | PhoneService, InternetService, StreamingTV, TechSupport |
| Account Information | Contract, PaymentMethod, PaperlessBilling |
| Financial | MonthlyCharges, TotalCharges |
| Target Variable | Churn |

---

#  Exploratory Data Analysis (EDA)

The following analyses are performed:

###  Missing Value Analysis

- Identify missing values
- Calculate percentage of missing data
- Handle missing values appropriately

###  Customer Distribution

- Churn vs Non-Churn customers
- Gender distribution
- Senior citizen analysis
- Partner and dependent analysis

###  Service Analysis

Study how churn changes with:

- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies

###  Financial Analysis

Analyze:

- Monthly Charges
- Total Charges
- Contract Type
- Payment Method
- Tenure

---

#  Key Insights

Some major observations:

 Month-to-month customers churn the most.

Customers with longer contracts have significantly lower churn rates.

 Customers without Online Security and Tech Support are more likely to churn.

 Higher monthly charges are associated with increased churn probability.

 Longer tenure customers are less likely to churn.

---

# 🤖 Machine Learning Pipeline

The project includes:

1. Data Cleaning
2. Missing Value Handling
3. Feature Encoding
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Churn Prediction

---

## Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost *(Coming Soon)*

---

#  Visualizations

This project includes:

- Countplots
- Pie Charts
- KDE Plots
- Histograms
- Boxplots
- Correlation Heatmaps
- Churn Distribution Graphs

---

#  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

#  Future Improvements

The project will be expanded with:

###  SQL Analysis

- Customer segmentation queries
- Churn rate by contract type
- Revenue analysis
- Window functions and CTEs

---

###  Power BI Dashboard

Interactive dashboard showing:

- Churn Percentage
- Revenue Loss
- Contract-wise Churn
- Customer Segments
- Monthly Charges Analysis
- Retention Insights

---

###  SHAP Explainability

Add Explainable AI using SHAP:

- Global feature importance
- Local customer explanations
- Waterfall plots
- Force plots

Example:

> Customer churned mainly because:
>
> - Month-to-Month Contract
> - High Monthly Charges
> - Lack of Tech Support

---

###  Streamlit Web App

A deployed web application where users can:

- Enter customer details
- Predict churn probability
- View explanation behind prediction
- Get retention recommendations

---

#  Repository Structure

```bash
Customer-Churn-Analysis/

│── customer_churn.ipynb
│── Telco-Customer-Churn.csv
│── README.md
│── images/
│── models/
```

---

#  Business Impact

Reducing churn by even a small percentage can lead to:

- Higher customer retention
- Increased recurring revenue
- Better customer experience
- Lower acquisition costs

This project aims to transform raw customer data into actionable business decisions.

---

##  Future Goal

Transform this project into a complete:

**Explainable AI Customer Retention Platform**

using:

- SQL
- Power BI
- XGBoost
- SHAP
- Streamlit
- Gemini API
- FastAPI

where the model not only predicts churn but also explains:

> **Why the customer is leaving and what the company can do to retain them.**

---

### Made with ❤️ while learning Machine Learning and Data Science.