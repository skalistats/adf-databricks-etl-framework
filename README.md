## ADF Databricks ETL Framework

This repository demonstrates a metadata-driven ETL framework built using Azure Data Factory and Azure Databricks for scalable and reusable cloud data pipelines.

### Overview
The framework is designed to orchestrate ingestion and transformation workflows using configuration-driven logic. Azure Data Factory handles scheduling and orchestration, while Databricks notebooks perform scalable data processing and transformations.

### Key Features
- Metadata-driven ingestion
- Parameterized pipeline execution
- Azure Data Factory orchestration
- Databricks notebook-based transformations
- Incremental and full load support
- Configurable control tables
- Audit logging and monitoring
- Reusable framework design

### Tech Stack
- Azure Data Factory
- Azure Databricks
- PySpark
- Spark SQL
- SQL
- ADLS Gen2
- Delta Lake

### Folder Structure
- `pipelines/` ADF pipeline definitions and orchestration notes
- `notebooks/` Databricks notebooks for ETL processing
- `config/` metadata and configuration files
- `docs/` architecture and design documentation
- `sql/` SQL scripts for control tables and validation

### Example Workflow
1. Read metadata from control/configuration tables
2. Trigger source-specific ingestion pipeline in ADF
3. Land raw data into storage
4. Execute Databricks notebook for transformation
5. Load curated output into target layer
6. Log execution details and validation results

### Skills Demonstrated
- Azure ETL architecture
- Metadata-driven framework design
- Cloud orchestration
- PySpark transformation development
- Reusable pipeline engineering
- Monitoring and audit implementation
