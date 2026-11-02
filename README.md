# 📊 Customer Churn Analysis & Prediction | Telecom Analytics

### Understanding Customer Behavior and Identifying Churn Risk in the Telecommunications Industry

**Python • Pandas • NumPy • Exploratory Data Analysis • Statistical Analysis • Machine Learning Preparation**

## 📌 Project Overview

Customer churn is a significant challenge in the telecommunications industry, affecting revenue, customer retention, and long-term business performance.

This project analyzes customer information from **Interconnect**, a fictional telecommunications company, to identify patterns associated with service cancellations and establish a foundation for predictive modeling.

The project combines multiple datasets containing customer demographics, contracts, billing information, and telecommunications services.

**Business Goal:** Identify customers at greater risk of canceling their services and support data-driven customer retention strategies.

## 🎯 Project Objectives

- Explore customer behavior and contract characteristics.
- Clean and integrate multiple data sources.
- Identify patterns associated with customer churn.
- Analyze financial and service-related variables.
- Prepare a reliable dataset for machine learning.
- Develop a strategy for future churn prediction.

## 🛠️ Technologies & Skills

| Technology | Application |
|---|---|
| Python | Data processing and analysis |
| Pandas | Data cleaning, transformation, and merging |
| NumPy | Numerical operations |
| Matplotlib | Statistical visualizations |
| Seaborn | Exploratory visualizations |
| Jupyter Notebook | Analysis and documentation |

**Key Skills:** Exploratory Data Analysis (EDA), Data Cleaning, Feature Engineering, Data Integration, Business Analytics, and Predictive Modeling Planning.

## 📂 Dataset Description

The analysis uses four datasets:

| Dataset | Description |
|---|---|
| `contract.csv` | Customer contracts, payment methods, and billing information |
| `personal.csv` | Customer demographic characteristics |
| `internet.csv` | Internet services and additional subscriptions |
| `phone.csv` | Telephone service information |

The datasets are integrated using the `customerID` identifier.

## 📊 Exploratory Data Analysis

The integrated dataset contains **7,043 customers**.

### Customer Churn Distribution

| Customer Status | Customers | Percentage |
|---|---:|---:|
| Active | 5,174 | 73.47% |
| Churned | 1,869 | 26.53% |
| **Total** | **7,043** | **100%** |

### 🔎 Key Findings

**1. Contract Type**

Customers with month-to-month contracts exhibited substantially higher churn rates than customers with longer-term agreements.

- Month-to-month: 42.71%
- One-year contracts: 11.27%
- Two-year contracts: 2.83%

**2. Payment Method**

Customers using electronic checks had a churn rate of 45.29%, compared with 15.24% for automatic credit card payments.

**3. Internet Service**

Fiber optic customers had a churn rate of 41.89%, compared with 18.96% for DSL customers.

**4. Technical Support and Online Security**

Customers without technical support or online security exhibited higher cancellation rates than customers subscribed to these services.

**5. Customer Tenure**

Customers who canceled had an average tenure of approximately 18 months, compared with 37.6 months among active customers.

These findings represent observed associations and should not be interpreted as causal relationships.

## 🔄 Project Methodology

### Phase 1 — Data Exploration and Preparation

- Inspect dataset structures and data types.
- Identify missing values and duplicates.
- Convert financial and date-related variables.
- Integrate customer information.
- Create the binary target variable `Churn`.
- Explore relationships between customer characteristics and cancellation behavior.
- Identify potential data leakage.

### Phase 2 — Predictive Modeling (Planned)

- Prepare features for machine learning.
- Split data into training and testing sets.
- Train and compare classification models.
- Evaluate predictive performance using appropriate metrics.
- Interpret results and identify potential business applications.

## 💡 Business Insights

The exploratory findings suggest that contract duration, payment method, internet service type, technical support, and customer tenure may be valuable indicators for customer retention analysis.

These insights can help guide future investigations into customer segments that may benefit from targeted retention strategies.

## 📈 Project Status

**Exploratory Data Analysis completed. Predictive modeling planned.**

The current version documents the initial analysis, dataset integration, and preliminary findings. Model training, evaluation, and final performance metrics will be added in subsequent updates.

## 👩‍💻 Author

**Andressa Cruz Miranda**

Computer Science | Data Analytics | Python | Machine Learning

[GitHub Profile](https://github.com/Andressa202)

*Developed as part of the TripleTen Data Science program.*

