# SIOP Forecast Analysis Dashboard (Power BI)

## 📌 Project Overview
This project analyzes Sales, Inventory & Operations Planning (SIOP) forecast data using Power BI.  
It transforms multiple forecast snapshots into a structured lag-based model for comparing forecast evolution over time.

## 🧠 Business Problem
Forecast data is stored in multiple monthly snapshots (As Of Periods).  
The goal is to:
- Compare forecasts across Resultant, Lag 0, and Lag 1
- Track forecast accuracy and bias
- Enable executive-level reporting for Revenue, Non-Revenue, and Capex

## ⚙️ Data Transformation (Power Query)
- Merged multiple snapshot tables
- Created lag-based structure:
  - Resultant (Latest forecast)
  - Lag 0 (Previous month)
  - Lag 1 (Two months prior)
- Standardized dimensions: Item, Country, Period

## 📊 KPIs Used
- Forecast Accuracy % = 1 - ABS(Lag Qty - Actual Qty) / Actual Qty
- Forecast Bias % = (Lag Qty - Actual Qty) / Actual Qty

## 📈 Dashboard Features
- Executive view for Revenue, Non-Revenue, Capex
- Lag selection filter (Resultant / Lag 0 / Lag 1)
- Country-wise performance analysis
- Forecast trend comparison

## 🧰 Tools Used
- Power BI
- Power Query
- Excel (.xlsb dataset)

## 📷 Dashboard Preview
(Add screenshots here)

## 🚀 Key Insights
- Forecast variance reduces significantly in Lag 0 compared to Resultant
- Revenue forecasts show higher stability than Capex
- Certain countries show consistent bias patterns

## 👤 Author
Karthikeya Cherukuri
