# Real Estate Monitor
UK Property Ownership Analysis with Microsoft Fabric

**Overview**

This end-to-end data engineering project focuses on capturing, transforming, and analyzing publicly available data about UK-registered companies that own property in England and Wales. The initial phase explores company ownership trends, purchase values, and regional distribution of commercial ownership using the UK Land Registry Corporate Ownership dataset.
The project will be built with Microsoft Fabric, combining Notebooks, OneLake, and Power BI to create an analytic pipeline.

**Objectives**

- Ingest and process Land Registry data for corporate property ownership in the UK.
- Structure the data into Bronze, Silver, and Gold layers using Lakehouse and Delta tables.
- Create a clean, queryable Silver layer ready for analysis.
- Deliver a dashboard or insights on:
    - Which companies own the most properties
    - Geographic concentration of corporate ownership
    - Trends in purchase price over time
 
**Architecture**
The solution follows a medallion architecture:
Raw CSV (Land Registry) ➡ Bronze Layer ➡ **Silver Layer** ➡ Gold Layer ➡ Visualization
