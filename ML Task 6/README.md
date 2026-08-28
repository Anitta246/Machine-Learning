# 📚 Online Education Dataset Analysis using Machine Learning

## 📌 Project Overview

This project focuses on analyzing an **Online Education Dataset** and predicting student performance using Machine Learning techniques.

The project analyzes the relationship between student engagement, total clicks, and their final results. Data visualization and Logistic Regression are used to understand and predict whether a student will pass or not.

---

## 🎯 Objectives

The main objectives of this project are:

* Analyze student performance in online education.
* Understand the relationship between **engagement level** and student pass rate.
* Handle missing values in the dataset.
* Visualize student engagement and performance.
* Build a Machine Learning model using **Logistic Regression**.
* Predict student pass/fail outcomes based on total clicks.

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab / Jupyter Notebook

---

## 📂 Dataset

The project uses an **Online Education Dataset** containing information related to student engagement and academic performance.

Important columns used in this project include:

* `engagement_level` – Student engagement category such as Low, Medium, or High.
* `total_clicks` – Total number of clicks or interactions made by the student.
* `pass_flag` – Indicates whether the student passed or not.
* `final_result` – Final academic result of the student.

---

## 🔍 Exploratory Data Analysis

### 1. Viewing the Dataset

The dataset is loaded using Pandas and the first few records are displayed using:

```python
df.head()
```

This helps us understand the structure and columns of the dataset.

---

### 2. Analyzing Final Results

The distribution of student final results is analyzed using:

```python
df["final_result"].value_counts()
```

This shows how many students belong to each final result category.

---

### 3. Pass Rate Based on Engagement Level

The average pass rate is calculated for different engagement levels:

```python
df.groupby("engagement_level")["pass_flag"].mean()
```

This helps identify whether students with higher engagement have better chances of passing.

---

## 📊 Data Visualization

A bar chart is created to visualize the relationship between student engagement level and pass rate.

```python
sns.barplot(
    x="engagement_level",
    y="pass_flag",
    data=df
)
```

The engagement levels are categorized as:

* Low
* Medium
* High

The visualization helps understand how student engagement affects academic performance.

---

## 🧹 Data Preprocessing

Before training the Machine Learning model, missing values are checked.

```python
df[["total_clicks", "pass_flag"]].isnull().sum()
```

Missing values are handled as follows:

```python
df["total_clicks"] = df["total_clicks"].fillna(0)
df["pass_flag"] = df["pass_flag"].fillna(0)
```

This ensures that the dataset does not contain missing values in the selected columns.

---

## 🤖 Machine Learning Model

### Logistic Regression

The project uses **Logistic Regression** to predict whether a student will pass based on their total number of clicks.

### Input Feature

```text
total_clicks
```

### Target Variable

```text
pass_flag
```

---

## ⚙️ Feature Scaling

The `StandardScaler` is used to normalize the feature values.

```python
from sklearn.preprocessing import StandardScaler

scaler = StandardScaler()
X_scaled = scaler.fit_transform(x)
```

Feature scaling helps improve the performance and stability of the Logistic Regression model.

---

## 🧠 Model Training

The Logistic Regression model is created and trained using:

```python
from sklearn.linear_model import LogisticRegression

model = LogisticRegression(max_iter=1000)
model.fit(X_scaled, y)
```

The model learns the relationship between student activity (`total_clicks`) and passing status (`pass_flag`).

---

## 📈 Model Coefficient

The model coefficient is displayed using:

```python
print("Model coefficient:", model.coef_[0][0])
```

The coefficient helps understand how changes in the number of student clicks influence the probability of passing.

---

## 📊 Visualization of Engagement Levels

The project also visualizes pass rates according to the following engagement levels:

* Low
* Medium
* High

This provides a clear comparison of student performance based on engagement.

---

## 📁 Project Structure

```text
Online-Education-ML-Project/
│
├── online_education_dataset.csv
├── online_education_dataset.py
└── README.md
```

---

## 🚀 How to Run the Project

### Step 1: Clone or Download the Project

Download the project files to your computer.

### Step 2: Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Step 3: Add the Dataset

Make sure the dataset file is available:

```text
online_education_dataset.csv
```

### Step 4: Run the Python File

```bash
python online_education_dataset.py
```

Or run the code using:

* Google Colab
* Jupyter Notebook
* VS Code

---

## 📌 Key Findings

* Student engagement level can be analyzed to understand its relationship with pass rates.
* Total clicks represent student interaction with the online learning platform.
* Missing values are handled before model training.
* Logistic Regression is used to classify students based on their pass status.
* Data visualization makes it easier to understand the relationship between engagement and academic performance.

---

## 🔮 Future Improvements

The project can be improved by:

* Adding more student-related features.
* Using multiple Machine Learning algorithms.
* Comparing model accuracy.
* Adding train-test split for proper model evaluation.
* Creating a student performance prediction interface.
* Deploying the model as a web application.

---

## 👩‍💻 Author

**Maria Anitta G**

BCA Student | Aspiring Data Analyst / Software Developer

---

## ⭐ Conclusion

This project demonstrates the use of **Data Analysis, Data Visualization, Data Preprocessing, and Machine Learning** to analyze student performance in an online education environment.

Using **Pandas, Seaborn, and Logistic Regression**, the project explores how student engagement and online activity can be connected to academic outcomes.

This project provides a basic foundation for developing more advanced student performance prediction systems in the future.
