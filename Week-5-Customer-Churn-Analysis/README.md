# Customer Churn Analysis and Prediction

## Project Overview

This project analyzes customer churn using the Telco Customer Churn dataset. The main goal is to understand why customers may leave a service and build a machine learning model to predict customer churn.

## Dataset

- Source: Kaggle
- Dataset: Telco Customer Churn
- Dataset ID: `blastchar/telco-customer-churn`
- CSV File: `WA_Fn-UseC_-Telco-Customer-Churn.csv`

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Project Workflow

1. Load the dataset.
2. Understand the dataset structure.
3. Check missing values and duplicate records.
4. Clean the `TotalCharges` column.
5. Handle missing values.
6. Remove the `customerID` column.
7. Perform exploratory data analysis.
8. Convert categorical data using one-hot encoding.
9. Split the data into training and testing sets.
10. Scale the features.
11. Train a Logistic Regression model.
12. Make predictions.
13. Evaluate the model.
14. Analyze important factors affecting churn.
15. Generate business insights and recommendations.

## Exploratory Data Analysis

The project includes visualizations for:

- Customer churn distribution
- Churn by contract type
- Monthly charges distribution
- Churn by internet service

## Machine Learning

A Logistic Regression model is used to predict whether a customer will churn.

The model uses:

- 80% training data
- 20% testing data
- StandardScaler for feature scaling

## Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix
- ROC Curve
- AUC Score

## Feature Importance

Logistic Regression coefficients are analyzed to identify the top factors that influence customer churn.

## Business Insights

The prediction model can help identify customers who have a higher risk of leaving. Businesses can use these insights to improve customer retention through better service, personalized offers, and suitable long-term plans.

## Conclusion

This project demonstrates how data analysis and machine learning can be used to understand customer churn and support business decision-making.
