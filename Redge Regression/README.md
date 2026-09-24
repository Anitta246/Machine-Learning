# 🚗 EV Car Price Prediction

## 📌 Project Overview

This project focuses on predicting the **price of electric vehicles (EVs) in India** using machine learning.

The project uses **Ridge Regression** to predict EV prices based on important vehicle features such as:

* Brand
* Model
* Range
* Power
* Battery

The dataset is processed using Python and machine learning techniques, including feature scaling, one-hot encoding, and train-test splitting.

---

## 🎯 Objective

The main objective of this project is to:

* Analyze an Indian EV car dataset.
* Identify important features related to EV prices.
* Preprocess numerical and categorical data.
* Build a **Ridge Regression** machine learning model.
* Evaluate the model using MAE, RMSE, and R² score.
* Compare different Ridge regularization values (`alpha`).

---

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data handling and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Visualization
* **Scikit-learn** – Machine learning

### Machine Learning Techniques

* Train-Test Split
* StandardScaler
* OneHotEncoder
* ColumnTransformer
* Pipeline
* Ridge Regression

---

## 📊 Dataset

The project uses an Indian EV dataset:

```text
ev_car_India_dataset.csv
```

The main features used for prediction are:

| Feature | Description      |
| ------- | ---------------- |
| Brand   | EV manufacturer  |
| Model   | EV model         |
| Range   | Driving range    |
| Power   | Vehicle power    |
| Battery | Battery capacity |
| Price   | Target variable  |

---

## ⚙️ Project Workflow

```text
EV Dataset
     ↓
Data Loading
     ↓
Data Inspection
     ↓
Feature Selection
     ↓
Train-Test Split
     ↓
Data Preprocessing
     ↓
Ridge Regression
     ↓
Model Prediction
     ↓
Model Evaluation
```

---

## 🧠 Model

### Ridge Regression

Ridge Regression is used to predict the EV price while applying L2 regularization to reduce the effect of multicollinearity and help control model complexity.

Different `alpha` values are tested:

```python
alphas = [0.01, 0.1, 1, 10, 100]
```

The model uses a pipeline containing:

1. **StandardScaler** for numerical features.
2. **OneHotEncoder** for categorical features.
3. **Ridge Regression** for price prediction.

---

## 📈 Evaluation Metrics

The model is evaluated using:

### MAE – Mean Absolute Error

Measures the average absolute difference between actual and predicted prices.

### RMSE – Root Mean Squared Error

Measures prediction error while giving more weight to larger errors.

### R² Score

Measures how well the model explains the variation in EV prices.

Both **training** and **testing** metrics are calculated.

---

## 📂 Project Structure

```text
EV-Car-Price-Prediction/
│
├── ev_car_latest.ipynb
├── ev_car_India_dataset.csv
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Open the notebook

Open:

```text
ev_car_latest.ipynb
```

using **Jupyter Notebook** or **Google Colab**.

### 3. Upload the dataset

Make sure the following dataset is available:

```text
ev_car_India_dataset.csv
```

### 4. Run the cells

Execute the notebook cells sequentially to preprocess the data, train the Ridge Regression model, and evaluate its performance.

---

## 📌 Results

The notebook compares Ridge Regression models using different `alpha` values:

```text
0.01
0.1
1
10
100
```

The performance is evaluated using:

* Train MAE
* Train RMSE
* Train R²
* Test MAE
* Test RMSE
* Test R²

The results are stored in a DataFrame for comparison.

---

## 🔮 Future Improvements

* Add more EV features such as charging time, seating capacity, and efficiency.
* Perform detailed exploratory data analysis.
* Compare Ridge Regression with other regression algorithms.
* Perform hyperparameter tuning.
* Deploy the model as a web application.
* Add interactive EV price prediction.

---

## 👩‍💻 Author

**Maria Anitta**

BCA Student | Aspiring Data Analyst & Full Stack Developer
