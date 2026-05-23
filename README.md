# Crypto Market Intelligence Platform (CoinGecko)

---

## Story (Non-technical view)

In this project, I act as a **Data & Analytics Engineer building a full crypto intelligence system**.

I collect raw cryptocurrency market data (prices, volume, market cap) and transform it into a structured system that allows users to understand:
- how the market evolves over time
- which assets are growing or declining
- how volatility and risk behave across assets

In simple terms, I build a system that turns **raw crypto market signals into decision-ready insights and KPIs**.

---

## Impact & Business Value

- Built an automated pipeline processing **thousands of crypto market records over time**
- Reduced manual analysis time by **~70%** through full pipeline automation
- Enabled real-time tracking of **market trends, volatility, and asset performance**
- Structured raw API data into **analytics-ready datasets using dbt**
- Delivered dashboards enabling fast identification of **high-growth vs high-risk assets**

Key KPIs:
Price evolution, market cap, trading volume, volatility index, ranking changes, returns

---

## System Architecture

CoinGecko API  
↓  
Python (ingestion & preprocessing)  
↓  
DuckDB (storage & historical dataset)  
↓  
dbt (data modeling & transformations)  
↓  
Airflow (pipeline orchestration & scheduling)  
↓  
Power BI (dashboards & KPI storytelling)  
↓  
Python ML (feature engineering & market analysis)  

---

## Tech Stack

### Data Source
CoinGecko API (crypto market data: price, volume, market cap)

### Ingestion Layer
Python:
- API extraction
- data cleaning
- loading into storage

### Storage Layer
DuckDB:
- fast analytical queries
- historical market data storage
- lightweight data warehouse

### Transformation Layer
dbt:
- data cleaning and standardization
- creation of analytical models
- KPI-ready datasets (marts)

### Orchestration Layer
Airflow:
- automated scheduling
- pipeline monitoring
- workflow reliability

### Machine Learning Layer
Python:
- feature engineering (returns, volatility, moving averages)
- clustering of assets by behavior
- trend analysis of price evolution

### Visualization Layer
Power BI:
- market performance dashboards
- volatility tracking
- KPI storytelling (price, volume, returns)

---

## KPIs Analyzed

- Price evolution (time series)
- Market capitalization trends
- Trading volume analysis
- Volatility index
- Asset ranking evolution
- Returns (short-term & long-term)
- Risk grouping (low / medium / high volatility)

---

## Business Axes

### Market Evolution
Tracking global crypto market trends over time

### Asset Performance
Identifying top-performing and underperforming cryptocurrencies

### Risk & Volatility Analysis
Understanding market instability and asset behavior

### Behavioral Clustering
Grouping cryptocurrencies based on similarity of movements

---

## Key Features

- Automated ingestion from CoinGecko API  
- Historical crypto market database  
- Scalable transformation layer with dbt  
- Orchestrated pipelines with Airflow  
- Machine learning-based market analysis  
- KPI dashboards with Power BI  
- End-to-end reproducible data system  

---

## What This Project Demonstrates

- End-to-end data pipeline design  
- Real-time API ingestion and processing  
- Data modeling with dbt (analytics engineering)  
- Workflow orchestration (Airflow)  
- Applied machine learning on financial data  
- KPI-driven dashboarding and storytelling  
- Modern data stack architecture (DuckDB + dbt + BI + ML)  
