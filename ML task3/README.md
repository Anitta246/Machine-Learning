# 🏠 Real Estate Property Price Analysis using K-Means Clustering

## 📌 Project Overview

This project focuses on analyzing real estate property data using **Machine Learning**, specifically the **K-Means Clustering algorithm**. The project groups properties based on important factors such as **property price** and **square feet area**.

The **Elbow Method** is used to determine the optimal number of clusters. After applying K-Means clustering, the properties are categorized into three groups:

* **Casual** – Lower price-to-area properties
* **Mid-Range** – Medium price-to-area properties
* **Luxury** – Higher price-to-area properties

The project also uses **Folium** to create a **real interactive map**. Users can explore property locations and view important details such as location, price, square feet, price per square feet, cluster number, and property category.

---

## 🎯 Project Objectives

The main objectives of this project are:

1. To clean and preprocess real estate property data.
2. To analyze the relationship between property price and square feet.
3. To apply the K-Means clustering algorithm for property segmentation.
4. To use the Elbow Method to identify the optimal number of clusters.
5. To classify properties into Casual, Mid-Range, and Luxury categories.
6. To visualize property clusters using graphs.
7. To create a real interactive geographical map using Folium.
8. To display property information interactively based on latitude and longitude.
9. To generate a final processed dataset containing clustering results and categories.

---

## 🧠 Machine Learning Algorithm

### K-Means Clustering

K-Means is an unsupervised machine learning algorithm used to divide data into a predefined number of clusters.

In this project, K-Means uses the following features:

* Property Price
* Super Built-up Area / Square Feet

The data is standardized using `StandardScaler` before applying K-Means to ensure that features with different scales do not dominate the clustering process.

The algorithm groups similar properties based on their price and area characteristics.

---

## 📊 Elbow Method

The **Elbow Method** is used to determine a suitable value for `K`, which represents the number of clusters.

The algorithm is tested with different values of `K`, and the **inertia** value is calculated for each cluster count.

The resulting Elbow graph helps identify the point where increasing the number of clusters provides diminishing improvement.

In this project, **K = 3** is used to create three main property categories:

```text
Cluster 1 → Casual
Cluster 2 → Mid-Range
Cluster 3 → Luxury
```

---

## 🏷️ Property Categories

The project creates three property categories based on the comparison between property price and square feet.

### 🟢 Casual

Properties with relatively lower price per square feet are classified as **Casual**.

### 🟡 Mid-Range

Properties with medium price per square feet are classified as **Mid-Range**.

### 🔴 Luxury

Properties with higher price per square feet are classified as **Luxury**.

The final category is assigned based on the K-Means cluster characteristics and average price-per-square-feet values.

---

## 🗺️ Interactive Property Map

The project uses **Folium** to create an interactive real estate map.

The dataset contains:

* Latitude
* Longitude

These coordinates are used directly to plot properties on the map.

Each property marker displays information including:

* 📍 Location
* 💰 Price
* 📐 Square Feet
* 💵 Price per Square Feet
* 🔢 K-Means Cluster
* 🏷️ Property Category

The map also uses marker clustering to organize multiple properties in nearby locations.

The generated map can be opened in a web browser and explored interactively.

---

## 🔄 Project Workflow

```text
Real Estate Dataset
        ↓
Data Loading
        ↓
Data Cleaning
        ↓
Missing Value Handling
        ↓
Price & Square Feet Selection
        ↓
Feature Scaling
        ↓
Elbow Method
        ↓
K-Means Clustering
        ↓
Cluster Analysis
        ↓
Casual / Mid-Range / Luxury
        ↓
K-Means Visualization
        ↓
Latitude & Longitude
        ↓
Folium Interactive Map
        ↓
Final Processed Dataset
```

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Machine Learning

* Scikit-learn
* K-Means Clustering
* StandardScaler

### Data Processing

* Pandas
* NumPy

### Data Visualization

* Matplotlib

### Interactive Mapping

* Folium
* Folium MarkerCluster

### Development Environment

* Jupyter Notebook / Google Colab
* Python 3.x

---

## 📦 Required Libraries

Install the required libraries using:

```bash
pip install pandas numpy matplotlib scikit-learn folium
```

---

## 📁 Project Structure

```text
Real-Estate-ML-Project/
│
├── real_estate_project.ipynb
│
├── dataset.csv
│
├── elbow_method.png
│
├── kmeans_clusters.png
│
├── real_estate_interactive_map.html
│
├── real_estate_clustered_dataset.csv
│
└── README.md
```

---

## 📈 Project Outputs

The project generates the following outputs:

### 1. Elbow Method Graph

```text
elbow_method.png
```

This graph helps analyze the optimal number of clusters.

### 2. K-Means Cluster Visualization

```text
kmeans_clusters.png
```

This visualization shows properties grouped according to their cluster categories.

### 3. Interactive Real Estate Map

```text
real_estate_interactive_map.html
```

This HTML file provides an interactive map where users can explore property locations and details.

### 4. Clustered Dataset

```text
real_estate_clustered_dataset.csv
```

This file contains the original property information along with:

* Price Area Ratio
* K-Means Cluster
* Casual / Mid-Range / Luxury Category
* Latitude
* Longitude

---

## 💡 Key Features

* ✅ Real estate data preprocessing
* ✅ Property price analysis
* ✅ Square feet analysis
* ✅ Price-per-square-feet comparison
* ✅ Feature scaling
* ✅ Elbow Method
* ✅ K-Means clustering
* ✅ Three property categories
* ✅ Casual classification
* ✅ Mid-Range classification
* ✅ Luxury classification
* ✅ K-Means visualization
* ✅ Real interactive Folium map
* ✅ Property marker clustering
* ✅ Interactive property information popup
* ✅ Final clustered dataset export

---

## 🎓 Applications

This project can be useful for:

* Real estate property analysis
* Property market segmentation
* Price comparison
* Investment analysis
* Real estate recommendation systems
* Identifying luxury property locations
* Identifying affordable property areas
* Geographic property visualization

---

## 🚀 Future Enhancements

The project can be improved in the future by adding:

1. A web-based dashboard using Streamlit or Flask.
2. Property search and filtering functionality.
3. Price range filters.
4. Category-based map filtering.
5. Interactive charts and dashboards.
6. Real-time property data.
7. Property recommendation using machine learning.
8. Predictive house price models using regression algorithms.
9. Advanced clustering using DBSCAN or Hierarchical Clustering.
10. Integration with a real estate database.

## Output

### 1. Elbow Method Graph

<img width="3000" height="1800" alt="elbow_method" src="https://github.com/user-attachments/assets/2a723f04-a966-41bc-9d59-b2246e47b87f" />

### 2. K-Means Cluster Visualization

<img width="3000" height="2100" alt="kmeans_clusters" src="https://github.com/user-attachments/assets/70b06f8d-d15a-43e4-b2a4-394b8aa120f1" />

