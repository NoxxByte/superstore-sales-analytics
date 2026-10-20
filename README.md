# Superstore Sales Analytics Dashboard | Power BI

An interactive sales and profitability report built in Microsoft Power BI, based on the Sample Superstore project by the original repository author. The report has been opened and visually customized; further validation and enhancements are ongoing.

## Project overview
The dashboard is designed to explore sales, profit, quantity, discounts, regional performance, product subcategories, and trends over time.

## Report features visible in the supplied report
- KPI cards for profit, sales, quantity, discount, and order count
- Clustered column chart comparing sales and profit by region
- Donut chart showing profit contribution by region
- Gauge visual for sales against a benchmark
- Sales and profit trend visuals
- Top subcategories by profit
- Category, region, and subcategory slicers
- Additional report pages labelled `Tooltip Page` and `Column Chart`

## Files
- `superstore-sales-analytics.pbix` — Power BI report file
- `data/Dataset of the report.csv` — source dataset from the original project
- `Superstore_Sales_Analytics_Project_Report.docx` — project documentation

## Tools
- Microsoft Power BI Desktop
- CSV data
- Power BI visualizations and slicers

## Data model and DAX
The visible Data pane contains `Orders`, `People`, and `Returns` tables. Exact relationship settings and the original DAX expressions have not yet been independently documented. Do not assume that sample formulas in external notes are the author's original measures. Inspect Model view and the measures in Power BI Desktop before documenting exact relationships or DAX.

## Customization completed so far
- Saved a working copy under a new project name.
- Changed the report canvas to a light blue-grey background.
- Changed the Sales KPI callout value to a dark navy colour.
- Reviewed slicer selections and the main report visuals.

These are early visual edits; the dashboard remains based on the original project and should be described as a customized/adapted project, not as created entirely from scratch.

## Suggested next improvements
- Validate all KPI calculations and the sales gauge target.
- Review model relationships and measures.
- Standardize visual colours, typography, spacing, and titles.
- Add a profit-margin measure after verifying the underlying data.
- Capture clear screenshots of the final report.
- Write data-backed findings after checking totals with slicers cleared.

## Attribution
This project is adapted from the public GitHub project **Power BI Sales Report – Sample Superstore Analysis**. The original README describes KPIs, regional analysis, sales/profit trends, slicers, tooltip pages, and RLS.

Original repository: https://github.com/Chaandu1997/Power-BI-Sales-Report-Sample-Superstore-Analysis

Please review the original repository's current licence and terms before redistributing its PBIX or dataset. Credit the original author and clearly identify your own modifications. If the licence does not permit redistribution of the source dataset or report, remove those files and link to the original repository instead.
