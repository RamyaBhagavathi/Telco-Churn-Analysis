Telco Customer Churn Prediction
This project focuses on analyzing customer churn behavior in a telecom company using machine learning. It includes data cleaning, exploratory data analysis (EDA), model building, evaluation, threshold tuning, and hyperparameter optimization.

Problem Statement
Customer churn is a critical problem in the telecom industry. This project aims to identify customers who are likely to discontinue the service using historical customer data. Predicting churn can help companies retain customers and reduce revenue loss.

Dataset
Source: Kaggle (Telco Customer Churn Dataset)

Records: ~7,000+

Target: Churn (Yes/No)

Steps Covered
Data Cleaning

Handled missing values

Corrected data types

Exploratory Data Analysis (EDA)

Visualized customer churn trends

Identified key churn drivers

Feature Engineering

Encoded categorical variables

Scaled numerical features

Data Preprocessing

Train-test split

Applied transformations for modeling

Modeling (Multiple Models Tried)

Logistic Regression

Random Forest

Support Vector Machine

KNN

Decision Tree

Gradient Boosting

Pipeline Integration

Used sklearn.pipeline to combine steps

Hyperparameter Tuning

Applied GridSearchCV to improve model performance

Threshold Tuning

Adjusted threshold to increase Recall (important in churn)

Best Model Performance (Logistic Regression)
Metric	Score
Accuracy	78.8%
Precision	62.4%
Recall	51.6%
F1 Score	56.5%

Key Learnings
Pipeline makes model building and testing cleaner and scalable

Threshold tuning helped tailor the model for real business goals

Evaluating with multiple metrics (not just accuracy) gives a realistic view

Future Improvements
Try advanced models like XGBoost (if environment allows)

Deploy as a simple web app using Flask or Streamlit

Use SHAP or LIME for feature interpretation

Files in this Repo
File Name	Description
telco_churn_analysis.ipynb	Full notebook with code + markdown
README.md	Project overview (this file)
model.pkl (optional)	Saved trained model using joblib

Author
Trisha Ramya B
Passionate about data and solving business problems through ML.
