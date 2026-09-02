# Adam E-Commerce Sales Dashboard

An interactive Power BI dashboard analyzing e-commerce order and profitability data, built to help business teams track sales performance, profit trends, and customer purchasing behavior at a glance.

## Overview

This dashboard consolidates order-level transaction data into a single-page interactive report, letting stakeholders filter by time period and category to explore where sales and profit are coming from — and where they're being lost.

## Data Model

Two related tables power the report:
- **Orders** — order date, customer name, state, order-level details
- **Details** — category, sub-category, payment mode, amount, profit, quantity, AOV

## Key Metrics (KPI Cards)

- **Sum of Amount** — total sales value
- **Sum of Profit** — total profit generated
- **Average Order Value (AOV)**
- **Sum of Quantity** — total units sold

## Dashboard Visuals

- **Column charts** — profit and sales trends by Order Date (Month / Quarter hierarchy)
- **Bar charts** — category and state-wise performance comparison
- **Donut charts** — category and payment-mode share breakdown
- **Slicers** — interactive filters for dynamic, on-the-fly analysis
- **Custom dark-gradient themed background** for a clean, modern look

## Dimensions Analyzed

- Category & Sub-Category
- State (regional distribution)
- Payment Mode
- Customer Name
- Order Date (Month / Quarter)

## Tools & Techniques Used

- **Power BI Desktop** — report design and visualization
- **Power Query** — data transformation
- **DAX** — measures for Amount, Profit, AOV, and Quantity aggregations
- **Data Modeling** — relationship between Orders and Details tables

## Key Insights

- Profit and sales trends by month/quarter reveal seasonal performance patterns
- Category and sub-category breakdown highlights top-performing product lines
- State-wise comparison identifies highest and lowest performing regions
- Payment mode split shows customer preference trends

## Skills Demonstrated

Power BI · DAX · Power Query · Data Modeling · Data Visualization · Business Analytics
