# Logistics Operations ETL Pipeline (Azure + Power BI)

## Project Overview
This project showcases a real-time ETL pipeline for logistics operations data monitoring.  
Data was extracted, cleaned, transformed using Python, stored in Azure Data Lake Storage Gen2, and connected to Power BI.

## Technologies Used
- Azure Data Lake Storage Gen2
- Python (pandas, azure-storage-blob)
- Power BI (Connection and Visualization)

## Steps Performed
1. **Extract**: Pulled raw logistics transaction dataset from Azure Blob Storage.
2. **Transform**:
   - Cleaned missing values.
   - Created KPIs like traffic congestion category, warehouse stock health, and average loading/unloading time.
3. **Load**:
   - Saved transformed dataset back into Azure in a `processed/` container.
4. **Visualization**:
   - Connected Azure Storage to Power BI for real-time data exploration (no dashboards created yet).

## Repository Structure
- `logisticsproj.ipynb`: Full ETL code in Python.
- `README.md`: Project overview and instructions.

## Key Highlights
- Full Azure Data Lake Gen2 ingestion and processing pipeline.
- KPI engineering for logistics operational metrics.
- Demonstrated real-world cloud data engineering practices.

---
