# Delivery_logistics_Big_data
Delivery Logistics Analytics project built in Databricks. Includes data ingestion, cleaning, feature engineering, PySpark notebook analysis, SQL queries, and an interactive dashboard. Analyzes delays, cost efficiency, partner performance, and regional delivery trends

---
/Delivery_Logistics.csv
/Delivery_logistics_notebook.ipynb
/SQL QURIES.ipynb
/Delivery_logistics_performance.lvdash.json
/README.md
---

# 📘 *README – Delivery_logistics_notebook.ipynb*

## *Delivery_logistics_notebook.ipynb*

This notebook contains the *data cleaning and PySpark-based analysis* for the Delivery Logistics project.

### *Purpose*

To implement the ETL workflow required in the final exam:

* Load raw data
* Clean and standardize fields
* Create engineered features
* Perform notebook-based analytics

### *Key Operations*

* Selected and casted numeric and categorical fields
* Removed invalid/missing records
* Created new features such as cost_per_km, delay flags, and rating logic
* Generated PySpark visualizations (delay trends, cost insights, weather patterns)
* Verified schema and data quality

### *Why this file matters*

It satisfies *Section 4.5: Notebook Analysis*, demonstrating the ability to use PySpark for exploration and ETL inside Databricks.

---

# 🧮 *README – SQL QURIES.ipynb*

## *SQL QURIES.ipynb*

This notebook contains all *SQL analytical queries* used in the project and in the final dashboard.

### *Purpose*

To perform the SQL-based analytics required for:

* Delay rate calculations
* Partner performance scoring
* Cost efficiency classification
* Weather impact analysis
* Delivery mode and region-level insights

### *Key SQL Queries*

* Weather vs Delay Rate
* Delivery Partner Performance
* Cost Efficiency by Mode
* Region Delay Comparison
* On-Time vs Delayed Summary

### *Why this file matters*

This file satisfies *Section 4.4: SQL Analysis* and contains queries used as data sources for the interactive dashboard.

---

# 📊 *README – Delivery_logistics_performance.lvdash.json*

## *Delivery_logistics_performance.lvdash.json*

This is the exported *Databricks dashboard* that visualizes the insights derived from SQL queries.

### *Purpose*

To provide a clear, interactive performance overview of the delivery system.

### *Dashboards Included*

* Donut chart → Delay Rate by Weather Condition
* Bar chart → Delay Rate by Region
* Scatter plot → Partner Rating vs Delay %
* Bar chart → Cost per KM by Delivery Mode
* KPI Tiles → Delivery counts, delay trends
* Dashboard Filters → Weather Condition, Delivery Mode, Region

### *Why this file matters*

It satisfies *Section 4.6: Dashboard Creation*, proving your ability to build interactive, filter-enabled dashboards in Databricks.

---

# 📦 *README – Delivery_Logistics.csv*

## *Delivery_Logistics.csv*

This is the original dataset used for the Delivery Logistics analysis.

### *Columns Include*

* Distance (km)
* Delivery time (hours)
* Delivery partner
* Delivery mode
* Region
* Cost
* Weather condition
* Package weight
* Delay flag
* Rating

### *Purpose*

Used as the source file for:

* Ingestion (Section 4.1)
* Cleaning and feature engineering (Section 4.2)
* Delta table creation (Section 4.3)
* Notebook and SQL analysis

### *Why this file matters*

It is required to *reproduce the full Databricks workflow* from ingestion to dashboard.

