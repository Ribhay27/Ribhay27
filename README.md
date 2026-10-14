# Hi, I'm Ribhay Singh 👋

**Data Science Graduate (ASU) building end-to-end data & ML systems — from pipelines to production**

Portfolio · Email · LinkedIn

## About Me

I'm a Data Science graduate from Arizona State University who likes working across the full lifecycle of a data problem — from ingesting messy real-world data to building and evaluating models and shipping systems people can actually use.

As a Software Engineer Intern at Initialyze, I worked on ETL pipelines and REST APIs using Databricks. Since then, I've been building end-to-end data and ML projects independently, including a hospital quality analytics platform and a time-series forecasting benchmark comparing traditional ML, neural networks, and Transformers.

## Tech Stack

### Languages
Python · SQL · Java · C++

### Data Engineering & ML
PySpark · Databricks · Airflow · dbt · PostgreSQL · XGBoost · PyTorch

### Deployment & Cloud
FastAPI · Streamlit · AWS · GCP

### Visualization
Tableau · Matplotlib · Seaborn

---

# Featured Projects

## CareMetrics — Clinical Performance & Readmission Risk Analytics Pipeline

End-to-end hospital quality analytics platform built on public CMS and CDC data. Airflow orchestrates ingestion, dbt transforms it into a PostgreSQL warehouse, and XGBoost/LightGBM models predict 30-day readmission risk with SHAP-based explainability — served through a FastAPI backend and a Streamlit dashboard.

**Airflow · dbt · PostgreSQL · XGBoost · LightGBM · SHAP · FastAPI · Streamlit**

---

## Electricity Demand Forecasting — Accuracy vs. Model Complexity

Time-series forecasting benchmark built on **50,000+ hours of German electricity-demand data** to answer a practical ML question: **when does a more complex forecasting model actually become worth using?**

The task was to use the previous **168 hours of demand to forecast the next 24 hours** using chronological train/validation/test splits to avoid time-series leakage.

I benchmarked five approaches across increasing levels of model complexity:

- Seasonal Naive baseline
- XGBoost
- DLinear
- LSTM
- PatchTST Transformer

PatchTST achieved the best test performance at **2.57% WAPE**, but XGBoost finished extremely close at **2.64%**. DLinear also outperformed the more complex LSTM, showing that additional architectural complexity did not consistently translate into better forecasting performance.

The main finding was that while PatchTST produced the lowest forecasting error, **XGBoost offered the strongest accuracy-to-complexity tradeoff** when implementation effort, tuning, training cost, maintainability, and deployment simplicity were also considered.

**Python · PyTorch · XGBoost · Time-Series Forecasting · LSTM · Transformers · PatchTST**

---

## HireLens — Job Market Intelligence Platform

Scrapes job postings, pipes them through a PostgreSQL data pipeline, extracts in-demand skills with NLP, and surfaces hiring trends across a 5-page Streamlit dashboard.

**Python · PostgreSQL · NLP · Streamlit**

---

## SBA Loan Default Prediction

ML pipeline predicting SBA 7(a) loan default risk from 1.2M+ historical loan records, surfacing which features matter most for repayment outcomes.

**Python · Machine Learning**

---

## FitPro

Full-stack fitness analytics app predicting calorie burn with Random Forest and XGBoost, with real-time tracking via PostgreSQL/Databricks and a Streamlit dashboard for progress visualization.

**Python · Random Forest · XGBoost · PostgreSQL · Databricks · Streamlit**

---

## World Happiness Explorer

End-to-end analysis of global happiness data — cleaning, EDA, and regression modeling to uncover the socio-economic drivers of national well-being, visualized in Tableau.

**Python · Tableau · Regression**

---

## Real Estate Forecasting

Home price forecasting tool built with multiple regression analysis.

**Python · Regression**

---

## EchoMind AI

AI journaling assistant that turns reflections into emotional summaries you can revisit over time, built with FastAPI and an LLM backend.

**FastAPI · LLM**

---

## Currently Learning

- System design for backend/data engineering roles
- Advanced ML techniques & model tuning
- Spark and cloud-native deployment on GCP/AWS
- Building AI agents with LangChain and vector databases
- Modern frontend frameworks (React)

---

## Let's Connect

📫 **Email:** singhribhay@gmail.com  
🌐 **Portfolio:** ribhaysingh.vercel.app  
💼 **LinkedIn:** linkedin.com/in/ribhaysingh  
📍 **Phoenix, AZ** — open to internships & full-time roles in Data Engineering, Data Science, Data Analytics, and Machine Learning
