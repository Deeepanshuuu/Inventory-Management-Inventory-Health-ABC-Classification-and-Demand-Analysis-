# Inventory Management, Inventory Health, ABC Classification & Demand Analysis

## Project Overview

This project analyses supply chain inventory data using **Microsoft Power BI** to evaluate inventory health, demand patterns, reorder requirements, SKU-level sales contribution, and inventory performance across multiple warehouses.

The objective is to convert raw inventory data into actionable insights that can support inventory monitoring, replenishment planning, demand forecasting, and better inventory allocation decisions.

The analysis uses historical SKU-warehouse-level data covering 365 days across multiple warehouses and suppliers.

---

## Business Objectives

- Evaluate inventory levels against defined reorder points.
- Identify SKU-warehouse combinations requiring replenishment attention.
- Analyse SKU contribution to overall sales through ABC classification.
- Compare actual demand with forecast demand.
- Understand inventory distribution across warehouses.
- Analyse sales, cost of goods sold, and gross profit.
- Identify potential areas for improving inventory planning and control.

---

## Tools & Techniques

| Category | Tools / Techniques |
|---|---|
| Data Analysis & Visualization | Microsoft Power BI |
| Data Modelling | Power BI Data Model |
| Calculations | DAX |
| Inventory Analysis | Inventory Health & Reorder Point Analysis |
| SKU Segmentation | ABC Classification |
| Forecast Evaluation | Weighted Absolute Percentage Error (WAPE) |
| Business Improvement | Inventory Monitoring & Replenishment Analysis |

---

## Dataset Overview

**Dataset:** High-Dimensional Supply Chain Inventory Dataset  
**Source:** Kaggle

[Access the dataset](https://www.kaggle.com/datasets/ziya07/high-dimensional-supply-chain-inventory-dataset)

| Dataset Attribute | Details |
|---|---:|
| Total Records | 91,250 |
| Total Columns | 15 |
| Time Period | 1 January – 30 December 2024 |
| Unique SKUs | 50 |
| Warehouses | 5 |
| Suppliers | 10 |
| Regions | 4 |
| Daily Observations | 365 |

### Key Data Fields

- Date
- SKU_ID
- Warehouse_ID
- Supplier_ID
- Region
- Units_Sold
- Inventory_Level
- Supplier_Lead_Time_Days
- Reorder_Point
- Order_Quantity
- Unit_Cost
- Unit_Price
- Promotion_Flag
- Stockout_Flag
- Demand_Forecast

---

## Key Performance Indicators

The following indicators were evaluated as part of the analysis.

| KPI | Result |
|---|---:|
| Total Units Sold | 1,829,979 |
| Total Sales Revenue | ₹33.43 Million |
| Total Cost of Goods Sold | ₹22.34 Million |
| Gross Profit | ₹11.09 Million |
