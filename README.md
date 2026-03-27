# 📊 E-commerce Funnel Analysis Using Jupyter Notebook & Power BI

---

## 🧾 Project Description

This project focuses on analyzing the **customer journey in an e-commerce platform** using funnel analysis.
The goal is to understand how users move from **product view → add to cart → purchase**, identify where users drop off, and suggest improvements to increase conversion rates.

The project uses **Jupyter Notebook** for data cleaning and analysis, and **Power BI** for building an interactive dashboard.

---

## 🎯 Objectives

* Analyze user behavior across different funnel stages
* Identify major drop-off points in the funnel
* Measure conversion rates between stages
* Evaluate performance by brand and category
* Provide actionable insights to improve conversions

---

## 🛠️ Tools Used

* **Jupyter Notebook (Python)**

  * pandas
  * numpy
  * matplotlib / seaborn

* **Power BI**

  * Dashboard creation
  * Data visualization
  * KPI tracking

---

## 📂 Dataset

The dataset contains e-commerce user activity with the following key columns:

* `event_time` – time of user action
* `event_type` – view, cart, purchase
* `product_id` – product identifier
* `category_code` – product category
* `brand` – product brand
* `price` – product price
* `user_id` – user identifier
* `user_session` – session ID

---

## 🔄 Project Workflow

### 1. Data Cleaning (Jupyter Notebook)

* Removed duplicates
* Handled missing values (filled with "Unknown")
* Converted data types
* Created new features (like month)

---

### 2. Funnel Creation

Defined funnel stages based on `event_type`:

* View
* Cart
* Purchase

---

### 3. Metrics Calculation

Calculated:

* Total Users
* Total Views
* Total Purchases
* Conversion Rate
* Stage-wise drop-off

---

### 4. Analysis

* Brand performance analysis
* Category performance analysis
* Monthly trend analysis

---

### 5. Data Export

Exported cleaned and aggregated datasets from Jupyter Notebook to CSV files for Power BI.

---

### 6. Dashboard Creation (Power BI)

Built an interactive dashboard with:

* KPI Cards (Users, Purchases, Conversion Rate, Views)
* Funnel Chart (View → Cart → Purchase)
* Brand performance chart
* Category analysis chart
* Monthly trend chart
* Slicers (Brand, Category)

---

## 📊 Key Insights

* Highest drop-off occurs between **View and Cart stage**
* Some brands show higher conversion rates than others
* Certain categories generate more purchases
* Conversion rate varies across time

---

## 💡 Recommendations

* Improve product page design to increase cart additions
* Focus on high-performing brands
* Optimize low-performing categories
* Retarget users who viewed but did not purchase

---

## 📌 Conclusion

This project demonstrates how **data analysis and visualization** can be used to identify funnel bottlenecks and improve business performance.
It highlights the importance of understanding user behavior to increase conversion rates.

---

## 🚀 Future Improvements

* Add customer segmentation
* Include revenue analysis
* Apply machine learning for prediction

---
