# churnzerocode
# Bank Customer Churn Prediction

## Overview
This project predicts whether a bank customer is likely to leave the bank (churn) using Machine Learning models.

The objective is to help banks identify high-risk customers early and improve customer retention strategies.

---

# Problem Statement

Customer churn directly impacts a bank’s:
- revenue
- customer acquisition cost
- long-term profitability

This project builds predictive models to detect customers likely to churn based on:
- demographics
- banking behavior
- account activity

---

# Dataset Features

| Feature | Description |
|---|---|
| CreditScore | Customer credit score |
| Geography | Customer country/location |
| Gender | Male/Female |
| Age | Customer age |
| Tenure | Years with bank |
| Balance | Account balance |
| NumOfProducts | Number of bank products used |
| HasCrCard | Has credit card or not |
| IsActiveMember | Active membership status |
| EstimatedSalary | Estimated salary |
| Exited | Target variable (1 = churned, 0 = retained) |

---

# Project Workflow

Raw Dataset  
↓  
Data Inspection  
↓  
Data Cleaning  
↓  
Exploratory Data Analysis (EDA)  
↓  
Categorical Encoding  
↓  
Feature Selection  
↓  
Train-Test Split  
↓  
Stratified Sampling  
↓  
Feature Scaling  
↓  
Class Imbalance Handling  
↓  
Model Training  
↓  
Model Evaluation  
↓  
SHAP Explainability  
↓  
Business Insights & Retention Strategies

---

# Models Used

- Logistic Regression
- Balanced Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

---

# Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

---

# Key Findings

- Age was the strongest churn indicator.
- Customers with more products showed higher churn tendencies.
- Inactive members were more likely to churn.
- German customers showed comparatively higher churn probability.
- Random Forest delivered the best balance of recall and overall predictive performance.

---

# SHAP Explainability

SHAP (SHapley Additive exPlanations) was used to:
- understand feature impact
- explain model decisions
- identify key churn-driving factors

---

# Business Recommendations

- Target high-age customers with loyalty plans.
- Improve engagement for inactive members.
- Reduce product complexity for overloaded customers.
- Design region-specific retention campaigns.
- Provide proactive support for high-balance customers.

---

# Installation

Install dependencies using:

```bash
pip install -r requirements.txt
