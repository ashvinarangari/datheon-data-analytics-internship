# Task 2: Executive Sales and Profit Dashboard

Power BI report created for the Datheon Data Analytics internship using the Superstore sales dataset.

## Objective
Help executives explore sales, profit, order volume, regional performance, and product profitability using an interactive two-page report.

## Tools
- Power BI Desktop
- Power Query
- DAX

## Report Pages

### 1. Sales and Profit
- KPI cards: Total Sales, Total Profit, Total Orders, and Profit Margin %
- Monthly sales line chart
- Regional sales bar chart
- Category and sub-category sales treemap
- Year, Region, Segment, and State slicers

### 2. Product Profitability
- Matrix showing sub-category sales, profit, and profit margin
- Regional profit margin bar chart
- Scatter chart comparing average discount and profit margin by sub-category, with bubble size representing sales
- Year, Region, and Segment slicers

## Model Organisation
The model diagram contains Facts_orders, Dim_customer, Dim_product, Dim_Date, and a Measure table.

## Measures Referenced by the Report
- Total Sales
- Total Profit
- Total Orders
- Profit Margin %
- Avg Discount %

## How to Use
1. Download the PBIX file and open it in Power BI Desktop.
2. Explore both report pages.
3. Use the slicers to filter the report and compare results.
4. Clear selections to return to the full dataset.
5. If refreshing data, update the source path in Power Query to your local dataset location.

## PDF Report
Export the final report from Power BI Desktop using File > Export > Export to PDF. Add the exported PDF to this project folder. The PDF is a static snapshot; interactive filtering is available in the PBIX report.

## Suggested Project Files
- Executive_Sales_Profit_Dashboard.pbix
- Executive_Sales_Profit_Dashboard.pdf 
- README_Task2.md 

## Interpretation Notes
- Compare sales with profit and margin rather than judging performance by revenue alone.
- Discount and profitability comparisons show association, not proof of causation.
- Results change with slicer selections.

## Author
Ashvina Rangari

[LinkedIn](https://www.linkedin.com/in/ashvina-rangari-b7822818b/)
