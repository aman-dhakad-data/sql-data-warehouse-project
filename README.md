# SQL Data Warehouse Project

This project demonstrates the implementation of a modern SQL-based data warehouse using Medallion Architecture (Bronze, Silver, and Gold layers).

The warehouse integrates CRM and ERP sales datasets from CSV files into a centralized analytical model using SQL Server and Star Schema design principles.

---

## 🏗️ Data Architecture

The project follows the Medallion Architecture approach:

### Bronze Layer
- Raw CRM and ERP CSV data ingestion
- Source-aligned structure
- Minimal transformation

### Silver Layer
- Data cleansing and standardization
- Null handling and deduplication
- Data quality improvements

### Gold Layer
- Business-ready analytical model
- Star Schema implementation
- Fact and Dimension views for reporting and analytics

---

## ⭐ Star Schema Model

The Gold Layer uses a Star Schema design for analytical querying.

### Dimension Tables
- `gold.dim_customers`
- `gold.dim_products`

### Fact Table
- `gold.fact_sales`

The fact table connects with dimension tables using surrogate keys for simplified reporting and analytics.

---

## ⚙️ Data Engineering Concepts Applied

- ETL Pipeline Development
- Medallion Architecture
- Star Schema Modeling
- Fact & Dimension Tables
- Surrogate Keys
- SQL Views
- Data Integration
- Data Cleansing
- Data Quality Validation
- Git & GitHub Version Control

---

## 🛠️ Tools & Technologies

- SQL Server Express
- SQL Server Management Studio (SSMS)
- SQL
- Git & GitHub

---

## 📂 Repository Structure

```text
datasets/
├── source_crm/
└── source_erp/

docs/
├── data_catalog.md
└── naming_conventions.md

scripts/
├── bronze/
├── silver/
└── gold/

tests/
├── init_database.sql
├── quality_checks_silver.sql
└── quality_checks_gold.sql
```

---

## 📊 Data Sources

The project uses sales-related datasets from two source systems:

- CRM System
- ERP System

Both datasets are stored as CSV files inside the `datasets/` directory.

---

## 📘 Documentation

Project documentation is available in the `docs/` folder:

- Data Catalog
- Naming Conventions

---

## ✅ Data Quality Checks

Validation scripts were created to verify:

- Uniqueness of surrogate keys
- Referential integrity
- Valid fact-to-dimension relationships

---

## 📚 What I Learned

Through this project, I learned:

- How modern data warehouses are structured
- Practical ETL pipeline development
- Star Schema modeling
- SQL-based analytical transformations
- Organizing and documenting technical projects using GitHub

---

## 👨‍💻 About Me

Hi, I'm Aman.

I am currently learning Data Engineering and building hands-on projects focused on SQL, data warehousing, and analytics.

This project is part of my practical learning journey to improve real-world data engineering skills.
