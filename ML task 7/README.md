# 📊 Sales Dataset Analysis

## 📌 Project Overview

This project performs **Sales Data Analysis** using Python. The dataset is cleaned by removing missing values, cancelled invoices, invalid transactions, and duplicate records. A new **TotalAmount** column is created to calculate the total sales value.

The project also uses **RFM Analysis** to understand customer purchasing behavior.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📂 Dataset

The project uses a sales dataset containing information such as:

* Invoice
* Customer ID
* Invoice Date
* Quantity
* Price

## 🔄 Data Cleaning

The following preprocessing steps are performed:

* Removed records with missing **Customer ID**
* Removed cancelled invoices starting with **"C"**
* Removed transactions with invalid **Quantity**
* Removed transactions with invalid **Price**
* Removed duplicate records

## 💰 Feature Engineering

A new column called **TotalAmount** is created using:

`TotalAmount = Quantity × Price`

This helps calculate the total value of each transaction.

## 👥 RFM Analysis

Customer behavior is analyzed using:

* **Recency** – Number of days since the customer's last purchase
* **Frequency** – Number of unique purchases made by the customer
* **Monetary** – Total amount spent by the customer

## 🚀 Conclusion

This project demonstrates how raw sales data can be cleaned, processed, and analyzed to understand **sales performance and customer purchasing behavior**. RFM analysis helps identify valuable customers based on their purchasing activity.

## 📦 Libraries Installation

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

## ▶️ How to Run

```bash
jupyter notebook Sales_dataset.ipynb
```

Then run all the cells to perform the sales data cleaning and RFM analysis.
