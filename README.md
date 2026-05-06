# data-warehouse-powerbi-project

## Overview
This repository contains an end-to-end data engineering project built using the Medallion Architecture (Bronze, Silver, Gold). The objective is to transform raw data into a structured, analytics-ready data warehouse and enable reporting through Power BI.

The project focuses on data quality, scalable design, and clear separation of data processing layers.

---

## Architecture

The pipeline is organized into three layers:

### Bronze Layer
- Ingests raw data from source systems (ERP, CRM, etc.)
- Stores data in its original format
- Maintains historical data for traceability

### Silver Layer
- Cleans and standardizes data
- Handles missing values and duplicates
- Produces consistent and validated datasets

### Gold Layer
- Applies business logic and transformations
- Builds fact and dimension tables (star schema)
- Provides analytics-ready data for reporting

---

## Data Pipeline

1. Ingest raw data into the Bronze layer  
2. Clean and transform data in the Silver layer  
3. Model data into fact and dimension tables in the Gold layer  
4. Connect Power BI to the Gold layer for reporting  

---

## Tech Stack

- SQL (data transformation and modeling)   
- Data Warehousing (Star Schema)  
- Power BI (visualization and dashboards)  

---

## Project Structure








## Key Features

- Medallion Architecture implementation (Bronze → Silver → Gold)  
- Structured and modular ETL pipeline  
- Data cleaning and validation  
- Fact and dimension modeling  
- Integration with Power BI for analytics  

---

## Power BI Integration

The Gold layer is used as the data source for Power BI dashboards, enabling:
- KPI tracking  
- Trend analysis  
- Interactive business insights  

---

## Future Improvements

- Workflow orchestration (e.g., scheduling pipelines)  
- Incremental data loading  
- Cloud deployment (AWS, Azure, or GCP)  
- Performance optimization  

---

## Summary

This project demonstrates the design and implementation of a modern data pipeline, covering ingestion, transformation, modeling, and visualization. It reflects practical data engineering concepts used in real-world systems.
