# Inventory and Supply Chain Management Analysis Dashboard

## 📌 Project Overview

This Power BI dashboard provides insights into inventory performance, warehouse efficiency, transportation costs, lead times, order fulfillment, and inventory levels across multiple regions and product categories.

The dashboard helps businesses optimize inventory management, reduce operational costs, and improve supply chain decision-making.

---

## 🎯 Business Problem

Organizations often face challenges such as:

- Excess inventory and stock shortages
- High transportation costs
- Long supplier lead times
- Poor warehouse utilization
- Backorders affecting customer satisfaction

This dashboard helps monitor these metrics and supports data-driven supply chain decisions.

---

## 📊 Key KPIs

| KPI | Value |
|------|------|
| Warehouse Utilization | 34.08 |
| Days Sales of Inventory | 15.56 |
| Inventory Turnover Ratio | 23.47 |

---

## 📈 Dashboard Features

### Warehouse Utilization
- Tracks warehouse space usage
- Helps optimize storage capacity

### Transportation Cost Analysis
- Compares transportation costs by region
- Evaluates category-wise logistics expenses

### Units Sold Analysis
- Year-over-year sales trend monitoring
- Identifies business growth patterns

### Lead Time Analysis
- Measures supplier delivery performance
- Category-level lead time comparison

### Order Status Monitoring
- Fulfilled Orders
- Pending Orders
- Canceled Orders

### Inventory Level Analysis
- Inventory comparison by category and region
- Supports stock optimization decisions

---

## 🛠 Tools & Technologies

- Power BI
- DAX
- Power Query
- Data Modeling
- Data Cleaning
- Excel Dataset

---

## 📉 Visualizations Used

- KPI Cards
- Gauge Chart
- Donut Chart
- Clustered Column Chart
- Line Chart
- Bar Chart
- Slicers

---

## 📐 Sample DAX Measures

```DAX
Warehouse Utilization =
DIVIDE([Used Capacity],[Total Capacity])*100

Inventory Turnover =
DIVIDE([Cost of Goods Sold],[Average Inventory])

DSI =
DIVIDE([Average Inventory],[Cost of Goods Sold])*365
