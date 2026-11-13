# Swiggy Sales Analysis

An Excel-based sales analysis project exploring Swiggy food listings and sales patterns across Indian cities from January to August 2025. The workbook combines a raw dataset, analysis summaries, and an interactive dashboard.

## Project Overview

The objective of this project is to understand how recorded sales vary by time, geography, restaurant, and food type, and to summarize the results through an Excel dashboard.

## Workbook Structure

| Sheet | Description |
|---|---|
| `Swiggy Data` | Raw dataset containing 197,430 records and 14 fields |
| `Analyze` | KPI calculations and summary tables used for analysis |
| `Dashboard` | Dashboard view for exploring the summarized results |

## Dataset Details

- **Period:** 1 January 2025 to 31 August 2025
- **Records:** 197,430
- **States represented:** 28
- **Cities represented:** 28
- **Restaurants represented:** 993
- **Food types:** Veg and Non-Veg

### Main Fields

State, City, Order Date, Month, Day, Quarter, Restaurant Name, Location, Category, Dish Name, Food Type, Price (INR), Rating, and Rating Count.

## Key Metrics

| Metric | Value |
|---|---:|
| Total Sales (sum of Price) | ₹5.30 Cr |
| Total Records / Orders shown in workbook | 197,430 |
| Average Order Value shown in workbook | ₹268.51 |
| Average Rating | 4.34 |
| Total Rating Count | 5,591,574 |

## Analysis Covered

- Overall sales performance and key KPIs
- Monthly sales trends
- Sales by day of the week
- Veg vs Non-Veg sales contribution
- Restaurant-wise sales comparison
- State-wise and city-wise sales distribution
- Quarterly sales, average rating, and record counts

## Tools Used

- Microsoft Excel
- Pivot Tables and Pivot Charts
- Excel formulas
- Dashboard visualizations

## Important Data Note

The workbook's sales metric is calculated by summing the `Price (INR)` field, and its order count is based on the 197,430 dataset records. The source columns do not include a unique order ID, item quantity, or customer ID. Therefore, these figures should be interpreted as workbook-level recorded sales and record counts, not independently verified completed-order revenue or unique customer transactions.

## How to Explore

1. Download or clone this repository.
2. Open the Excel workbook in Microsoft Excel.
3. Start with the `Dashboard` sheet for a visual summary.
4. Refer to the `Analyze` sheet to inspect the supporting KPIs and breakdowns.
5. Use the `Swiggy Data` sheet to review the underlying records.

---

*This project was created for hands-on practice in Excel-based data analysis, business reporting, and dashboard development.*
