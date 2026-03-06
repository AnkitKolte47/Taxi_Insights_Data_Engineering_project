# 🚕  Taxi Insights Data Engineering Project (Databricks)

## 📌 Project Overview

This project demonstrates an end-to-end **Data Engineering pipeline**
built using Databricks and PySpark.

The pipeline processes NYC taxi trip data using the **Medallion
Architecture** approach:

Bronze → Silver → Gold

The goal of this project is to simulate how real companies process raw
data, clean it, and generate business insights.

------------------------------------------------------------------------

# 🏗️ Architecture

Raw Taxi Data\
⬇\
Bronze Layer (Raw Ingestion)\
⬇\
Silver Layer (Data Cleaning & Transformation)\
⬇\
Gold Layer (Business Insights & Aggregations)

------------------------------------------------------------------------

# ⚙️ Technologies Used

-   Databricks
-   PySpark
-   Apache Spark
-   Delta Tables
-   SQL
-   GitHub

------------------------------------------------------------------------

# 📂 Project Structure

taxi-insights-data-engineering/

notebooks/\
- wirte_data_to_bronze.ipynb\
- bronze_to_silver_processing.ipynb\
- business_agg_gold.ipynb

README.md

------------------------------------------------------------------------

# 🥉 Bronze Layer -- Raw Data Ingestion

Notebook: `wirte_data_to_bronze.ipynb`

### Tasks performed

-   Read raw NYC taxi trip dataset
-   Apply schema to the dataset
-   Load raw data into Bronze table
-   Store unprocessed data for future processing

This layer contains **raw and unmodified data**.

------------------------------------------------------------------------

# 🥈 Silver Layer -- Data Cleaning & Processing

Notebook: `bronze_to_silver_processing.ipynb`

### Tasks performed

-   Read data from Bronze layer
-   Clean incorrect or null values
-   Convert columns into correct data types
-   Prepare structured dataset for analytics

This layer contains **clean and structured data**.

------------------------------------------------------------------------

# 🥇 Gold Layer -- Business Insights

Notebook: `business_agg_gold.ipynb`

### Tasks performed

-   Generate business insights
-   Perform aggregations
-   Identify patterns in taxi trips
-   Create datasets for analytics

This layer contains **aggregated data used for reporting and business
analysis**.

------------------------------------------------------------------------

# 📊 Example Insights Generated

-   Number of trips per vendor
-   Vendor performance comparison
-   Aggregated trip statistics
-   Business-level metrics from taxi trips

------------------------------------------------------------------------

# 📈 Learning Outcomes

Through this project I learned:

-   Building end-to-end data pipelines
-   Implementing Medallion Architecture
-   Using PySpark for large-scale data processing
-   Working with Databricks notebooks
-   Data cleaning and transformations using Spark

------------------------------------------------------------------------

# 👨‍💻 Author

**Ankit Kolte**\
Aspiring Data Engineer passionate about building scalable data pipelines
using modern data engineering tools.

------------------------------------------------------------------------

⭐ If you like this project, feel free to explore the notebooks.
