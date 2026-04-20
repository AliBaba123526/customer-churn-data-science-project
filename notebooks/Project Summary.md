# Customer Churn Prediction Project

## Overview
This project aims to predict customer churn using machine learning techniques. The goal is to identify customers who are likely to leave a telecom company, allowing the business to take proactive retention actions.

## Data Preparation
- Handled missing values
- Converted data types (e.g., TotalCharges)
- Encoded categorical variables using one-hot encoding

## Exploratory Data Analysis (EDA)
Key insights:
- Customers with low tenure are more likely to churn
- Higher monthly charges are associated with higher churn
- Month-to-month contracts have higher churn rates

## Model Development
- Model used: Logistic Regression
- Data split into training and testing sets
- Features scaled using StandardScaler

## Model Evaluation
- Initial accuracy: ~78%
- Confusion matrix revealed poor detection of churn cases

## Model Improvement
- Adjusted classification threshold from 0.5 → 0.3
- Recall for churn improved from 52% → 76%

## Business Insight
Improving recall ensures more at-risk customers are identified, helping businesses reduce customer loss even at the cost of some false positives.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Key Learning
This project demonstrates the importance of:
- Understanding evaluation metrics (precision, recall)
- Interpreting model performance beyond accuracy
- Aligning model decisions with business goals
