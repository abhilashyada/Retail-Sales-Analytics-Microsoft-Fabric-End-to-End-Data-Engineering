# Power BI — Retail Sales Analytics

## Report Overview

The Power BI report provides retail sales insights using the Gold layer of the Microsoft Fabric Lakehouse.

## Technical Configuration

- Platform: Microsoft Fabric
- Visualization: Power BI
- Storage mode: Direct Lake
- Semantic model: `sm_incremental_sales_analytics`
- Report: `Sales_Analytics_Incremental_Dashboard`

## Dashboard Visualizations

- Total Revenue
- Total Products
- Total Customers
- Revenue by Product Category
- Top Products by Revenue
- Top Customers by Revenue

## Validated Business Metrics

| Metric | Value |
|---|---:|
| Total Revenue | ₹113,277.00 |
| Total Products | 6 |
| Total Customers | 8 |

## Connection Requirements

The original report uses a live connection to the Microsoft Fabric semantic model. Access to live data requires appropriate authentication and permissions.

The live connection report is not a standalone offline dataset. To reproduce the solution independently, deploy the Lakehouse, execute the transformation notebooks, and configure the semantic model in your own Fabric workspace.
