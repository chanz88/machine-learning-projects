# Random Forest
A Random Forest project to predict whether a telecom customer will churn (leave the service) based on demographic, account, and service usage features, and to compare its performance with a Decision Tree

## Dataset used
This project uses the Telco Customer Churn dataset, which contains 7,043 customers and information such as gender, senior citizen status, partner, dependents, tenure, phone and internet services, online security, tech support, streaming services, contract type, paperless billing, payment method, monthly charges, and total charges

The target variable is Churn, which indicates whether a customer left the service (Yes) or stayed (No). The data is imbalanced

## What I Did
- Data cleaning
- Train test split
- Categorical feature encoding (Ordinal Encoding for binary and contract features, One-Hot Encoding for nominal features)
- Feature scaling with StandardScaler
- Building a preprocessing and modeling pipeline
- Random Forest
- Comparing Random Forest with Decision Tree
- Hyperparameter tuning with Grid Search and Stratified 5-Fold Cross-Validation
- Model evaluation
