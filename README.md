# Olist Store | Brazilian E-Commerce Analytics Dashboard

## Project Overview

This project analyzes the **Brazilian E-Commerce Public Dataset (Olist)** using **Python** and **Power BI** to uncover actionable business insights related to sales, customers, products, payments, sellers, and delivery performance.

The project follows the complete data analytics workflow:

* Data Cleaning
* Data Transformation
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Modeling
* Interactive Dashboard Development

---

#  Dataset

* **Source:** Kaggle – Brazilian E-Commerce Public Dataset by Olist
* **Period:** September 2016 – August 2018
* **Orders:** ~100K
* **Customers:** ~96K
* **Products:** ~33K
* **Sellers:** ~3K
* **Link of DataSet https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

---

# 🛠️ Tools & Technologies

### Python

* Pandas
* NumPy
* Matplotlib


### Power BI

* Data Modeling
* DAX Measures
* Interactive Visualizations
* Page Navigation
* Slicers
* KPI Cards

---

# Data Preparation

The dataset was prepared using Python by:

* Handling missing values
* Removing duplicates
* Fixing data types
* Creating calculated columns
* Feature engineering
* Merging multiple datasets into a final analytical dataset

### Created Features

* Total Cost
* Delivery Delay (Days)
* Delivery Time (Days)
* Approval Time (Hours)


---

# 📊 Dashboard Pages

## 📦 1. Orders & Sales

**KPIs**

* Total Orders
* Total Revenue
* Average Order Value

**Visualizations**

* Revenue Trend
* Top Product Categories by Revenue
* State Filter

![Orders & Sales](images/)

---

## 👥 2. Customers & Delivery

**KPIs**

* Total Customers
* Average Shipping Cost
* Delayed Orders %

**Visualizations**

* Delivery Delay Distribution
* Top Customer States
* State Filter

> *(Insert Customers & Delivery dashboard screenshot here)*

---

## 💳 3. Payment & Reviews

**KPIs**

* Average Review Score
* Total Reviews
* Average Installments

**Visualizations**

* Review Score Distribution
* Payment Installments
* Payment Method Breakdown

> *(Insert Payment & Reviews dashboard screenshot here)*

---

## 🏪 4. Sellers & Products

**KPIs**

* Total Sellers
* Total Products
* Average Products per Seller

**Visualizations**

* Top Selling Product Categories
* Top Seller States

> *(Insert Sellers & Products dashboard screenshot here)*

---

#  Key Insights

### 📦 Sales

* Generated over **$16M** in total revenue.
* A small number of product categories contribute the majority of revenue.
* Revenue increased steadily throughout most of the observed period.

### 👥 Customers

* Approximately **96K unique customers** placed orders.
* Customer activity is concentrated in a few Brazilian states.

### 🚚 Delivery

* About **6.7%** of orders were delivered later than the estimated delivery date.
* Longer delivery delays are associated with lower customer satisfaction.

### ⭐ Reviews

* Most customers gave **5-star reviews**, indicating generally positive experiences.
* Review scores decline noticeably for delayed deliveries.

### 💳 Payments

* Credit cards are the dominant payment method.
* Most customers prefer paying in a single installment, while installment usage decreases as the number of installments increases.

### 🏪 Sellers & Products

* The marketplace includes approximately **3K sellers** and **33K products**.
* Product sales are highly concentrated in a limited number of categories.

---
# 💡 Business Insights & Recommendations


## Insight 1 — Delivery Delays Reduce Customer Satisfaction

Analysis shows a strong relationship between delivery delays and customer satisfaction.

* **Average review score for on-time deliveries:** **4.18 / 5**
* **Average review score for delayed deliveries:** **2.25 / 5**
* Approximately **6.7%** of all orders were delivered later than the estimated delivery date.

**Business Impact**

* Late deliveries significantly reduce customer satisfaction.
* Lower ratings can negatively affect seller reputation and customer retention.

**Recommendation**

* Optimize shipping routes and logistics operations.
* Monitor sellers with frequent late deliveries.
* Provide proactive delivery notifications to customers when delays are expected.
* Review estimated delivery dates to ensure they are realistic.

---

## Insight 2 — Revenue is Concentrated in Few Categories

A limited number of product categories generate the majority of total revenue.

**Recommendation**

* Prioritize inventory and marketing investment in top-performing categories.
* Launch promotional campaigns for underperforming categories to increase sales diversification.

---

## Insight 3 — Credit Card is the Preferred Payment Method

Most customers complete purchases using credit cards, while other payment methods represent a much smaller share.

**Recommendation**

* Continue optimizing the credit card checkout experience.
* Offer installment promotions to encourage higher-value purchases.

---

## Insight 4 — Customer Base is Highly Concentrated by State

A significant percentage of customers come from a few Brazilian states.

**Recommendation**

* Focus regional marketing campaigns on high-performing states.
* Expand logistics and advertising efforts in lower-performing regions to increase market penetration.


# 🚀 Conclusion

This project demonstrates an end-to-end Business Intelligence workflow, starting from raw data preprocessing in Python and ending with a professional interactive Power BI dashboard that helps stakeholders monitor sales performance, customer behavior, delivery efficiency, payment patterns, and product performance.
