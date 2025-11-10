# 🛍️ Customer Shopping Behavior Analysis

### 🔍 **Project Overview**

This project analyzes customer shopping behavior across 3,900 transactions to uncover insights into **spending patterns**, **customer segmentation**, **product preferences**, and **subscription trends**.
The analysis combines **Python (EDA)**, **PostgreSQL (SQL analytics)**, and **Power BI (dashboard visualization)** to deliver data-driven business insights.

---

### 📂 **Dataset Summary**

* **Rows:** 3,900
* **Columns:** 18
* **Key Features:**

  * Customer Demographics: `age`, `gender`, `location`, `subscription_status`
  * Purchase Details: `item_purchased`, `category`, `purchase_amount`, `season`
  * Shopping Behavior: `discount_applied`, `previous_purchases`, `review_rating`, `shipping_type`
* **Missing Data:** 37 null values in `review_rating` handled using median imputation per product category.

---

### 🧠 **Process Overview**

#### 🐍 1. Exploratory Data Analysis (Python)

* Loaded and cleaned dataset using **pandas**.
* Handled missing values and standardized column names.
* Engineered new features:

  * `age_group` (binned customer ages)
  * `purchase_frequency_days`
* Integrated cleaned data with **PostgreSQL** for advanced SQL queries.

#### 🧾 2. SQL Analysis (PostgreSQL)

Performed 10+ analytical queries to extract business insights, including:

* Revenue by gender and age group
* High-spending discount users
* Top 5 products by review rating
* Shipping type comparison (Standard vs Express)
* Subscribers vs Non-Subscribers spending
* Product discount dependency
* Customer segmentation (New, Returning, Loyal)
* Repeat buyers and subscriptions correlation

#### 📊 3. Dashboard (Power BI)

Developed an interactive Power BI dashboard with visuals for:

* Revenue by season, category, and payment method
* Customer loyalty and purchase frequency
* Review ratings vs spending trends

---

### 💡 **Key Business Recommendations**

* **Boost Subscriptions:** Offer exclusive subscriber benefits.
* **Loyalty Programs:** Reward frequent buyers to enhance retention.
* **Optimize Discounts:** Control margins while driving sales.
* **Product Strategy:** Highlight top-rated and best-selling items.
* **Targeted Marketing:** Focus on high-revenue age groups and express-shipping users.

---

### 🧰 **Tools & Technologies**

* **Python:** Data Cleaning & Feature Engineering
* **PostgreSQL:** SQL Business Analysis
* **Power BI:** Dashboard Visualization
* **Pandas, Matplotlib:** Data Exploration

---

** Author **

**Sujit Kumar Behera**
📅 Project Year: 2025

---
