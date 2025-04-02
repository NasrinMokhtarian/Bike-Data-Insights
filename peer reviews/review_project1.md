# Peer Review: Airbnb Data Engineering Project by [kevinkevin556](https://github.com/kevinkevin556/airbnb-de-project.git)

## 🔹 Problem Description (4/4)  
The README provides a clear problem statement: designing a data pipeline for Airbnb using data from Inside Airbnb.

It explains the goal of extracting, loading, and transforming data for different stakeholders (data analysts, data scientists, and LLM engineers).

The problem is well-described and clearly defines the use case and intended users.
## 🔹 Cloud Usage (4/4)  
The project uses Google Cloud Platform (GCP) for the data warehouse (BigQuery) and storage (Google Cloud Storage).

Terraform is used for infrastructure as code (IaC) to provision cloud resources.

The project provides both on-premise and cloud-based ELT solutions. 

## 🔹 Data Ingestion (Batch) (4/4)  
The project supports both batch processing via Apache Airflow and streaming isn't mentioned, so I'll evaluate based on batch.

Batch Processing / Workflow Orchestration (4 Points)
Apache Airflow is used for end-to-end workflow orchestration with multiple steps in the DAG, uploading data to a data lake (Google Cloud Storage) and then into a warehouse (BigQuery).

The README describes how to activate DAGs for both on-premise and cloud setups.

## 🔹 Data Warehouse (4/4)  
Google BigQuery is used as the data warehouse.

The README states that dimension modeling is applied for better understanding of the dataset.

The dbt documentation (linked) likely includes optimizations like partitioning and clustering, but since it's not explicitly described in the README, we would need to check the dbt models to confirm. 

## 🔹 Transformations (4/4)  
The project uses dbt for data transformations.

It includes custom dbt macros and generic tests, which are mentioned in the README.

## 🔹 Dashboard (4/4)  
A Looker Studio dashboard is provided.

The README mentions that the final result can be viewed via a link (which should ideally show at least two tiles).

## 🔹 Reproducibility (4/4)  
The README provides step-by-step setup instructions for both on-premise (PostgreSQL) and cloud-based (GCP) deployments.

Instructions cover setting up GCP credentials, running Airflow, and configuring Terraform.

The teardown process for cloud resources is also documented, which is a good practice.

### **Final Score: 28/28**  
 

