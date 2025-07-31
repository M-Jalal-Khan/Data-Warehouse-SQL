# 📦 Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project showcases the end-to-end development of a modern data warehouse using **SQL Server**, including robust **ETL pipelines**, clear **dimensional data models**, and practical **SQL-based analytics** for business decision-making.

---

## 🧱 Data Architecture: Medallion Approach

This project follows the **Medallion Architecture**, structuring data across three logical layers to ensure quality, reusability, and scalability.


### 🔹 Bronze → Silver → Gold


### 📊 Architecture Diagram

- **🔹 Bronze Layer**: Ingests raw ERP and CRM data from CSV files into SQL Server.
- **🔸 Silver Layer**: Performs data cleaning, standardization, and validation.
- **⭐ Gold Layer**: Hosts business-ready data modeled using star schema principles for efficient analysis.

---

## 📖 Project Highlights

This repository includes:

1. **Data Architecture**
   - Medallion-style data layering
   - System architecture and flow diagrams

2. **ETL Development**
   - Extraction of raw CSV data
   - SQL-based transformation scripts
   - Multi-layered data pipeline into analytical models

3. **Data Modeling**
   - Fact and dimension tables using a star schema
   - Relationships optimized for analysis and reporting

4. **SQL-Based Analytics**
   - Reports and queries for customer behavior, product performance, and sales trends

---

## 🎯 Skills Demonstrated

- ✅ SQL Development  
- ✅ Data Warehousing  
- ✅ ETL Pipeline Design  
- ✅ Dimensional Modeling  
- ✅ Data Cleaning & Integration  
- ✅ Business Intelligence & Reporting  
- ✅ Data Governance & Best Practices

---

## 📂 Repository Structure

```text
data-warehouse-project/
│
├── datasets/                           # Raw ERP & CRM CSV data
│
├── docs/                               # Diagrams and documentation
│   ├── etl.drawio                      # ETL process diagram
│   ├── data_architecture.drawio        # Medallion architecture overview
│   ├── data_catalog.md                 # Metadata and dataset descriptions
│   ├── data_flow.drawio                # Layer-to-layer data movement
│   ├── data_models.drawio              # Star schema visual
│   ├── naming-conventions.md           # Standards for naming tables/columns
│
├── scripts/                            # SQL codebase by layer
│   ├── bronze/                         # Raw data ingestion
│   ├── silver/                         # Data cleaning and transformation
│   ├── gold/                           # Data modeling and reporting
│
├── tests/                              # SQL validation and QA scripts
│
├── README.md                           # Project overview and documentation
├── LICENSE                             # License (MIT)
├── .gitignore                          # Git exclusions
└── requirements.txt                    # Setup or tool references


---

## 🚀 Project Phases

### 🏗️ Phase 1: Data Warehouse Development

- Import ERP and CRM datasets (CSV)
- Clean, deduplicate, and integrate core tables
- Design and build a **star schema** in SQL Server
- Implement ETL using SQL scripts in layered stages

---

### 📊 Phase 2: Business Analytics

- Perform SQL analysis on customer and product behavior
- Generate insights using aggregate metrics and KPIs
- Write clear, performant queries for reporting

---

## 🧰 Tools & Technologies

- **SQL Server Express** – Database engine  
- **SQL Server Management Studio (SSMS)** – Query and DB interface  
- **Draw.io** – Visual diagrams  
- **CSV Files** – Raw data input  
- **Git & GitHub** – Version control and collaboration  
- **Coda / Notion** – Project planning and documentation

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).  
You’re free to use, modify, or share this project with proper attribution.

---

## 👤 Author

**Muhammad Jalal Khan**  
Data Analyst | BI Expert |


