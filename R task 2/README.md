# E-Commerce Customer Satisfaction Prediction

## Project Overview
This project uses Machine Learning to predict customer satisfaction levels based on customer purchase behavior. The model is trained using an E-Commerce Customer Behavior dataset and Logistic Regression algorithm.

---

## Dataset
Dataset: E-Commerce Customer Behavior

Target Variable:
- Satisfaction Level

Features Used:
- Gender
- Age
- City
- Membership Type
- Total Spend
- Items Purchased
- Discount Applied
- Days Since Last Purchase

Dropped Columns:
- Customer ID
- Average Rating

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Machine Learning Algorithm
- Logistic Regression

---

## Project Workflow

### Step 1: Import Libraries
Import all required Python libraries.

### Step 2: Load Dataset
Read the dataset using Pandas.

### Step 3: Data Preprocessing
- Remove unnecessary columns.
- Encode categorical and boolean values using LabelEncoder.
- Separate features and target.

### Step 4: Split Dataset
Split the dataset into Training (70%) and Testing (30%).

### Step 5: Feature Scaling
Apply StandardScaler to normalize the feature values.

### Step 6: Train Model
Train the Logistic Regression model.

### Step 7: Prediction
Predict customer satisfaction on test data.

### Step 8: Model Evaluation
Evaluate using:
- Accuracy Score
- Classification Report
- Confusion Matrix

### Step 9: Feature Importance
Visualize feature importance using model coefficients.

---

## Evaluation Metrics
- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Output
The project generates:
- Accuracy Score
- Classification Report
- Confusion Matrix
- Feature Importance Graph

---

## Libraries Required

```bash
pip install pandas numpy matplotlib scikit-learn
```

---

## Dataset File

```
E-commerce Customer Behavior - Sheet1.csv
```

---

## Author

**Maria Anitta G**

Bachelor of Computer Applications (BCA)

Kamaraj College

Year of Passing: 2027
