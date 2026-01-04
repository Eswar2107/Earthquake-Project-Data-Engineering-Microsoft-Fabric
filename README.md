# Earthquake-Project-Data-Engineering-Microsoft-Fabric

## Project Overview
This project demonstrates how to build an end-to-end data engineering and analytics pipeline using Microsoft Fabric. It covers data ingestion, transformation, orchestration, and visualization using Data Factory, Data Engineering, and Power BI.

The pipeline processes earthquake event data sourced from the USGS (United States Geological Survey) API.

## Technologies Used
- Python  
- PySpark  
- Microsoft Fabric  
  - Data Engineering  
  - Data Factory  
- Power BI  

## Getting Started
To get started with this project:

- Download the notebooks from the repository  
- Follow the step-by-step instructions provided in the YouTube tutorial  
- Execute the notebooks in sequence: **Bronze → Silver → Gold**

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

## Pipeline Orchestration & Automation
- Implemented scheduled pipeline execution using **Microsoft Fabric Data Factory**  
- Automated end-to-end data processing from ingestion to Gold layer  
- Configured **semantic model refresh** to ensure Power BI reports always use the latest data  

## Architecture
This project follows a **Medallion Architecture (Bronze, Silver, Gold)** approach to deliver reliable, scalable, and automated analytics using Microsoft Fabric.
