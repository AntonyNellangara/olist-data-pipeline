# Olist Data Pipeline

### End-to-End E-commerce Data Engineering Project

An end-to-end ELT pipeline built using Snowflake, Airbyte, dbt, Apache Airflow, Python, Docker, and Power BI to transform raw Olist e-commerce data into structured, analytics-ready datasets.

## Project Overview

This project demonstrates a modern data engineering workflow, from data ingestion and cloud warehousing to data transformation, orchestration, and business intelligence.

## Architecture

```text
MySQL → Airbyte → Snowflake → dbt → Power BI
                         ↑
                  Apache Airflow
                  (Orchestration)
```

## Technology Stack

- MySQL: Source database
- Airbyte: Data ingestion and incremental loading
- Snowflake: Cloud data warehouse
- dbt Core: SQL transformations and data quality testing
- Apache Airflow: Workflow orchestration
- Python: API integration and automation
- Docker: Containerisation
- Power BI: Data visualisation and reporting

## Key Features

- Integrated MySQL with Snowflake using Airbyte across 9 incremental source streams.
- Developed 20 dbt models across staging, intermediate, and marts layers.
- Built fact and dimension models for orders, order items, customers, products, sellers, dates, and reviews.
- Implemented dbt data quality tests to validate data reliability.
- Developed Airflow DAGs with Python-based Airbyte API integration to trigger and monitor data synchronisation.
- Connected Snowflake analytical models to Power BI for interactive business reporting.

## Data Warehouse Models

The project consists of 20 dbt models across three transformation layers:

1. Staging Layer
   - 8 models
   - Materialisation: Views

2. Intermediate Layer
   - 5 models
   - Materialisation: Views

3. Marts Layer
   - 7 models
   - Materialisation: Tables and Views

Total Models: 20

## Business Insights

The transformed data supports analysis of:

- Sales and revenue performance.
- Customer purchasing behaviour.
- Product and seller performance.
- Order and delivery trends.
- Customer reviews and satisfaction.

## Future Enhancements

- Scheduled pipeline execution.
- Automated failure alerts and monitoring.
- CI/CD integration for dbt.
- Enhanced data quality monitoring.

## Skills Demonstrated

Data Engineering · ELT Pipelines · Snowflake · SQL · dbt · Airbyte · Apache Airflow · Python · Docker · Power BI

---

Project Domain: E-commerce Analytics

Dataset: Brazilian Olist E-commerce Dataset
