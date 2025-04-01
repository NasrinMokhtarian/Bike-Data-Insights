#Flight Price Prediction

##Batch Processing Project

Data Ingestion with dlt

📌 Project Overview

This project focuses on building a batch data pipeline for analyzing a flight booking dataset. The goal is to extract, transform, and load (ETL) the dataset using dlt, DuckDB, pandas, and BigQuery for further analysis in Looker Studio. The project follows best practices learned in the DataTalksClub Data Engineering Zoomcamp 2025.

🔍 Objectives

Automate batch data ingestion using dlt.

Store raw data in DuckDB.

Perform data transformations using pandas.

Load processed data into BigQuery for analysis.

Create SQL queries and dashboards to generate insights.

📂 Repository Structure

├── data/                # Sample dataset (if applicable)

├── ingestion/           # dlt ingestion scripts

├── transformations/     # Data cleaning and transformation scripts

├── sql_queries/         # SQL queries for analysis

├── dashboards/          # Dashboards & reports

├── README.md            # Project documentation

📊 Dataset

Source: Flight Price Prediction dataset from Kaggle

Format: CSV

Fields: Airline, Date, Time, Price, Class (Economy/Business), Stops, etc.

Frequency: Static dataset (one-time load)

⚙️ Technologies Used

dlt (data ingestion from Kaggle to DuckDB)

DuckDB (temporary storage & processing)

pandas (data transformation & cleaning)

BigQuery (data warehousing & querying)

Looker Studio (visualization & reporting)

🔄 Batch Processing Pipeline

Extract Data: dlt downloads the dataset from Kaggle.

Store Raw Data: Data is stored in DuckDB.

Transform Data: pandas cleans and processes the data (e.g., date formatting, price conversions, stop count normalization).

Load into BigQuery: Processed data is stored for querying.

Analyze & Visualize: SQL queries + Looker Studio dashboards for insights.
