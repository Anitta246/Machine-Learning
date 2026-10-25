# Credit Card Fraud Detection Using Machine Learning

## Project Overview
This project focuses on detecting fraudulent credit card transactions using Machine Learning. It uses the **Random Forest Classifier** algorithm to classify transactions as genuine or fraudulent.

The main goal is to identify suspicious transactions and improve financial transaction security.

## Objectives
- Detect fraudulent credit card transactions.
- Analyze transaction data using Python.
- Train a machine learning model using Random Forest.
- Evaluate model performance using different metrics.
- Visualize fraud detection results.

## Technologies Used
- **Programming Language:** Python
- **Platform:** Google Colab / Jupyter Notebook
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Machine Learning Algorithm:** Random Forest Classifier

## Dataset
The project uses the `creditcard.csv` dataset containing credit card transaction records.

**Dataset Features:**
- Time – Transaction time information.
- V1 to V28 – Anonymized transaction features.
- Amount – Transaction amount.
- Class – Transaction category.

**Class Labels:**
- 0 – Genuine Transaction
- 1 – Fraudulent Transaction

## Project Workflow
1. Import the required Python libraries.
2. Load the credit card transaction dataset.
3. Perform data exploration and preprocessing.
4. Handle missing target values.
5. Split the dataset into 80% training and 20% testing data.
6. Train the Random Forest Classifier.
7. Predict genuine and fraudulent transactions.
8. Evaluate the model performance.
9. Visualize the confusion matrix, feature importance, and ROC curve.

## Machine Learning Algorithm
**Random Forest Classifier**

Random Forest is a supervised machine learning algorithm that combines multiple decision trees to make predictions.

It helps classify credit card transactions as genuine or fraudulent based on transaction features.

## Model Evaluation
The model is evaluated using:

- **Precision:** Measures how many predicted fraud transactions are actually fraudulent.
- **Recall:** Measures how many actual fraud transactions are correctly detected.
- **F1-Score:** Balances precision and recall.
- **Confusion Matrix:** Displays correct and incorrect predictions.
- **ROC-AUC Score:** Measures the model's ability to distinguish between genuine and fraudulent transactions.

## How to Run the Project
1. Download or open the project notebook.
2. Open it in Google Colab or Jupyter Notebook.
3. Install the required Python libraries.
4. Upload the `creditcard.csv` dataset.
5. Run all notebook cells in order.
6. View the predictions, evaluation metrics, and visualizations.

## Project Output
The project generates:
- Genuine and fraudulent transaction predictions.
- Confusion matrix.
- Precision, Recall, and F1-Score.
- ROC-AUC score and ROC curve.
- Feature importance visualization.
- Fraud detection analysis.

## Conclusion
This project demonstrates how Machine Learning can be used to detect fraudulent credit card transactions. The Random Forest Classifier analyzes transaction patterns and predicts whether a transaction is genuine or fraudulent.

The project provides practical experience in data preprocessing, machine learning model training, prediction, evaluation, and data visualization.
