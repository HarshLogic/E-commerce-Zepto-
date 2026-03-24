# 🛒 Zepto E-commerce Data Analysis (SQL Project)

## 📌 Overview

This project focuses on analyzing a real-world e-commerce dataset inspired by Zepto to extract meaningful business insights related to product pricing, inventory, and category performance. The analysis is performed using SQL by simulating real-world data analyst tasks such as data cleaning, querying, and insight generation.

---

## 🎯 Objectives

* Perform data cleaning and preprocessing on raw dataset
* Analyze product categories, pricing trends, and inventory distribution
* Identify high-performing and low-performing products
* Evaluate discount strategies and their effectiveness
* Generate actionable insights for business decision-making

---

## 🛠️ Tools & Technologies

* SQL (MySQL / PostgreSQL)
* Excel / CSV (for dataset handling)
* Data Analysis & EDA Techniques

---

## 📂 Dataset Description

The dataset contains information about:

* Product Name
* Category
* Price & Discounted Price
* Discount Percentage
* Stock Availability
* Ratings (if applicable)

---

## 🔍 Key Analysis Performed

### 1. Data Cleaning

* Removed duplicate records
* Handled missing values
* Standardized inconsistent formats (pricing, discounts)

### 2. Exploratory Data Analysis (EDA)

* Distribution of products across categories
* Price range analysis
* Discount trend analysis

### 3. SQL-Based Insights

* Category-wise product count and performance
* Top expensive and least expensive products
* Products with highest discounts
* Stock availability and inventory gaps
* Aggregated insights using GROUP BY and HAVING

---

## 📊 Key Insights

* Identified categories with **highest product availability and demand**
* Found **pricing inconsistencies** across similar product categories
* Detected products with **high discounts but low stock**, indicating demand-supply mismatch
* Highlighted opportunities for **inventory and pricing optimization**

---

## 📈 Sample SQL Queries

```sql
-- Top 5 most expensive products
SELECT product_name, price
FROM products
ORDER BY price DESC
LIMIT 5;

-- Category-wise product count
SELECT category, COUNT(*) AS total_products
FROM products
GROUP BY category;

-- Products with highest discount
SELECT product_name, discount_percentage
FROM products
ORDER BY discount_percentage DESC
LIMIT 10;
```

---

## 🚀 Future Improvements

* Build interactive dashboards using Power BI or Tableau
* Integrate Python for advanced data visualization
* Apply machine learning for demand forecasting
* Automate data pipeline for real-time analysis

---

## 📌 Conclusion

This project demonstrates practical SQL skills and the ability to derive business insights from raw data. It reflects real-world data analyst responsibilities including data cleaning, querying, and decision-making support.

---

## 👤 Author

**Harshvardhan Sinha**

* 📧 Email: [harshvardhansinha17@gmail.com](mailto:harshvardhansinha17@gmail.com)
* 🔗 GitHub: https://github.com/HarshLogic
* 🔗 LinkedIn: https://www.linkedin.com/in/harshlogic/

---
