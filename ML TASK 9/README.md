# Household Energy Consumption Prediction

## 📌 Project Overview

This project predicts **household energy consumption** using machine learning. The dataset contains household-related factors such as household size, average temperature, and peak-hour usage.

A **Polynomial Regression** model is used to learn the relationship between these factors and total energy consumption.

## 🎯 Objective

The main objective of this project is to:

* Analyze household energy consumption data
* Handle missing values
* Select important input features
* Train a Polynomial Regression model
* Predict household energy consumption
* Evaluate the model using different performance metrics
* Compare actual and predicted energy consumption

## 📂 Dataset

The dataset used in this project is:

`household_energy_consumption.csv`

### Features Used

| Feature                | Description                       |
| ---------------------- | --------------------------------- |
| `Household_Size`       | Number of people in the household |
| `Avg_Temperature_C`    | Average temperature in Celsius    |
| `Peak_Hours_Usage_kWh` | Energy usage during peak hours    |

### Target Variable

`Energy_Consumption_kWh`

This is the total household energy consumption that the model predicts.

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook / Google Colab

## 🤖 Machine Learning Algorithm

### Polynomial Regression

Polynomial Regression with **degree 2** is used in this project.

The model is trained using:

* `PolynomialFeatures`
* `LinearRegression`

The dataset is divided into:

* **80% Training Data**
* **20% Testing Data**

## 🔄 Project Workflow

1. Import required Python libraries
2. Load the household energy consumption dataset
3. Explore the first few records
4. Check dataset shape and information
5. Generate statistical summary
6. Remove missing values
7. Select input and target variables
8. Split the dataset into training and testing sets
9. Apply Polynomial Features with degree 2
10. Train the Linear Regression model
11. Generate predictions
12. Evaluate model performance
13. Visualize actual vs predicted energy consumption

## 📊 Model Evaluation

The following metrics are used to evaluate the model:

* **MAE (Mean Absolute Error)** – Measures the average absolute difference between actual and predicted values.
* **MSE (Mean Squared Error)** – Measures the average squared difference between actual and predicted values.
* **RMSE (Root Mean Squared Error)** – Measures the prediction error in the same unit as energy consumption.
* **R² Score** – Measures how well the model explains the variation in energy consumption.

## 📈 Visualization

The project includes an **Actual vs Predicted Energy Consumption** scatter plot.

This visualization helps compare the model's predictions with the actual energy consumption values.

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone <your-repository-url>
```

### 2. Install Required Libraries

```bash
pip install pandas matplotlib scikit-learn
```

### 3. Add the Dataset

Place the following file in the working directory:

```text
household_energy_consumption.csv
```

### 4. Open the Notebook

Open:

```text
household_energy_consumption.ipynb
```

You can run it using **Jupyter Notebook** or **Google Colab**.

## 📁 Project Structure

```text
Household-Energy-Consumption/
│
├── household_energy_consumption.ipynb
├── household_energy_consumption.csv
└── README.md
```

## 🔮 Future Improvements

* Compare Polynomial Regression with other regression algorithms
* Add more household-related features
* Perform feature selection
* Tune model parameters
* Create an interactive energy consumption dashboard
* Deploy the model as a web application

## 👩‍💻 Author

**Maria Anitta**

BCA – Bachelor of Computer Applications
