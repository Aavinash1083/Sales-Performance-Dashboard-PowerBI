# Sales Performance Dashboard Using Power BI

## Project Overview

This project presents an interactive Sales Performance Dashboard built using Microsoft Power BI to analyze sales, profit, order volume, and profitability across product categories and regions.

The dashboard helps users explore business performance through KPI cards, sales trend analysis, and interactive filters.

## Dashboard Preview

![Sales Performance Dashboard](dashboard.png)

## Business Objectives

- Monitor overall sales and profit performance.
- Analyze monthly sales trends.
- Compare sales across product categories.
- Evaluate profit performance across regions.
- Filter results by year, category, and region.

## Key Performance Indicators (KPIs)

| KPI | Description |
|---|---|
| Total Sales | Total sales revenue |
| Total Profit | Total profit generated |
| Total Orders | Distinct number of orders |
| Profit Margin | Profit as a percentage of sales |

## Dashboard Visualizations

1. **Monthly Sales Trend** — Tracks sales performance over time.
2. **Sales by Category** — Compares Furniture, Office Supplies, and Technology.
3. **Profit by Region** — Compares profit across Central, East, South, and West.

## Interactive Filters

- **Year:** Filter results by year.
- **Category:** Select a product category.
- **Region:** Focus on a specific sales region.

## Tools and Technologies

- Microsoft Power BI Desktop
- Power Query for data cleaning and transformation
- DAX for measures and calculations
- Data modeling and date-table relationships
- Superstore dataset

## Key DAX Measures

```dax
Total Sales = SUM(superstore[Sales])

Total Profit = SUM(superstore[Profit])

Total Orders = DISTINCTCOUNT(superstore[Order ID])

Total Quantity = SUM(superstore[Quantity])

Profit Margin % =
DIVIDE([Total Profit], [Total Sales], 0)
```

## Key Insights

- Technology has the highest sales among the three product categories in the current dashboard.
- The West region shows the highest profit among the four regions.
- The dashboard reports a total profit margin of approximately 12.47%.
- Year, category, and region filters allow users to explore performance in more detail.

## Project Files

- `Sales_Performance_Dashboard.pbix` — Power BI project file, if included.
- `Sales_Performance_Dashboard.pdf` — Static PDF report.
- `dashboard.png` — Dashboard preview image.

## How to Use

1. Download the `.pbix` file from this repository.
2. Open it using Microsoft Power BI Desktop.
3. Interact with the year, category, and region slicers.
4. Explore the KPI cards and visualizations.

## Author

**Aavinash M.**

GitHub: [Aavinash1083](https://github.com/Aavinash1083)
