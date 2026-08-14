# 🛒 Olist E-Commerce Sales Analysis

## 📌 Project Overview

This project presents an end-to-end analysis of the **Olist Brazilian E-Commerce dataset** using **SQL Server and Power BI**.

The goal of the project is to transform raw e-commerce data into meaningful business insights by analyzing sales performance, customer behavior, order status, payment methods, delivery performance, product categories, and seller performance.

---

## 🎯 Business Objectives

The analysis aims to answer key business questions such as:

* What is the overall sales performance?
* How are sales changing over time?
* Which product categories generate the highest revenue?
* What are the most popular payment methods?
* How many orders are delivered, canceled, or unavailable?
* How does delivery performance affect customer experience?
* Which sellers and customers contribute most to the business?
* What are the key sales and customer performance indicators?

---

## 📊 Dataset

The project uses the **Olist Brazilian E-Commerce Public Dataset**, which contains information about orders placed on the Olist marketplace.

The dataset includes several related tables covering:

* Customers
* Orders
* Order Items
* Payments
* Reviews
* Products
* Sellers
* Geolocation
* Product Category Translation

---

## 🔄 Project Workflow

```text
Raw CSV Data
      ↓
SQL Server
      ↓
Database Creation
      ↓
Data Exploration
      ↓
SQL Analysis
      ↓
SQL Views
      ↓
Power BI
      ↓
Interactive Dashboard
      ↓
Business Insights
```

---

## 🗄️ SQL Analysis

The SQL analysis covers multiple analytical techniques, including:

* Database exploration
* Dimension exploration
* Date range analysis
* Measures exploration
* Magnitude analysis
* Ranking analysis
* Change-over-time analysis
* Cumulative analysis
* Performance analysis
* Data segmentation
* Part-to-whole analysis

The project also creates SQL Views to prepare analytical data for Power BI.

### 📁 SQL Scripts

The `scripts` folder contains the SQL analysis scripts:

```text
scripts/
├── 00_database.sql
├── 01_database_exploration.sql
├── 02_dimensions_exploration.sql
├── 03_date_range_exploration.sql
├── 04_measures_exploration.sql
├── 05_magnitude_analysis.sql
├── 06_ranking_analysis.sql
├── 07_change_over_time_analysis.sql
├── 08_cumulative_analysis.sql
├── 09_performance_analysis.sql
├── 10_data_segmentation.sql
└── 11_part_to_whole_analysis.sql
```

---

## 🧱 SQL Views

Several analytical views were created to provide structured datasets for reporting and dashboard development.

```text
views/
├── vw_ExecutiveKPIs.sql
├── vw_customers_summary.sql
├── vw_delivery_status.sql
├── vw_orders_status_summary.sql
├── vw_payment_type.sql
├── vw_sales_summary.sql
└── vw_sellers_summary.sql
```

---

## 📈 Power BI Dashboard

The processed data and SQL views are used to build an interactive Power BI dashboard.

The dashboard provides an overview of:

* Executive KPIs
* Sales performance
* Customer performance
* Order status
* Delivery performance
* Payment methods
* Product and seller performance

### Dashboard

The Power BI dashboard files are available in:

```text
power bi dashboard/
├── Olist Dashboard.pbix
└── Olist Dashboard.pdf
```

---

## 🛠️ Tools & Technologies

* **SQL Server**
* **SQL**
* **Power BI**
* **Excel / CSV**
* **Git & GitHub**

---

## 📁 Project Structure

```text
Olist-E-Commerce-Sales-Analysis/
│
├── dataset/
│   ├── olist_customers_dataset.csv
│   ├── olist_geolocation_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── olist_order_reviews_dataset.csv
│   ├── olist_orders_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── olist_sellers_dataset.csv
│   └── product_category_name_translation.csv
│
├── docs/
│   └── project roadmap.png
│
├── power bi dashboard/
│   ├── Olist Dashboard.pbix
│   └── Olist Dashboard.pdf
│
├── scripts/
│   └── SQL analysis scripts
│
├── views/
│   └── SQL analytical views
│
├── LICENSE
└── README.md
```

---

## 📌 Key Skills Demonstrated

This project demonstrates practical experience with:

* Relational data analysis
* SQL querying
* Data exploration
* Analytical SQL
* SQL Views
* KPI development
* Business-oriented analysis
* Power BI dashboard development
* Data visualization
* Git & GitHub

---

## 📚 Dataset Source

The project uses the **Olist Brazilian E-Commerce Public Dataset**.

Dataset originally provided through the Olist e-commerce dataset on Kaggle.

---

## 👤 Author

**Ahmed Elameary**

Data Analytics | Data Engineering

GitHub: [@ahmed-elamearyy](https://github.com/ahmed-elamearyy)
