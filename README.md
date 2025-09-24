# Inventory and Supply Chain Management Dashboard

A Power BI dashboard that surfaces key inventory KPIs (warehouse utilization, days sales of inventory, turnover), visualizes transportation cost by region/category, tracks backorders and shows systems-level views for decision-making.

This dashboard helps leaders quickly identify inventory inefficiencies, regional logistic cost drivers, backorder hotspots, and category-level lead time issues so they can prioritize operational actions and reduce holding & logistics costs.

### Tech Stack

Power BI Desktop – report authoring (.pbix)

Power Query (M) – data cleaning and transformation

DAX – KPI measures and time-intelligent calculations

Data – Inventory_SupplyChain_Dataset.csv (included)

### 	Data source & structure

Primary file: Inventory_SupplyChain_Dataset.csv

Date (YYYY-MM-DD) — transaction or snapshot date

Region — East / West / North / South

Category — Electronics / Clothing / Accessories / Furniture

Units_Sold — integer

Inventory_Level — units or $ (consistent unit across file)

COGS — cost of goods sold (period)

Transportation_Cost — numeric (USD)

Warehouse_Capacity — numeric (e.g., square meters or pallet positions)

Warehouse_Used — numeric (same units as capacity)

Lead_Time_Days — days from order to delivery (for category)

Order_Status — Fulfilled / Pending / Canceled / Backorder

Backorder_Count — integer


### 5) Features / highlights

### Business Problem

Organizations often face:

• Excess inventory in some regions while stockouts occur in others

• High transportation costs in specific categories/regions

• Unknown lead-time variability across suppliers/categories

• Backorders and long fulfillment times impacting customer service

### Goal of the dashboard

• Provide a single-source-of-truth for operations & supply chain KPIs.

• Track trends and identify problem areas (regions, categories).

• Provide actionable signals for inventory rebalancing, vendor engagement, and transport optimization.

### Walkthrough of key visuals

• Top-left KPI cards: Warehouse Utilization, Days Sales of Inventory (DSI), Inventory Turnover Ratio.

• Gauge / Donut: Warehouse Utilization (current vs capacity).

• Bar chart (stacked): Transportation cost by Region & Category.

• Line chart: Units sold by Year.

• Donut / Pie: Average lead time by Category.

• Bar chart: Count of Backorders by Order Status (with labels).

• Horizontal Bar chart / Matrix: Inventory level by Category and Region.

### Business impact & insights

• Pinpoint low-turn inventory (optimize working capital).

• Identify categories with high transportation cost for renegotiation or consolidation.

• Expose regions with backorder concentration for faster replenishment.

• Support monthly leadership reviews with one-page executive summary.

### 6.	Screenshots / Demos
Example: ![Dashboard Preview](https://github.com/Ayan1901/Inventory-and-Supply-Chain-Analytics-Dashboard/blob/main/Snapshot%20of%20the%20dashboard.png)
