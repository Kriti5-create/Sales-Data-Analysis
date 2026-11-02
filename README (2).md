# ApexLark Data Analytics Internship — Day 01: Excel Sales Analysis

Exploration, validation, analysis and visualization of the **Sample Superstore** retail dataset (9,994 rows × 19 columns, 2014–2017) in Microsoft Excel.

## Files
| File | Description |
|------|-------------|
| `ApexLark_Day01_Sales_Analysis.xlsx` | Excel workbook with all tasks |
| `ApexLark_Day01_Insights_Report.pdf` | One-page insights report |
| `README.md` | Project overview |

## Workbook structure
- **Data Profile:** row and column counts, column data types, blank and duplicate checks, and a data validation summary
- **Summary:** KPIs built with SUM, AVERAGE, MAX, MIN, COUNT, COUNTIF and unique counts
- **Data:** the cleaned dataset as an Excel Table (`SalesData`), with conditional formatting that flags blanks, invalid values, losses, duplicates and mixed date formats
- **Analysis:** SUMIFS tables by category, city, region, month and product, with INDEX/MATCH answers to the business questions
- **Charts:** Sales by Category (column), Monthly Sales Trend (line), Sales by City (bar) and Category Distribution (pie)

## Key results
- Total Sales **$2.30M**, Total Profit **$286K** (12.5% margin), 5,009 orders, 793 customers
- Top category: **Technology** ($836K)
- Top city: **New York City** ($256K)
- Highest-value order: **SM-20320**, order CA-2014-145317 ($23,661)
- Best month: **November 2017** ($118K)
- Most units sold: **Staples** (215)

## Data quality notes
No missing values. 1 duplicate record was flagged. Dates arrived in mixed formats and were standardized. 16 product names had trailing spaces, which were trimmed. 1,871 line items were sold at a loss.

## Tools
Microsoft Excel (Tables, formulas, Conditional Formatting, Charts)
