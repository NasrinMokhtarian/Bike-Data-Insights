# Bike-Data-Insights
## Batch Processing Project


📌 Project Overview

This project focuses on building a batch data pipeline for analyzing bike rental data in London. The goal is to extract, transform, and load (ETL) the dataset using Kestra, PostgreSQL, Google Cloud Storage (GCS), and BigQuery. The project follows best practices learned in the DataTalksClub Data Engineering Zoomcamp 2025.

🔍 Objectives

  * Automate batch data ingestion using Kestra.

  * Store raw data in PostgreSQL or Google Cloud Storage (GCS).

  * Perform data transformations using Spark/dbt.

  * Load processed data into BigQuery for analysis.

  *  Create SQL queries and dashboards to generate insights.

🏗️ Architecture
    graph TD;
        A[Kestra] -->|Extract| B[Raw Data Storage];
        B -->|Load| C[PostgreSQL / GCS];
        C -->|Transform| D[Spark/dbt];
        D -->|Load| E[BigQuery];
        E -->|Analyze| F[Dashboards/SQL Queries];
