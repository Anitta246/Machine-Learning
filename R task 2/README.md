# Customer Satisfaction Prediction using Machine Learning

## Project Overview
This project predicts the **Customer Satisfaction Level** (Satisfied, Neutral, or Unsatisfied) using Machine Learning techniques. The model analyzes customer demographics, shopping behavior, spending patterns, and purchase history to classify the customer's satisfaction level.

---

## Dataset Information

The dataset contains customer shopping behavior and satisfaction details.

### Features

| Column Name | Description |
|-------------|-------------|
| Customer ID | Unique customer identifier |
| Gender | Male / Female |
| Age | Customer age |
| City | Customer's city |
| Membership Type | Gold, Silver, Bronze |
| Total Spend | Total amount spent |
| Items Purchased | Number of items purchased |
| Average Rating | Customer rating |
| Discount Applied | Whether discount was applied (True/False) |
| Days Since Last Purchase | Days from last purchase |
| Satisfaction Level | Target variable |

---

## Problem Type

**Machine Learning Classification**

Target Variable:

```
Satisfaction Level
```

Classes:

- Satisfied
- Neutral
- Unsatisfied

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Machine Learning Workflow

### Step 1
Import required libraries.

### Step 2
Load the dataset.

### Step 3
Check dataset information and missing values.

### Step 4
Encode categorical variables using LabelEncoder.

### Step 5
Separate Features (X) and Target (y).

### Step 6
Split dataset into Training and Testing sets.

### Step 7
Normalize numerical features using StandardScaler.

### Step 8
Train the Random Forest Classifier.

### Step 9
Predict customer satisfaction.

### Step 10
Evaluate the model using:

- Accuracy Score
- Classification Report
- Confusion Matrix
- Feature Importance

---

## Machine Learning Model

Random Forest Classifier

Reason for choosing:

- Handles both numerical and categorical data
- High accuracy
- Reduces overfitting
- Provides feature importance

---

## Evaluation Metrics

The model performance is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Expected Output

- Customer Satisfaction Prediction
- Accuracy Score
- Classification Report
- Confusion Matrix
- Feature Importance Graph

---

## Project Structure

```
Customer_Satisfaction_Prediction/
│
├── customer_shopping_behavior.csv
├── Customer_Satisfaction_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## Conclusion

This project successfully predicts customer satisfaction based on shopping behavior and customer information. The Random Forest Classifier provides an effective solution for multi-class classification and helps businesses understand customer satisfaction for better decision-making.

---

## Future Improvements

- Hyperparameter Tuning
- Cross Validation
- XGBoost Classifier
- LightGBM
- CatBoost
- Deployment using Streamlit or Flask

---

## Author

**Maria Anitta G**

BCA – III Year

Kamaraj College

2027
