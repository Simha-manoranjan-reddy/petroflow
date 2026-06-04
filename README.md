# PetroFlow ⚡
### Azure End-to-End Energy Analytics Pipeline

Real-time crude oil and natural gas market 
analytics pipeline built on Azure.

## Tech Stack
- Azure Data Factory — Ingestion
- Azure ADLS Gen2 — Storage
- Azure Databricks + PySpark — Transformation
- Azure Synapse Analytics — Query Layer
- Azure DevOps — CI/CD
- Azure Fabric — Lakehouse

## Architecture
Source (EIA API) → ADF → ADLS Bronze
→ Databricks → Silver → Gold
→ Synapse → Power BI

## Data Sources
- EIA API — Real crude oil prices
- EIA API — Natural gas prices
