# ☁️ Azure End-to-End Data Pipeline

## Project Overview
A fully cloud-native data pipeline built on Microsoft Azure — demonstrating modern 
data engineering from raw data ingestion through to interactive Power BI dashboard.
Built to support DP-600 (Microsoft Fabric Analytics Engineer) certification preparation
and showcase enterprise-grade Azure data engineering skills.

---

## 🎯 Business Problem
Organisations generating large volumes of raw data need scalable, governed, and automated
pipelines to transform that data into business insights. This project demonstrates:
- Automated data ingestion into Azure Data Lake
- Scalable transformation using Databricks and PySpark
- Production-ready Power BI reporting with governance controls
- End-to-end pipeline monitoring and data quality checks

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Cloud Platform | Microsoft Azure |
| Data Storage | Azure Data Lake Storage Gen2 |
| Data Processing | Azure Databricks (PySpark) |
| Transformation | PySpark, SQL |
| Orchestration | Azure Data Factory |
| Semantic Layer | Microsoft Fabric / Power BI |
| Visualisation | Power BI (DAX, Power Query, RLS) |
| Version Control | Git / GitHub |

---

## 🏗️ Pipeline Architecture
Raw Data Source
↓
Azure Data Lake (Bronze Layer — raw)
↓
Azure Databricks (PySpark transformation)
↓
Azure Data Lake (Silver Layer — cleaned)
↓
Azure Data Lake (Gold Layer — aggregated)
↓
Power BI Dashboard (DAX, RLS, Scheduled Refresh)

---

## 📊 Dashboard Features
- Real-time data refresh via Power BI Service
- Row-Level Security (RLS) for data governance
- Executive KPI cards and trend analysis
- Drill-down and cross-filtering capabilities
- Scheduled refresh via Power BI Gateway

---

## 🗂️ Project Structure
azure-data-pipeline/
│
├── databricks/
│   ├── 01_ingest.py            # Bronze layer ingestion
│   ├── 02_transform.py         # Silver layer transformation
│   └── 03_aggregate.py         # Gold layer aggregation
│
├── sql/
│   └── data_quality_checks.sql # Data validation queries
│
├── powerbi/
│   └── dashboard.pbix          # Power BI dashboard
│
├── docs/
│   └── architecture.md         # Pipeline architecture docs
│
└── README.md

---

## 📈 Status

| Phase | Status |
|---|---|
| Dataset selection | ⏳ In Progress |
| Azure Data Lake setup | ⏳ In Progress |
| Databricks pipeline | ⏳ In Progress |
| PySpark transformations | ⏳ In Progress |
| Power BI dashboard | ⏳ Planned |
| RLS & governance | ⏳ Planned |

---

## 🔗 Background
This project directly supports my DP-600 (Microsoft Fabric Analytics Engineer) 
certification preparation and builds on real cloud data engineering experience from 
John Deere Technology Center, where I re-engineered legacy telemetry pipelines using 
PySpark in Databricks with incremental loading logic, processing tens of GBs of IoT 
sensor data from field-deployed agricultural equipment.

---

## 👤 Author
**Avinash Desai** — Data Analyst | PL-300 Certified | MSc Data Analytics (1:1) DBS
- 🔗 [LinkedIn](https://linkedin.com/in/avinash-desai4/)
- 📧 desaiavinash93@gmail.com
