# SQL Data Warehouse Project

A data warehouse built with SQL Server using Medallion Architecture 
(Bronze, Silver, Gold layers) to consolidate and analyze sales data 
from ERP and CRM source systems.

## 🏗️ Architecture
- **Bronze Layer**: Raw data ingested from CSV files
- **Silver Layer**: Cleaned and standardized data
- **Gold Layer**: Business-ready star schema for analytics

## 🛠️ Tools Used
- SQL Server Express
- SQL Server Management Studio (SSMS)
- Git & GitHub

## 📂 Project Structure
```
scripts/
├── bronze/    # Raw data load scripts
├── silver/    # Data cleaning scripts
└── gold/      # Analytical model scripts
```

## 📊 Data Sources
- CRM System (3 CSV files)
- ERP System (3 CSV files)

## 📚 Documentation

- [Data Catalog](docs/data_catalog.md)
- [Naming Conventions](docs/naming_conventions.md)
