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

📂 Repository Structure
 * ├── data/                # Sample dataset (if applicable)
 * ├── kestra_flows/        # Kestra workflow YAML files
 * ├── sql_queries/         # SQL queries for analysis
 * ├── notebooks/           # Jupyter Notebooks for EDA & analysis
 * ├── dashboards/          # Dashboards & reports
 * ├── README.md            # Project documentation

📊 Dataset
   * Source: Santander Bicycle Rentals - London: [datasets](https://cycling.data.tfl.gov.uk/)
   * Format: CSV
   * Fields: Rental Start Time, End Time, Station, Bike ID, User Type, etc.
   * Frequency: Daily updates (batch processing)

⚙️ Technologies Used
   * Kestra (orchestration & scheduling)
   * PostgreSQL / Google Cloud Storage (storage layer)
   * Spark / dbt (batch transformations)
   * BigQuery (data warehousing)
   * Looker Studio (visualization & reporting)

🔄 Batch Processing Pipeline
   * Extract Data: Kestra downloads the dataset from source.
   * Store Raw Data: Data is stored in PostgreSQL or GCS.
   * Transform Data: Spark/dbt processes the data (cleaning, aggregations).
   * Load into BigQuery: Processed data is stored for querying.
   * Analyze & Visualize: SQL queries + Looker dashboards for insights.
