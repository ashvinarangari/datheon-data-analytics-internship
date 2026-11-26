# Datheon Data Analytics Internship

# Task 1: Superstore Sales Exploratory Data Analysis

A Python EDA project completed for the Datheon Data Analytics internship.
This project explores sales, profitability, customer segments, regional performance, and discount patterns using Python, Pandas, Matplotlib, and Seaborn.

## Project Objective
Explore customer purchase volume, monthly sales trends, category revenue, regional performance, and the relationship between discounts and profitability.

## Tools Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook
- OpenPyXL for Excel export

## Dataset

The Superstore sales dataset was obtained from the Datheon task resources.

The input file contains 10,800 rows and 21 columns, including order dates, customer segments, regions, product categories,sales, quantity, discounts, and profit.

## Data Cleaning

- Inspected data types, missing values, and duplicate records.
- Removed 504 exact duplicate rows.
- Removed 302 remaining records missing essential analysis fields.
- Retained 9,994 records for analysis.
- Retained 11 records with missing postal codes because those
  values are not required for the sales analyses.
- Converted Order Date and Ship Date to datetime.
- Retained negative profits to analyse loss-making transactions.
- Exported the cleaned dataset to Excel.

## Analysis Performed

- Sales and profit by product category
- Monthly sales trends using Year-Month
- Regional sales
- Customer segment sales, profit, units, and unique orders
- Quantity sold by category
- Discount-versus-profit analysis
- Profit distribution
- Sales-versus-profit analysis
- Shipping-mode sales
- Top 10 sub-categories by sales
- Correlation analysis

## Five Key Business Findings

1. **Consumer customers lead sales.**
   The Consumer segment generated sales of 1,161,401.34, profit of 134,119.21, and purchases totalling 19,521 units.
   This makes it an important segment for retention initiatives.

2. **Corporate customers form the second-largest sales segment.**
   Corporate sales totalled 706,146.37, with profit of 91,979.13 across 1,514 unique orders. Targeted account support could help maintain this business.

3. **Office Supplies leads purchase volume.**
   Office Supplies sold 22,906 units, compared with 8,028 for Furniture and 6,939 for Technology. Inventory planning should account for this difference in unit demand.

4. **Undiscounted transactions have stronger aggregate margins.**
   Transactions with no discount generated profit of 320,987.60 and a profit margin of 29.51%. Transactions discounted by 20% had an aggregate margin of 11.82%.

5. **Every observed discount level of 30% or more has a negative
   aggregate profit.**
   For example, the 30% discount group recorded a loss of 10,369.28. These discount groups should be reviewed by category and product before changing pricing policies.

## Recommendations

- Prioritise service and retention for Consumer and Corporate customers.
- Align Office Supplies inventory with its higher purchase volume.
- Review products sold at high discounts and assess their margins.
- Use monthly sales patterns to guide inventory and promotion planning.

## Limitations

These results describe historical transactions. The relationship between discounts and profit does not prove that discounts alone caused losses; product and customer differences may also contribute.

## How to Run

1. Download or clone this repository.
2. Obtain superstore_sales.csv from the task resources.
3. Place it in the dataset folder beside the notebook.
4. Install the required packages:

   pip install pandas numpy matplotlib seaborn openpyxl notebook

5. Open Task1_EDA_Analysis.ipynb in Jupyter Notebook.
6. Run the cells from top to bottom.

## Author

Ashvina Rangari

LinkedIn: https://www.linkedin.com/in/ashvina-rangari-b7822818b/
