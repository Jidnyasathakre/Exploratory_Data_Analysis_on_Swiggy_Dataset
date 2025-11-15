# 📊 Exploratory Data Analysis on Swiggy Dataset

This project performs a detailed **Exploratory Data Analysis (EDA)** on a Swiggy restaurant menu dataset, with the goal of understanding pricing trends, restaurant distribution, customer ratings, and category-wise insights across different Indian states and cities.

The analysis focuses on data cleaning, preprocessing, visualization, and extracting meaningful business insights that can help food delivery platforms or restaurant partners make data-driven decisions.

---

## 🔍 **Project Overview**

The notebook walks through the complete EDA workflow:

### **1. Data Loading & Structure Understanding**

* Imported dataset containing restaurant details, menu items, locations, prices, ratings, and categories.
* Explored structure using `.head()`, `.shape()`, `.info()`, and descriptive statistics.

### **2. Data Cleaning & Preprocessing**

* Renamed columns to a clean, consistent `snake_case` format.
* Checked for missing values (none found).
* Identified and removed duplicate entries.
* Handled outliers in the **Price** column using IQR.
* Ensured data integrity (e.g., valid rating ranges, price checks).

### **3. Exploratory Data Analysis**

* Frequency distributions of:

  * **States**, **Cities**, and **Locations**
  * **Dish categories**
  * **Dish names**
* Univariate and multivariate analysis using histograms, box plots, and value counts.
* Identified most popular categories and high-performing locations/dishes.

### **4. Statistical Insights**

* Summary statistics for numerical features.
* Correlation analysis:

  * Weak or no correlation between **Price** and **Rating**.
  * Slight positive correlation between **Rating** and **Rating_Count**.

### **5. Key Findings**

* Karnataka has the highest number of listed dishes.
* Bengaluru dominates the dataset with large restaurant and dish variety.
* Popular dish category trends vary by location.
* Higher prices do **not** necessarily translate to better ratings.
* Some dishes have extremely high rating counts, indicating popularity and reliability.

### **6. Business Value**

* Identify top-performing states and cities for strategic expansion.
* Optimize pricing strategies based on category and location.
* Improve visibility for high-rated but low-count dishes.
* Focus on customer engagement in underperforming regions.

---

## 📁 **Datset Used**
<a href="https://github.com/Jidnyasathakre/Exploratory_Data_Analysis_on_Swiggy_Dataset/blob/main/swiggy_all_menus_india.csv"></a>

---

## 🛠️ **Tech Stack**

* **Python**
* **Pandas**, **NumPy**
* **Matplotlib**
* **Jupyter Notebook**

---
