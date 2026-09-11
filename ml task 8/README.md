# EV Car Price Prediction – India

## 📌 Project Overview

This project analyzes an **Electric Vehicle (EV) car dataset from India** using Python and builds a **Linear Regression model** to predict EV car prices based on their driving range.

The project includes data inspection, data cleaning, model training, prediction, and model evaluation.

## 🎯 Objective

The main objectives of this project are:

- Explore EV car data in India
- Understand EV features such as price, range, power, and battery
- Build a Linear Regression model
- Predict EV car prices based on range
- Evaluate the model performance

## 📊 Dataset

The dataset contains **26 EV car records** and **6 columns**.

| Column | Description |
|---|---|
| Brand | Brand/manufacturer of the EV |
| Model | EV model name |
| Price | Price of the EV |
| Range | Driving range of the EV |
| Power | Power of the EV |
| Battery | Battery capacity |

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## 🔄 Project Workflow

1. Import required Python libraries
2. Load the EV dataset using Pandas
3. Display the first few records
4. Check dataset information
5. Check the shape of the dataset
6. Handle missing values in Range and Price
7. Select Range as the input feature
8. Select Price as the target variable
9. Split the dataset into training and testing data
10. Train the Linear Regression model
11. Calculate slope and intercept
12. Predict EV prices
13. Compare actual and predicted prices
14. Visualize actual vs predicted prices
15. Evaluate the model using regression metrics

## 🤖 Machine Learning Model

### Linear Regression

Linear Regression is used to predict the **price of an EV based on its driving range**.

- **Input Feature:** Range
- **Target Variable:** Price
- **Test Size:** 20%
- **Random State:** 42

### Model Parameters

- **Slope:** 0.1414
- **Intercept:** -34.3961

## 📈 Model Evaluation

The model performance was evaluated using the following metrics:

| Metric | Result |
|---|---:|
| MAE | 17.5081 |
| MSE | 410.5502 |
| RMSE | 20.2620 |
| R² Score | 0.2179 |

An **Actual vs Predicted Price** graph is also used to visualize the model predictions.

## 🔍 Result

The model shows a positive relationship between **EV range and price**. However, the R² score of **0.2179** shows that range alone does not explain most of the variation in EV prices.

Other features such as **Power, Battery capacity, Brand, and Model** can be included in future analysis to improve the prediction accuracy.

## 📁 Project Structure

```text
EV-Car-India/
│
├── ev_car_India_dataset.csv
├── ev_car_india_dataset.ipynb
└── README.md
