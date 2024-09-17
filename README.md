# Customer Churn Prediction

## Problem Statement

Customer churn refers to when customers stop using company services. In this project, we aim to predict customer churn using a historical dataset of customer behavior. This prediction helps businesses take proactive measures to retain valuable customers.

## Dataset Description

The dataset consists of customer demographic details, account information, services subscribed, and churn status. The target variable is `Churn`, where `Yes` means the customer has churned, and `No` means they have not.

**Columns**:
- `gender`, `SeniorCitizen`, `Partner`, `Dependents`, etc. (Demographics)
- `tenure`, `PhoneService`, `InternetService`, etc. (Account info)
- `Churn` (Target Variable)

## Objective

Our goal is to develop a machine learning model that accurately predicts whether a customer will churn or not. We use Logistic Regression as the base model and tune hyperparameters using GridSearchCV.

## Approach

1. Data Cleaning and Preprocessing
2. Feature Encoding and Scaling
3. Logistic Regression Model with Hyperparameter Tuning
4. Model Evaluation
5. Visualization of Key Correlations and Features

## Conclusion

- The best model achieved an accuracy of X% (replace with actual score).
- `tenure`, `MonthlyCharges`, and contract types were highly influential in predicting churn.
