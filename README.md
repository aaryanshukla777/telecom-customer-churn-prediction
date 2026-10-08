# Telecom Customer Churn Prediction

## Overview

This project uses Python and machine learning to analyze telecom customer behavior and predict customer churn. The analysis focuses on identifying patterns associated with customer attrition and evaluating classification models for churn prediction.

## Objectives

- Analyze customer characteristics and churn patterns
- Clean and preprocess the dataset for machine learning
- Explore factors associated with customer churn
- Build and compare classification models
- Evaluate model performance using multiple metrics
- Translate analytical findings into customer retention recommendations

## Project Workflow

### 1. Data Cleaning
- Converted relevant variables into appropriate data types
- Handled missing values
- Removed non-predictive identifiers

### 2. Exploratory Data Analysis
Analyzed relationships between churn and variables such as:
- Contract type
- Monthly charges
- Customer tenure
- Customer service and technology-related services
- Other customer attributes

### 3. Data Preprocessing
- Encoded categorical variables
- Standardized numerical features
- Split the dataset into training and testing sets

### 4. Machine Learning

The project compares:

- Logistic Regression
- Random Forest

### 5. Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Results

The Logistic Regression model achieved:

- **Accuracy:** 81.62%
- **F1 Score:** 62.63%

The models were compared to determine the more suitable approach for identifying customers at risk of churn.

## Business Insights

The analysis highlights customer characteristics associated with higher churn risk and supports potential retention strategies such as:

- Targeted incentives for customers on shorter-term contracts
- Retention offers for customers with higher monthly charges
- Encouraging adoption of relevant support and security services
- Prioritizing newer customers for proactive retention initiatives

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

text
telecom-customer-churn-prediction/
│
├── Customer_Churn_Prediction.ipynb
└── README.md
