# Sales & Customer Dashboard

A comprehensive Tableau project delivering two interconnected dashboards — the **Sales Dashboard** and the **Customer Dashboard** — designed to give sales managers and executives clear, actionable insights into sales performance and customer behavior.

---

## Project Overview

The goal of this project is to provide stakeholders with a unified view of sales trends and customer data. Both dashboards are built with flexibility and interactivity at their core, enabling users to filter, compare, and explore data across time periods, product categories, and geographic regions.

---

## Dashboard Requirements

### Sales Dashboard

**Purpose**
Present an overview of sales metrics and trends, enabling year-over-year performance analysis and identification of key patterns.

**Key Features**

| Feature | Description |
|---------|-------------|
| KPI Overview | Summary of total sales, profits, and quantity for the current and previous year |
| Sales Trends | Monthly KPI data comparing current vs. previous year, with highest and lowest months highlighted |
| Product Subcategory Comparison | Side-by-side sales performance across subcategories, including profit margin comparison |
| Weekly Sales & Profit Trends | Weekly sales and profit for the current year, with average benchmarks and above/below-average highlights |

---

### Customer Dashboard

**Purpose**
Provide an overview of customer data, trends, and behaviors to support marketing teams and management in understanding customer segments and improving satisfaction.

**Key Features**

| Feature | Description |
|---------|-------------|
| KPI Overview | Summary of total customers, total sales per customer, and total orders for both years |
| Customer Trends | Monthly KPI data comparing current vs. previous year, with peak and low months highlighted |
| Customer Distribution by Orders | Distribution of customers by number of orders placed, revealing loyalty and engagement patterns |
| Top 10 Customers by Profit | Ranked list with order count, current sales, profit, and last order date |

---

## Design & Interactivity

### Mockups

Before development, mockups were created to plan the visual structure and container layout of both dashboards.

**Sales & Customer Mockup** — Used to plan the overall layout and placement of key elements.

![Sales & Customer Mockup](https://github.com/assets/6f0dcd3d-180e-4ce4-b138-b69ff06ea9f5)

**Container Mockup** — Outlines the vertical and horizontal container structure for a flexible, organised layout.

![Container Mockup](https://github.com/assets/9ad05eeb-aa29-4822-8e07-5f8a2f801e75)

### Interactivity

- **Dynamic Year Selection** — Users can select any year to view and compare historical data.
- **Seamless Navigation** — Interactive icons allow users to switch between the Sales and Customer dashboards without friction.
- **Chart-Level Filtering** — Data can be filtered directly through the charts for in-depth exploration.

### Data Filters

Users can filter all data by:
- **Product**: category and subcategory
- **Location**: region, state, and city

---

## Project Workflow

### 1. Analyze Requirements
- Collected user requirements and defined key objectives
- Selected appropriate chart types for each KPI
- Created initial mockups to visualize dashboard layouts

### 2. Build Data Source
- Connected to the data source and established Tableau connections
- Built a comprehensive data model to support the analysis
- Renamed fields and tables for clarity and consistency
- Verified and corrected data types to ensure accuracy

### 3. Build Charts
- Developed and tested calculated fields to support all visualizations
- Constructed charts aligned with mockups and requirements
- Applied formatting: removed unnecessary gridlines, cleaned axes, standardised coloring, and added informative tooltips

### 4. Build Dashboard
- Designed a container structure to organise the dashboard layout
- Assembled all charts within the container framework
- Applied final formatting: distributed objects evenly, adjusted colors and sizes, ensured all charts render within the "Entire View" setting
- Added legends, inner/outer padding, dynamic filters, and navigation icons

---

## Results

**Sales Dashboard**

![Sales Dashboard](https://github.com/assets/c6f37aaa-c069-43de-9440-85da6cefb362)

**Customer Dashboard**

![Customer Dashboard](https://github.com/assets/5fd66a43-48e5-4fb1-9300-6671a765668a)

---

## Repository Structure

```
Sales_Customer_Dashboard/
│
├── assets/
│   ├── Sales_Customer_Mockup.png
│   ├── Container_Mockup.png
│   ├── Sales_Dashboard.png
│   └── Customer_Dashboard.png
│
└── README.md
```