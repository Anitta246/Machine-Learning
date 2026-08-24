Churn Modelling Dataset

Project Overview

This dataset contains customer information from a banking business and is commonly used for customer churn prediction.

The main objective is to analyze customer characteristics and predict whether a customer is likely to leave the bank.

Dataset: Churn Modelling

Records: 10,000 customers

Features: 13 input columns

Target: Exited

Problem Type: Binary Classification

Dataset Columns

Column

Description

RowNumber

Unique row number

CustomerId

Unique customer ID

Surname

Customer surname

CreditScore

Customer's credit score

Geography

Customer's country/region

Gender

Customer gender

Age

Customer age

Tenure

Number of years the customer has been with the bank

Balance

Customer's account balance

NumOfProducts

Number of bank products used by the customer

HasCrCard

Whether the customer has a credit card (1 = Yes, 0 = No)

IsActiveMember

Whether the customer is an active member (1 = Yes, 0 = No)

EstimatedSalary

Estimated customer salary

Exited

Target variable: 1 = Customer left the bank, 0 = Customer stayed

Target Variable

The target column is:

Exited

0 → Customer stayed

1 → Customer exited/churned

This makes the dataset suitable for supervised machine learning classification.

Suggested Machine Learning Workflow

Load the CSV dataset.

Explore the data using descriptive statistics and visualizations.

Check for missing values and duplicate records.

Remove identifier columns that are not useful for prediction, such as RowNumber and CustomerId.

Encode categorical columns such as Geography and Gender.

Split the data into training and testing sets.

Scale numerical features when required.

Train classification models.

Evaluate the models using suitable classification metrics.

Use the best-performing model to predict customer churn.

Possible Machine Learning Algorithms

You can experiment with:

Logistic Regression

Decision Tree

Random Forest

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Gradient Boosting

XGBoost

Example Python Setup

import pandas as pd

df = pd.read_csv("Churn_Modelling (3) - Churn_Modelling (3).csv")

print(df.head())
print(df.shape)
print(df.info())
print(df.isnull().sum())

Dataset Statistics

Total rows: 10,000

Total columns: 14

Numerical and categorical features are included.

The target variable is Exited.

Project Goal

The goal of a churn modelling project using this dataset is to build a machine learning model that can identify customers who are at higher risk of leaving the bank.

Such a model can help a bank:

Identify customers at risk of churn

Understand important churn factors

Plan customer retention strategies

Improve customer satisfaction

Reduce customer loss

File

The dataset is provided as a CSV file:

Churn_Modelling (3) - Churn_Modelling (3).csv
