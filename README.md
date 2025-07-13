# 🏗️ Data Warehouse & Analytics Project

This project showcases a complete **ETL + Analytics** pipeline using **SQL Server** and follows the **Medallion Architecture** (Bronze, Silver, Gold). The warehouse is built using raw CSV data from ERP & CRM sources and transformed into business-ready models.

---

## ⚙️ Architecture Overview

The solution is divided into three core layers:
1. **Bronze Layer** - Raw data ingested from source CSVs (ERP/CRM).
2. **Silver Layer** - Cleaned, standardized, and transformed tables using SQL procedures.
3. **Gold Layer** - Final business-ready views with star schema modeling for reporting.

---

## 💡 ETL Concepts Covered

- Extracting CSV files into SQL Server using basic automation.
- Data cleansing: Removing nulls, fixing types, handling duplicates.
- Transformations: Standardization, normalization, derived columns.
- Modeling: Creating **fact** and **dimension** tables for optimized queries.
- Loading strategies: Truncate & Insert, Full Load, Batch Processing.

---

## 📊 Project Highlights

- ✅ Built full data warehouse manually with SQL Server.
- ✅ Followed real-world warehousing architecture.
- ✅ Wrote SQL scripts for each layer's ETL logic.
- ✅ Generated analytical queries to extract sales/customer trends.
- ✅ Great hands-on project for aspiring **Data Engineers**.

---

## 🗂️ Repository Structure

data-warehouse-project/
├── datasets/ → Raw data files (ERP & CRM)
├── scripts/
│ ├── bronze/ → Ingestion scripts
│ ├── silver/ → Transformation scripts
│ ├── gold/ → Business model scripts
├── docs/ → Architecture diagrams, project notes
├── README.md
└── .gitignore
