# 📊 Customer Behavior Analytics Dashboard

This project analyzes customer purchasing behavior using Python, SQL, and Power BI to generate meaningful insights and support data-driven decisions. It follows an end-to-end data analytics workflow—from data cleaning and exploratory data analysis (EDA) to database querying and interactive dashboard creation.

---

## 📊 Dashboard Preview

![Customer Behavior Dashboard](Dashboard.png)
*(Note: If the dashboard image isn't visible, please ensure 'Dashboard.png' is uploaded to the root of your repository)*

---

## 🎯 Project Objectives
* **Identify Purchase Patterns:** Understand how different customer segments interact with products.
* **Discount Impact Analysis:** Measure how promotional discounts affect overall sales volume and profit margins.
* **Product Performance:** Track and isolate high-performing product categories.
* **Demographic Segmentation:** Analyze purchasing trends across various age groups and customer backgrounds.

---

## 🛠️ Tech Stack
* **Python (Pandas & Jupyter Notebook):** Data cleaning, preprocessing, and Exploratory Data Analysis (EDA)[cite: 1].
* **SQL:** Relational data structuring and deep-dive analytical querying.
* **Power BI:** Interactive data modeling, DAX calculations, and executive dashboard design[cite: 1].

---

## 🔄 End-to-End Workflow

### 1. Data Cleaning & Preprocessing (Python)
* Handled missing values and eliminated data inconsistencies using Pandas.
* Standardized column types and formatted text fields for seamless database ingestion.
* Conducted Exploratory Data Analysis (EDA) inside `analysis.ipynb`.

### 2. Database Management & Querying (SQL)
* Structured and loaded the processed dataset into an SQL database.
* Wrote optimized queries in `customer_behavior_sql_queries.sql` to extract key performance metrics and customer metrics.

### 3. Data Visualization (Power BI)
* Imported data into Power BI to build an interactive, multi-perspective report.
* Created visualizations for customer demographics, regional trends, revenue distribution, and discount analysis.

---

## 📈 Key Insights Covered
* **High-Value Segments:** Identified which customer demographics drive the highest purchase frequency and lifetime value.
* **Promotion Effectiveness:** Isolated the threshold where discounts maximize sales volume without severely eroding margins.
* **Category Trends:** Pinpointed seasonal and baseline demand differences across major product categories.

---

## 📂 Project Structure

```text
├── analysis.ipynb                      # Jupyter Notebook for EDA & Python preprocessing
├── Customer_Behavior_Dashboard.pbix    # Power BI Dashboard file
├── customer_behavior_sql_queries.sql   # SQL script containing analytical queries
├── customer_shopping_behavior (3).csv  # Raw/Processed dataset (Excel/CSV format)
└── README.md                           # Project documentation# Customer_Behaviour_Analysis
