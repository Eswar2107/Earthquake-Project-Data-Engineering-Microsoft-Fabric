Earthquake-Project-Data-Engineering-Microsoft-Fabric
Project Overview

This project demonstrates how to build an end-to-end data engineering and analytics pipeline using Microsoft Fabric. It covers data ingestion, transformation, and visualization using Data Factory, Data Engineering, and Power BI.

The pipeline processes earthquake event data sourced from the USGS (United States Geological Survey) API.

Technologies Used: Python, PySpark, Microsoft Fabric (Data Engineering, Data Factory), Power BI

Getting Started

To get started with this project:

Download the notebooks from the repository

Follow the step-by-step guidance provided in the YouTube tutorial

Run the notebooks in sequence: Bronze → Silver → Gold

Repository Contents
Worldwide Earthquake Events API – Bronze Layer Processing

This notebook ingests raw earthquake data directly from the USGS API. It performs minimal processing and stores the data in its original format, forming the foundation for downstream processing.

Worldwide Earthquake Events API – Silver Layer Processing

This notebook cleans, transforms, and enhances data from the Bronze layer. It improves data quality and prepares the dataset for analytical use.

Worldwide Earthquake Events API – Gold Layer Processing

In this final stage, the notebook refines data into business-ready datasets. These datasets are optimized for insights, reporting, and dashboarding in Power BI.

Architecture Approach

This project follows the Medallion Architecture pattern:

Bronze Layer – Raw data ingestion

Silver Layer – Cleaned and transformed data

Gold Layer – Analytics-ready data

Prerequisites

Microsoft Fabric account

Fabric Administrator access (or access to an Admin account)

Familiarity with Python, PySpark, and data engineering concepts

Basic Power BI knowledge
