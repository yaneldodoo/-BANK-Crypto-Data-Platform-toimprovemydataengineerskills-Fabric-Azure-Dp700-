# Crypto Market Intelligence Platform (CoinGecko)

---

## Project Overview

I am building an end-to-end data platform using the CoinGecko API to analyze the cryptocurrency market over time.

The goal of this project is to transform raw market data into structured, reliable, and actionable insights through a complete data pipeline, similar to what is used in real companies.

This platform is inspired by tools like Finary, but focuses on data analysis and market understanding rather than financial advice.

---

## Objective

The platform is designed to:

- Collect cryptocurrency market data automatically  
- Store and historize data over time  
- Transform raw data into analytical models  
- Build machine learning models for market behavior analysis  
- Automate the entire data pipeline  
- Generate data-driven insights on market trends and performance  

---

## Data Scope

The platform processes cryptocurrency market data such as:

- Prices  
- Market capitalization  
- Trading volume  
- Market rankings  
- Historical price evolution  

---

## System Architecture

CoinGecko API  
↓  
Apache Nifi for ingestion
↓  
Apache Airflow for workflow orchestration and scheduling 
↓  
Python (data ingestion layer)  
↓  
DuckDB (raw data storage and historization)  
↓  
dbt (data transformation layer)  
↓  
Machine Learning Layer (feature engineering + models)  
↓  
Power BI (analytics and dashboard layer)

---

## Tech Stack

### Data Source
CoinGecko API for cryptocurrency market data.

---

### Orchestration Layer
Dataiku is used for:

- Scheduling pipelines  
- Automating workflows  
- Monitoring executions  

---

### Data Ingestion
Python is used for:

- API requests  
- Data extraction  
- Basic preprocessing  
- Loading data into storage  

---

### Storage Layer
DuckDB is used for:

- Storing raw data  
- Maintaining historical datasets  
- Fast analytical queries  

---

### Transformation Layer
dbt (data build tool) is used for:

- Data cleaning and standardization  
- Building analytical models  
- Creating business-ready datasets  

---

### Machine Learning Layer

This layer adds predictive and analytical intelligence on top of the data pipeline.

It includes:

- Feature engineering (moving averages, volatility, returns)  
- Supervised learning models (regression / classification)  
- Time-based analysis of crypto price trends  
- Clustering of cryptocurrencies based on behavior  

Example use cases:

- Predicting short-term price trends (exploratory, not financial advice)  
- Classifying assets by risk or volatility level  
- Grouping cryptocurrencies with similar market behavior  

This layer is implemented using Dataiku AutoML or Python-based ML workflows.

---

### Visualization Layer
Power BI is used for:

- Market trend analysis  
- Performance tracking  
- Volatility insights  
- Machine learning outputs visualization  
- Dashboard creation  

---

### Infrastructure (Optional)
Docker is used for:

- Containerizing the project  
- Ensuring reproducibility  
- Running the full pipeline in any environment  

---

## Key Features

- Automated data ingestion from CoinGecko API  
- Historical data tracking system  
- Structured data transformation using dbt  
- Orchestrated workflows with Dataiku  
- Machine learning layer for market analysis  
- Business intelligence dashboards with Power BI  
- Reproducible environment using Docker  

---

## Machine Learning Use Cases

The ML layer is used to generate analytical insights such as:

- Market trend classification  
- Volatility-based clustering of assets  
- Short-term price movement estimation (experimental)  
- Behavioral grouping of cryptocurrencies  

Important:  
This project does not provide financial advice. It focuses on data analysis and pattern recognition in financial markets.

---

## Final Outcome

This project results in a complete crypto data intelligence system that allows structured analysis of market evolution over time, combining data engineering, analytics, and machine learning.

---

## What This Project Demonstrates

- API integration and data ingestion  
- End-to-end data pipeline design  
- SQL-based data modeling with dbt  
- Workflow orchestration with Dataiku  
- Machine learning applied to financial data  
- Business intelligence and visualization  
- Data engineering best practices  
