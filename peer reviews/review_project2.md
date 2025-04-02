# Peer Review: Chicago Traffic Incidents Pipeline by [Leonard Isaac](https://github.com/leoimewore/airflow_docker.git)

## 🔹 Problem Description (2/4)  
The README briefly describes the objective but does not clearly state the problem it aims to solve.
## 🔹 Cloud Usage (2/4)  
The project is deployed on Google Cloud (BigQuery, GCS, DataProc), but there's no mention of IaC tools like Terraform. 

## 🔹 Data Ingestion (Batch) (2/4)  
Airflow is mentioned, but there’s no clear indication of a fully orchestrated end-to-end pipeline (e.g., DAG structure).

## 🔹 Data Warehouse (2/4)  
BigQuery is mentioned, but there’s no explanation for partitioning, clustering, or table optimization.

## 🔹 Transformations (4/4)  
The project uses Spark and dbt for transformations, which meets the highest criteria.

## 🔹 Dashboard (4/4)  
Looker Studio is mentioned and the README specifies the number of tiles and provides screenshots.

## 🔹 Reproducibility (0/4)  
No setup instructions or guidelines for running the project are provided.

### **Final Score: 16/28**  
 
