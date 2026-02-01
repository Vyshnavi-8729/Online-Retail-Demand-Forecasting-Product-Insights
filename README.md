Customer Segmentation & Revenue Optimization

Databricks Analytics + Machine Learning

🚀 Executive Summary

Understanding customer behavior is critical for revenue growth, yet many retail businesses lack structured customer segmentation models.

This project builds a full Databricks Lakehouse pipeline to segment customers based on purchasing behavior and generate insights for targeted marketing and revenue optimization.

🎯 Problem Statement

Retail organizations often treat all customers equally, missing opportunities for personalization and retention.

Objective:
Develop an AI-powered customer segmentation system that:

Identifies high-value customers

Groups customers by purchase behavior

Supports personalized marketing strategies

📊 Dataset

Source: Kaggle – Online Retail Dataset

Databricks Table: workspace.retail.online_retail

Key Fields Used:

CustomerID

Quantity, UnitPrice

InvoiceDate

Country

🏗️ Architecture (Medallion Architecture)

Bronze: Raw transactional data ingestion

Silver: Cleaned customer transactions

Gold: Customer-level aggregates and behavioral features

⚙️ Data Engineering

Cleaned null CustomerID values

Filtered invalid and cancelled transactions

Built customer metrics:

Total revenue

Purchase frequency

Average order value

Optimized Delta tables

📊 Analytics & Insights

Customer revenue distribution

Country-wise customer contribution

RFM-style analysis (Recency, Frequency, Monetary)

Visual segmentation insights

🤖 Machine Learning

ML Task: Customer segmentation (clustering)

Features: Total spend, purchase count, average order value

Model: K-Means Clustering

Evaluation: Cluster interpretability and business meaning

🧪 MLflow Tracking

Logged clustering parameters

Stored models and metrics

Compared clustering runs for optimal segmentation

💼 Business Impact

Identifies high-value and low-value customers

Enables targeted promotions

Improves customer retention strategy

Supports revenue optimization

🛠️ Tools & Technologies

Databricks Community Edition

PySpark & Spark SQL

Delta Lake

MLflow

Python

▶️ How to Run

Open the Databricks notebook

Attach cluster

Run all cells sequentially

👤 Author


Vysh
Databricks + Codebasics Resume Project Challenge
