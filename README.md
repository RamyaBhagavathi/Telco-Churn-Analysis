Telco Customer Churn Analysis
Project Overview
This project focuses on predicting customer churn for a telecom company using supervised machine learning models. The goal is to build an accurate and recall-optimized classifier to identify customers at risk of leaving, enabling the company to implement targeted retention strategies.

Key Objectives
Analyze telecom data to identify churn-driving patterns

Build and compare multiple classification models

Improve recall to minimize false negatives (missed churners)

Simulate an end-to-end model pipeline for business readiness

Dataset Description
Source: Public telecom customer dataset (7,043 records)
(originally hosted on Kaggle)

Key Features:

Contract type

Monthly charges

Tenure

Payment method

Senior citizen status

Churn label (Yes/No)

Workflow Summary
Data Cleaning: Handled missing values and corrected data types

Exploratory Data Analysis (EDA): Visualized churn trends by tenure, contract, charges

Feature Engineering: Converted categorical variables, encoded labels

Model Building: Logistic Regression, Random Forest, SVM

Model Tuning: Used GridSearchCV for hyperparameter optimization

Threshold Tuning: Adjusted decision thresholds to increase recall

Pipeline Creation: Built a reusable Scikit-learn pipeline using StandardScaler + Logistic Regression

Model Evaluation: Compared models using F1 Score, Precision, Recall, and Confusion Matrix

Model Performance
Best Model: Logistic Regression (with tuning and threshold adjustment)

Original Recall: 0.51

Final Recall: 0.73 (after threshold tuning)

F1 Score: 0.56

The model successfully captures the majority of churners, making it suitable for real-time customer retention strategies.

Tools and Technologies Used
Python (Jupyter Notebook)

NumPy, Pandas

Scikit-learn

Matplotlib, Seaborn

Repository Contents
telco_churn_analysis.ipynb: Source code, analysis, and results

README.md: This documentation

Author
Ramya Bhagavathi
GitHub: @RamyaBhagavathi

