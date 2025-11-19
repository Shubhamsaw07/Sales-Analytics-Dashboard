# Sales Analytics Project — SQL EDA + Power BI Dashboard

## Overview

This project demonstrates an end-to-end **Sales Analytics system** built using **MySQL** for data cleaning & EDA, and **Power BI** for interactive dashboarding.
The goal is to understand sales performance across **time, products, customers, and regions** using a well-designed **star schema**.

---

## 🧱 **Project Architecture**

### **Database: MySQL**

Structured using a **Star Schema**:

* **fact_sales**
* **dim_date**
* **dim_customer**
* **dim_product**
* **dim_store**

### **Reporting: Power BI**

* DAX Measures
* Interactive Visuals
* Multi-page report
* Filters, slicers, and drilldowns

---

## 🧪 **1. SQL Exploratory Data Analysis (EDA)**

### ✔ Data Profiling

* Row counts
* Checking for NULL values
* Detecting duplicates
* Validating foreign key relationships

### ✔ Data Cleaning

* Standardizing text fields
* Fixing data types
* Calculating discount percentages
* Removing or correcting invalid records

### ✔ Feature Engineering

* Seasonality fields
* Derived metrics
* Discount insights
* Customer-level aggregations

### ✔ Summary Views

Created `vw_sales_summary` to accelerate Power BI reporting.

---

## 📊 **2. Power BI Dashboard (5 Pages)**

### **📌 Page 1 — Executive Sales Overview**

* Total Sales, Units, Orders, AOV
* Monthly trend
* Sales by Category, Region, Gender
* Top 10 Products

### **📌 Page 2 — Product Performance Insights**

* Category & brand performance
* Discount vs Sales (Scatter)
* Category heatmap by month

### **📌 Page 3 — Store & Region Performance**

* Region-wise sales
* Store ranking
* Map visuals
* Store KPI table

### **📌 Page 4 — Customer Analysis**

* Total Customers & AOV
* Top customers
* Gender & country distribution

### **📌 Page 5 — Discount & Impact Analysis**

* Category discount%
* Discount vs Units
* High-discount transactions

---

## 🔧 **Tech Stack**

| Tool/Tech    | Purpose                               |
| ------------ | ------------------------------------- |
| **MySQL**    | Data storage, cleaning, EDA           |
| **SQL**      | Joins, aggregations, window functions |
| **Power BI** | Dashboard design & storytelling       |
| **DAX**      | KPI measures & calculations           |

---

## 📁 **Repository Structure**

```
📦 sales-analytics-project
 ┣ 📂 sql/
 ┃ ┣ eda_queries.sql
 ┃ ┣ cleaning_queries.sql
 ┃ ┗ summary_view.sql
 ┣ 📂 powerbi/
 ┃ ┣ dashboard.pbix
 ┣ 📂 exports/
 ┃ ┗ cleaned_data.csv
 ┣ 📄 README.md
```

---

## 🚀 **Key Insights**

* Seasonal patterns visible in monthly sales
* Top categories drive majority of revenue
* Region performance differs heavily
* Discounts increase units but reduce profitability
* Strong customer concentration in top 10%

---

## 🎯 **What I Learned**

* Designing a star schema
* SQL-based cleaning & profiling
* Creating DAX measures
* BI storytelling
* Building a multi-page interactive dashboard

---

## 📜 **How to Run the Project**

1. Import SQL files into MySQL
2. Load dimensions + fact tables
3. Run EDA queries
4. Connect Power BI to MySQL or CSV extracts
5. Open the `.pbix` file to view dashboard

---

## 🤝 **Contributions**

Feel free to fork the repo and submit pull requests.

---

## ⭐ **Show Support**

If you like this project, please **star the repository** ⭐ on GitHub!

---

If you want, I can also generate:

✅ A **GitHub project banner**
✅ A **short project description**
✅ Clean folder structure for your repo

Just ask.
