# Earthquake-Project-Data-Engineering-Microsoft-Fabric

## Project Overview
This project demonstrates how to build an end-to-end data engineering and analytics pipeline using Microsoft Fabric. It covers data ingestion, transformation, and visualization using Data Factory, Data Engineering, and Power BI.

The pipeline processes earthquake event data sourced from the USGS (United States Geological Survey) API.

## Technologies Used
- Python  
- PySpark  
- Microsoft Fabric  
  - Data Engineering  
  - Data Factory  
- Power BI
  
## Repository Contents

### Worldwide Earthquake Events API – Bronze Layer Processing
- Ingests raw earthquake data from the USGS API  
- Performs minimal processing  
- Stores data in its original raw format  
- Acts as the foundational data layer  

### Worldwide Earthquake Events API – Silver Layer Processing
- Cleans and transforms data from the Bronze layer  
- Enhances data quality and consistency  
- Prepares the dataset for analysis  

### Worldwide Earthquake Events API – Gold Layer Processing
- Creates business-ready, analytics-optimized datasets  
- Designed for insights, reporting, and dashboards  
- Optimized for Power BI visualizations  

## Architecture
This project follows a **Medallion Architecture (Bronze, Silver, Gold)** approach to deliver reliable and scalable analytics using Microsoft Fabric.
