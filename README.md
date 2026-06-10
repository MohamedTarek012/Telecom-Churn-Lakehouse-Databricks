# Telecom-Churn-Lakehouse-Databricks
## Architecture
Medallion Architecture (Bronze → Silver → Gold)

## Tech Stack
- Databricks Community Edition
- Delta Lake
- PySpark
- Databricks SQL Dashboard

## Dataset
IBM Telco Customer Churn — 7,043 customers

## Key Findings
- Overall churn rate: 26.5%
- MRR at risk: $139K/month
- Month-to-month contracts: 42-70% churn rate
- New customers (0-12m) most at risk

## Pipeline
01_bronze_ingestion → 02_silver_transform → 03_gold_kpis

## Dashboard
Telco Churn Analytics — Built on Databricks SQL
