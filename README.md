📦 SQL Data Warehouse & Analytics Project

A complete end-to-end data engineering and analytics project built using SQL Server.
This repository demonstrates raw data ingestion, data modeling, ETL pipelines, and SQL-based analytics following modern industry standards.

⸻

🏗️ Data Architecture (Medallion)

This project follows the Medallion Architecture:

🔹 Bronze Layer – Raw Data
	•	Stores raw data ingested from CSV files (ERP + CRM).
	•	Loaded directly into SQL Server without transformations.

🔸 Silver Layer – Cleaned Data
	•	Data cleaning, validation, and standardization.
	•	Resolves duplicates, missing values, and type issues.

🟡 Gold Layer – Business Data
	•	Final star-schema model with Fact & Dimension tables.
	•	Used for reporting, dashboards, and analytics queries.

⸻

📖 Project Overview

This project includes:
	•	Data Architecture: Designing a modern SQL-based warehouse
	•	ETL Pipelines: Extract → Transform → Load using SQL
	•	Data Modeling: Fact/Dimension schema for analytics
	•	Analytics: SQL queries for KPIs and business insights

⸻

🎯 Skills Demonstrated
	•	SQL Development
	•	Data Engineering
	•	ETL Pipeline Design
	•	Data Modeling (Star Schema)
	•	Data Analytics & Reporting

⸻

🚀 Project Requirements

1. Data Engineering
	•	Import data from ERP and CRM CSV sources.
	•	Clean and standardize data for quality and consistency.
	•	Integrate both sources into a unified analytical model.
	•	Focus on the latest dataset (no historization needed).
	•	Provide documentation for data architecture and schema.

2. Analytics & Reporting

Generate insights using SQL on:
	•	Customer behavior
	•	Product performance
	•	Sales trends

These insights help stakeholders make informed business decisions.