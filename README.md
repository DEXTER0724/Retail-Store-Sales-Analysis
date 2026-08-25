# Retail Store Sales Analysis

A data-driven approach to uncovering performance insights across products, customers, and regions using Microsoft Power BI.

---

## 📌 Project Overview
Retail businesses process massive transactional volumes daily across multiple regions, categories, and customers. Relying on static, raw spreadsheet records makes identifying revenue trends, high-margin products, and underperforming segments challenging. 

This project transforms raw retail transaction records sourced from Kaggle into an interactive business intelligence solution using Microsoft Power BI.

---

## 🎯 Objectives
* **Monitor Core KPIs**: Track overall sales, net profit, total orders, and margins dynamically.
* **Category & Regional Insights**: Evaluate performance breakdowns across product categories and geographical territories (North, South, East, West).
* **Product Performance**: Identify top-selling, high-value items versus lower-priced inventory to optimize product placement and stock levels.
* **Trend Analysis**: Monitor monthly sales trajectories to understand demand fluctuations over time.

---

## 🛠️ Tech Stack & Tools
* **Microsoft Excel**: Data cleaning, schema structuring, and initial storage.
* **Power BI Desktop**: Data modeling, DAX computations, and interactive dashboard design.
* **Power BI Service**: Report publishing and dashboard sharing.

---

## 📊 Dataset & Schema Structure

The data model connects sales transactions with product-level details:

* **Sales Table**: `Order ID`, `Order Date`, `Product ID`, `Product Name`, `Category`, `Quantity`, `Unit Price`, `Sales Amount`, `Profit`, `Region`, `Customer Name`.
* **Product Table**: `Product ID`, `Product Name`, `Category`.

### Key DAX Measures & Metrics
* **Total Sales**: `$10,131.50` (Sum of sales amounts across all orders)
* **Total Profit**: `$2,822.10` (Sum of profit across transactions)
* **Total Quantity Sold**: `313 units`
* **Total Orders**: `92`
* **Overall Profit Margin**: `27.85%` (`[Total Profit] / [Total Sales] * 100`)

---

## 🖥️ Dashboard Architecture

The dashboard is structured into two analytical views:

### 1. Executive Summary
* High-level KPI cards for total revenue, profit margin, and volume.
* Funnel and bar charts highlighting sales distribution by category (**Furniture** and **Electronics** driving majority volume, followed by **Stationery** and **Lifestyle**).
* Donut chart mapping revenue split evenly across the four operating regions (**North**, **South**, **East**, **West**).
* Time-series breakdown of sales and order volume across months.

### 2. Product Analysis
* **Monthly Sales Trajectory**: Area chart tracking sales momentum from January through May.
* **Top & Bottom Product Pricing Analysis**: Comparative breakdown identifying high-value inventory items (e.g., *Electric Standing Desk*, *4K Monitor*) alongside lower-cost inventory drivers (e.g., *Microfiber Cloths*, *Paper Clips*).

---

## 👥 Project Team 
* **Arya Bhalerao** – Data Modeling & Category Analytics
* **Arya Dongarkar** – DAX Measure Formulation & KPI Implementation
* **Vrushabh Kunkavalekar** – Product Performance & Trend Analysis
```[cite: 2]
