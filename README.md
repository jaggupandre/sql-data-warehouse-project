# 🚀 Retail Sales Data Warehouse Project (SQL Server + SSMS)

This project is a hands-on implementation of a **retail sales data warehouse**, inspired by the *"Data Warehouse Zero to Master"* YouTube series. I recreated and customized the entire project using **SQL Server** and **SSMS**, following best practices in data modeling, ETL, and performance optimization.
---
## Data Architecture

* The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:
* Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
* Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
* Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.
---

## 📌 Project Objectives

* Build a modern data warehouse using SQL Server with a proper **star schema**.
* Load and transform raw retail data into structured fact and dimension tables.
* Develop **ETL processes** using T-SQL scripts to handle staging, transformation, and loading.
* Optimize performance with indexing and partitioning.
* Enable analytical reporting using SQL queries for business insights.

---

## 🧰 Tech Stack

* **Database:** Microsoft SQL Server
* **Interface:** SQL Server Management Studio (SSMS)
* **Query Language:** T-SQL
* **Data Modeling:** Star Schema (Fact + Dimension tables)
* **ETL:** SQL Scripts for full-load (can be extended to incremental logic)
* **Optional:** Tableau / Power BI for data visualization (not implemented yet)

---

## 🏗️ Project Architecture

```
Raw Data → Staging Tables → Transformed Data → Star Schema (Warehouse) → Reporting Queries
```

* **Fact Table:** `fact_sales`
* **Dimension Tables:** `dim_customers`, `dim_products`

---

## 📈 Sample Business Use Cases

* Track monthly and yearly revenue trends.
* Analyze top customers and high-performing products.
* Perform regional performance breakdowns.
* Generate date-wise and product-category-wise sales summaries.

---

## 🔄 Future Enhancements

* Add **incremental load logic** using surrogate keys and timestamps.
* Integrate with **SSIS** or **Apache Airflow** for ETL orchestration.
* Build **BI dashboards** using Tableau or Power BI.
* Implement **Slowly Changing Dimensions (Type 2)** for tracking historical changes.

---

## 📚 Credits

This project is based on the YouTube series:
🎥 [Data Warehouse Zero To Master – by Data With Baraa](https://www.youtube.com/watch?v=t0znN5pCdzc&list=PLNFyyGG_pKeTbkpKYbInC9LHhSNYsurag)

---
