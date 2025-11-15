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

### **5. Key Insights**


#### **1. State-level Orders**

* Karnataka has the highest number of orders.
* Sikkim has the lowest.
* A few states—Karnataka, Maharashtra, Telangana, Delhi, and Tamil Nadu—dominate overall orders, indicating a high concentration in metro regions.


#### **2. City-level Trends**

* Bengaluru tops the list in city-level orders.
* Most orders are concentrated in capital or major metropolitan cities.


#### **3. Location Insights**

* Gomti Nagar (Lucknow) has the highest number of orders among all individual locations.
* Some locations, such as Faridabad, receive very few orders.


#### **4. Category Analysis**

* The **“Recommended”** category receives the highest number of orders.
* Many niche categories have extremely low order counts, with more than 300 categories having only a single order.


#### **5. Dish Preferences**

* The most ordered dish is **Choco Lava Cake**.
* Other top dishes include **Veg Fried Rice, Paneer Butter Masala, Chicken Sausage, and Jeera Rice**.


#### **6. Price Distribution**

* Dish prices range from **₹0.95** (e.g., Tomato Ketchup) to **₹614** (premium pizzas/meals).
* The average dish price is approximately **₹252**.


##### **7. Ratings**

* Ratings range from **0 to 5**.
* A large number of dishes have a rating of **0**, indicating they were not rated.
* Common positive ratings include **4.3, 4.5, and 4.6**.


#### **8. Correlation Insights**

* **Price vs Rating:** Shows a weak negative correlation (higher-priced dishes do not necessarily receive higher ratings).
* **Price vs Rating Count:** Weak negative correlation.
* **Rating vs Rating Count:** Moderate positive correlation (popular dishes with more ratings tend to have higher ratings).


#### **9. Top-Rated Items**

Examples of dishes with a **5.0 rating** include:

* Schweppes Water Bottle
* Ice Americano Coffee
* Korean Spice Mix


#### **10. Most Reviewed Dish**

* **“OB Chicken Tikka”** at **Yelahanka** has the highest number of rating counts.

### **6. Business Value**

* Focus promotions on top-performing states and cities (such as Karnataka and Bengaluru).
* Promote bestsellers like **Choco Lava Cake** across new markets.
* Optimize pricing strategies, as premium pricing does not directly improve ratings.
* Increase visibility of under-ordered categories and dishes to help balance demand.

---

## 📁 **Dataset Used**
- <a href="https://github.com/Jidnyasathakre/Exploratory_Data_Analysis_on_Swiggy_Dataset/blob/main/swiggy_all_menus_india.csv">swiggy_all_menus_india</a>

---

## 🛠️ **Tech Stack**

* **Python**
* **Pandas**, **NumPy**
* **Matplotlib**
* **Jupyter Notebook**

---
