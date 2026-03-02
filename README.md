# Telecom Customer Churn Prediction

## Problem
Telecom companies lose 15-25% customers every year.
It costs 5-10x more to acquire a new customer than retain one.
This project predicts which customers are likely to churn.

## Models Used
- Logistic Regression
- Random Forest Classifier
- XGBoost ✅ (Best Model - 90% Accuracy)

## Libraries
Python, Pandas, NumPy, Scikit-learn, XGBoost, SHAP, SMOTE, Seaborn, Matplotlib, SQLAlchemy

## Key Findings
- Customers with International Plan churn the most
- Customers with 4+ customer service calls churn 4x more
- High daytime call duration is a strong churn indicator

## Result
XGBoost achieved 90% test accuracy with no overfitting.
SHAP used for model explainability.
SMOTE used to handle class imbalance.
