# Telco-customer-churn
Telco customer churn
Step-by-Step Explanation and Implementation Guide for Customer Churn Prediction

1. Data Collection
Objective: Obtain a dataset containing customer features and churn labels.
Dataset: Use the Telco Customer Churn dataset from Kaggle.

python
Copy
import pandas as pd

# Load data
data = pd.read_csv('telco_churn.csv')
data['Churn'] = data['Churn'].map({'Yes': 1, 'No': 0})
