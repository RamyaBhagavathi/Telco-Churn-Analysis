# Telco Customer Churn Analysis

## Project Overview
This project analyzes customer data from a telecom company to predict churn using various classification algorithms. 
The objective is to develop a model that can identify customers who are likely to discontinue the service, allowing the company to take proactive retention actions.

## Goals
- Understand key factors influencing customer churn
- Build and compare machine learning models
- Improve model recall to capture more potential churners
- Deploy a practical model pipeline suitable for real-world use

## Dataset
- Source: Kaggle – Telco Customer Churn
- Records: 7,043 customer records with features like contract type, tenure, payment method, and churn status

## Workflow Summary
1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Model Building (Logistic Regression, Random Forest, SVM, etc.)
5. Model Comparison
6. Pipeline Creation (Logistic Regression with StandardScaler)
7. Hyperparameter Tuning using GridSearchCV
8. Threshold Tuning for better recall
9. Model Evaluation and Conclusion

## Model Performance
- Best performing model: Logistic Regression with hyperparameter tuning
- F1 Score: 0.56
- Recall: 0.51 (improved to 0.73 after threshold adjustment)

## Tools and Technologies Used
- Python
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Folder Structure
- `telco_churn_analysis.ipynb`: Jupyter notebook with code, analysis, and results
- `README.md`: Project overview and documentation

## Author
Ramya Bhagavathi  
GitHub: [RamyaBhagavathi](https://github.com/RamyaBhagavathi)
