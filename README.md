# Pizza_Sales_Analysis
# 🍕 End-to-End Pizza Sales Analytics | Azure Data Engineering + Power BI

## 📌 Project Overview

This project demonstrates a complete end-to-end data pipeline, starting from on-premise SQL Server to cloud-based analytics and visualization. The goal is to analyze pizza sales data and generate actionable business insights using Azure services and Power BI.

---

## 🎯 Business Objective

* Analyze sales performance across time, categories, and products
* Identify peak ordering hours and customer behavior
* Enable data-driven decision making for revenue optimization

---

## 🏗️ Architecture

**On-Prem SQL Server → Azure Data Factory → Azure Blob Storage → Azure Databricks → Power BI**

---

## ⚙️ ETL Pipeline

### 🔹 Extract

* Source data from on-premise SQL Server
* Connected using Self-Hosted Integration Runtime in Azure Data Factory

### 🔹 Load (Raw Layer)

* Ingested raw data into Azure Blob Storage
* Stored data in structured format (CSV/Parquet)

### 🔹 Transform (Databricks)

* Cleaned and handled missing/null values
* Converted data types (date, time, numeric fields)
* Created derived columns (order hour, day name, month)
* Aggregated data for reporting
* Optimized data using PySpark

### 🔹 Serve (Power BI)

* Connected Azure Databricks to Power BI
* Built data model using Star Schema
* Created DAX measures for KPIs and time intelligence

---

## 🧩 Data Model

* **Fact Table:** Sales
* **Dimension Tables:** Date, Pizza Category, Pizza Name
* Designed using **Star Schema** for optimized performance

---

## 📊 Key KPIs

* Total Revenue
* Total Orders
* Total Quantity Sold
* Average Order Value (AOV)
* Average Pizzas per Order

---

## 📈 Dashboard Features

* Monthly Revenue Trend Analysis
* Peak Order Hour Analysis
* Orders by Day of Week
* Revenue by Pizza Category
* Top & Bottom Performing Pizzas
* Interactive slicers for dynamic filtering

---

## 💡 Key Insights

* Peak sales occur during evening hours (6 PM – 9 PM)
* Weekends contribute significantly higher revenue
* Classic category dominates overall sales
* Large-size pizzas generate maximum revenue
* Top 20% of pizzas contribute to majority of sales (Pareto Principle)

---

## 🛠️ Tools & Technologies

* Azure Data Factory
* Azure Blob Storage
* Azure Databricks (PySpark)
* Power BI
* SQL Server
* DAX

---

## 🚀 Outcome

Designed and implemented a scalable end-to-end data pipeline integrating on-premise and cloud systems, enabling efficient data transformation and delivering actionable insights through an interactive Power BI dashboard.

---

## 📸 Dashboard Preview
![Dashboard Preview](https://github.com/AKAMUNDRA/Pizza_Sales_Analysis.F/blob/main/Pizza%20Sales.png)




