# Bank Customer Churn Prediction

## Project Overview
This project predicts whether a bank customer is likely to leave the bank (Customer Churn) using Machine Learning. The model analyzes customer information such as age, gender, country, credit score, balance, and account details to classify customers as either **Churn** or **Not Churn**.

The project is implemented in **Python** using **Scikit-learn** and a **Random Forest Classifier**.

---

## Objective
The main objective of this project is to:
- Predict customer churn accurately.
- Help banks identify customers who are likely to leave.
- Support customer retention strategies through data-driven insights.

---

## Dataset
The dataset used is:

**Bank Customer Churn Prediction.csv**

### Features
- customer_id
- credit_score
- country
- gender
- age
- tenure
- balance
- products_number
- credit_card
- active_member
- estimated_salary
- churn (Target Variable)

---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Algorithm
**Random Forest Classifier**

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## Project Workflow

### 1. Import Libraries
Required Python libraries are imported.

### 2. Load Dataset
The Bank Customer Churn dataset is loaded using Pandas.

### 3. Data Exploration
- Display first few records
- Check dataset information
- Find missing values
- Generate descriptive statistics

### 4. Data Visualization
A count plot is created to visualize the distribution of churned and retained customers.

### 5. Data Preprocessing
- Encode categorical columns using LabelEncoder.
- Features:
  - country
  - gender

### 6. Feature Selection
Input Features:
- credit_score
- country
- gender
- age
- tenure
- balance
- products_number
- credit_card
- active_member
- estimated_salary

Target:
- churn

### 7. Train-Test Split
The dataset is divided into:
- 80% Training Data
- 20% Testing Data

### 8. Feature Scaling
StandardScaler is used to normalize feature values.

### 9. Model Training
A Random Forest Classifier is trained using the training dataset.

### 10. Model Evaluation
The trained model is evaluated using **Accuracy Score**.

---

## Output
The notebook displays:

- Dataset preview
- Dataset information
- Missing value analysis
- Statistical summary
- Customer churn visualization
- Model Accuracy

Example:

```
Model Accuracy: 0.86
```

*(The accuracy may vary depending on the dataset and random state.)*

---

## Project Structure

```
Bank-Customer-Churn-Prediction/
│
├── Chrun.ipynb
├── Bank Customer Churn Prediction.csv
└── README.md
```

---

## Applications
- Customer Retention
- Banking Analytics
- Marketing Campaigns
- Risk Management
- Customer Relationship Management (CRM)

---

## Future Enhancements
- Hyperparameter tuning
- Cross-validation
- Feature importance analysis
- Confusion Matrix
- ROC Curve
- Precision, Recall, and F1-Score comparison
- Deployment using Flask or Streamlit

---

## Conclusion
This project demonstrates how Machine Learning can be applied to predict customer churn in the banking sector. By identifying customers who are likely to leave, banks can take proactive measures to improve customer satisfaction and reduce churn. The Random Forest Classifier provides reliable performance and serves as a strong baseline model for customer churn prediction.

---

## Author
**Maria Anitta G**

BCA Student  
Kamaraj College, Thoothukudi
