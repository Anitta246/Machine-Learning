# Customer Churn Prediction

## 📌 Project Overview

This project is based on **Customer Churn Prediction using Machine Learning**. The main objective is to predict whether a customer will leave the bank or continue using its services.

The model analyzes different customer details such as credit score, age, balance, tenure, number of products, and activity status to identify customers who are likely to churn.

## 📂 Dataset

The dataset contains customer information such as:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Has Credit Card
* Is Active Member
* Estimated Salary

### Target Variable

**Exited**

* `0` - Customer did not leave the bank
* `1` - Customer left the bank

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## 🔄 Data Preprocessing

The following steps are performed:

1. Load the dataset
2. Check for missing values
3. Remove unnecessary columns
4. Encode categorical variables
5. Split the dataset into training and testing data
6. Apply feature scaling
7. Prepare the data for machine learning

## 🤖 Machine Learning Model

Machine Learning algorithms are used to train the dataset and predict customer churn.

The project helps identify customers who may potentially leave the bank based on their personal, financial, and account-related information.

## 🚀 Project Workflow

Dataset
↓
Data Preprocessing
↓
Feature Engineering
↓
Train-Test Split
↓
Feature Scaling
↓
Model Training
↓
Prediction
↓
Model Evaluation

## 📁 Project Structure

```text
Customer-Churn-Prediction/
│
├── Churn_Modelling.csv
├── churn_prediction.ipynb
└── README.md
```

## 🎯 Project Objective

The main objective of this project is to build a machine learning model that can predict customer churn and help banks identify customers who are at risk of leaving.

## 📊 Expected Outcome

The trained machine learning model predicts whether a customer is likely to stay with the bank or leave the bank. This can help businesses take appropriate customer retention strategies.
