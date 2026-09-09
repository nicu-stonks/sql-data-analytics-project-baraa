# SQL Data Analytics Project: E-Commerce & Retail Insights

This repository contains a complete end-to-end data analytics workflow using advanced SQL queries, built to extract actionable business insights from retail data.

---

## 📊 Project Overview
The objective of this project is to analyze raw sales, customer, and product data to answer critical business questions regarding revenue generation, product performance, and customer segmentation. 

Key analytical areas covered:
* **Sales Performance & Trends:** Tracking revenue trends, category contributions, and order behaviors over time.
* **Customer Segmentation:** Evaluating customer tenure, total spend, order frequency, and identifying high-value customers.
* **Product Analytics:** Analyzing best-performing products, pricing strategies, and inventory movement.

---

## 🗺️ Project Roadmap & Analytics Workflow

The analysis follows a structured two-phase roadmap: starting with **Exploratory Data Analysis (EDA)** to understand schemas, dimensions, and baseline metrics, followed by **Advanced Analytics** to evaluate trends, performance, part-to-whole relationships, and customer segmentation.



### Key Milestones:
* **Exploratory Data Analysis (EDA):** Database & Dimensions Exploration, Date Exploration, Key Measures, Magnitude Analysis, and Top/Bottom N Ranking.
* **Advanced Analytics:** Change-Over-Time Analysis, Cumulative Metrics, Performance Tracking, Part-to-Whole (Proportional) Contribution, Data Segmentation, and Analytical Reporting.

---


## 🛠️ Tech Stack & Tools
* **Database Management System:** Microsoft SQL Server (SSMS)
* **Language:** T-SQL
* **Key SQL Concepts Used:**
  * Common Table Expressions (`WITH` CTEs)
  * Window Functions (`OVER()`, `PARTITION BY`, `ROW_NUMBER()`)
  * Advanced Aggregations & Grouping
  * Conditional Logic (`CASE WHEN`, `COALESCE`, `NULLIF`)
  * Data Type Casting & Formatting (`CAST`, `ROUND`)

---

## 📂 Project Structure

```text
├── scripts/
│   ├── 01_database_setup.sql          # Database and schema creation scripts
│   ├── 02_data_exploration.sql        # Exploratory data analysis scripts
│   └── 03_customer_insights.sql       # Advanced analytics & customer segmentation
├── datasets/                          # Raw CSV / data backup files
└── README.md
