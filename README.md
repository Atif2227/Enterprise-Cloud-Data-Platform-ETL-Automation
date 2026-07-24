# Enterprise-Cloud-Data-Platform-ETL-Automation
Modernized enterprise reporting by consolidating 12+ years of historical data into a scalable cloud platform with automated ETL pipelines and executive analytics using Microsoft Fabrics

# Introduction

This project demonstrates the design and implementation of a modern enterprise data platform using **Microsoft Fabric**. It consolidates data from multiple sources—including LMS OData, Oracle ERP, and shared file systems—into a centralized Lakehouse, enabling scalable data integration, automated ETL processes, and high-performance analytics.

The solution leverages Microsoft Fabric Data Pipelines, Dataflows Gen2, Notebooks, and a Bronze–Silver–Gold Lakehouse architecture to automate historical and incremental data loading, perform data transformation and validation, and create analytics-ready datasets. A Power BI Semantic Model built on the Gold layer provides a reliable foundation for enterprise reporting and business intelligence.

The result is a fully automated, cloud-native data platform that improves data quality, reduces manual effort, accelerates reporting, and delivers a single source of truth for enterprise decision-making.

# Enterprise Data Integration & Modern Lakehouse Platform using Microsoft Fabric

## Challenge

- Enterprise data was distributed across multiple systems including LMS OData, Oracle ERP, and shared Excel files.
- No centralized data platform existed, resulting in fragmented and inconsistent reporting.
- Large LMS OData datasets could not be efficiently processed using traditional Power BI refresh mechanisms.
- Reporting relied heavily on manual data preparation and semi-automated workflows.
- Historical data analysis was limited due to performance constraints.
- Multiple disconnected data sources increased the risk of data inconsistencies and reporting errors.
- The organization required a scalable, automated, and cloud-native data integration platform capable of supporting enterprise analytics.

---

## Solution

- Designed and implemented an enterprise data platform using Microsoft Fabric Lakehouse architecture.
- Integrated data from LMS OData, Oracle ERP, and shared folders into a centralized Lakehouse.
- Developed automated ETL pipelines using Fabric Dataflows Gen2 and Data Pipelines.
- Implemented staged historical data loading for large datasets followed by dynamic incremental refresh using rolling 30-day windows.
- Built automated Delta Lake MERGE (UPSERT) processes using Fabric Notebooks and PySpark to efficiently update existing records and insert new records.
- Established a Bronze-Silver-Gold Lakehouse architecture to support scalable data engineering, business transformations, and reporting.
- Implemented data quality validation during ingestion to eliminate invalid source values before downstream processing.
- Built a centralized orchestration pipeline with dependency management, automated scheduling, failure notifications, and execution monitoring.
- Created a Power BI Semantic Model from Gold-layer datasets to support enterprise dashboards and advanced analytics.

---

## Impact

- Established a single source of truth across multiple enterprise data sources.
- Eliminated manual ETL execution through fully automated data pipelines.
- Significantly reduced processing time by refreshing only recently modified records instead of reloading historical data.
- Improved reporting performance and scalability for large enterprise datasets.
- Increased data consistency and reliability through centralized data management.
- Enhanced data quality with automated cleansing and validation during ingestion.
- Enabled scalable enterprise reporting using a structured Bronze-Silver-Gold architecture.
- Delivered a robust analytics platform capable of supporting enterprise dashboards and future AI and advanced analytics initiatives.

---

## Live Dashboard

🔗 **View Power BI Report**

> *(Power BI report link will be added here.)*

---

## Media

📷 **Project Screenshots**

> *(Screenshots will be added here.)*

🎥 **Project Demo Video**

> *(Video link will be added here.)*

---

# Tech Stack

## Platform

- Microsoft Fabric
- Microsoft Power BI

## Data Engineering

- Fabric Lakehouse
- Dataflows Gen2
- Data Pipelines
- Fabric Notebooks
- PySpark
- Delta Lake
- Power Query (M)
- SQL Analytics Endpoint

## Data Sources

- OData API
- Oracle Database
- On-Premises File System
- On-Premises Data Gateway

---

## Detailed Documentation

🔗 **Document Link**

> *(Document link will be added here.)*