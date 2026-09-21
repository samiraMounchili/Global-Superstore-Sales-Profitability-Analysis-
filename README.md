 # Global-Superstore-Sales-Profitability-Analysis-
Sales and profitability analysis of 51,290 Global Superstore transactions using Excel, MySQL and Power BI, including KPI analysis, customer profitability, discount impact and interactive dashboards. 
# Global Superstore Sales & Profitability Analysis

## Project Overview

This project analyses 51,290 Global Superstore transaction records using Excel, MySQL and Power BI.

The objective was to evaluate sales performance, profitability, customer behaviour, regional performance and the impact of discounting, and to identify areas where stronger commercial decisions could improve profitability.

## Tools Used

- Microsoft Excel
- MySQL
- Power BI
- Power Query
- DAX

## Business Questions

- How are sales and profit changing over time?
- Which regions generate the highest and lowest profit?
- Which categories and sub-categories drive profitability?
- How do discount levels affect profit margins?
- Which customer segments contribute the most sales?
- Who are the highest-value customers?
- Which customers generate sales but remain unprofitable?

## Key KPIs

- Total Sales: £12.64M
- Total Profit: £1.47M
- Profit Margin: 11.61%
- Total Orders: 25,035
- Total Customers: 1,590
- Average Order Value: £504.99

## Key Findings

- Sales increased consistently between 2011 and 2014.
- Sales growth reached approximately 27.2% in 2013.
- Discounts above 20% were associated with negative overall profitability.
- The 31%+ discount band produced approximately -51.27% profit margin.
- Tables were the main loss-making sub-category, generating approximately -£64K in profit.
- Consumer customers generated approximately 51.5% of total sales.
- Some high-revenue customers were identified as loss-making, showing that sales value alone does not indicate customer profitability.

## SQL Analysis
[View SQL Analysis](global_superstore_sql_analysis.sql)

MySQL was used to analyse the dataset and validate key business metrics.

Techniques included:

- SELECT
- WHERE
- GROUP BY
- ORDER BY
- HAVING
- CASE WHEN
- Aggregate functions
- CTEs
- LAG
- RANK
- Window functions
- Year-on-year growth calculations
- Customer profitability analysis
- Discount segmentation

## Power BI Dashboard

The Power BI report was divided into two pages.

### Executive Overview

Includes:

- KPI cards
- Sales and Profit Trend by Year
- Region Profitability
- Profit Margin by Discount Band
- Sales by Customer Segment
- Interactive Year, Region and Category slicers

<img width="661" height="370" alt="Executive overview" src="https://github.com/user-attachments/assets/445ef915-56ba-4c24-82fa-9a95a275bc71" />



### Detailed Analysis
[global superstore Sql analyis.sql](https://github.com/user-attachments/files/32474603/global.superstore.Sql.analyis.sql)
<img width="522" height="369" alt="Detailed Analysis" src="https://github.com/user-attachments/assets/8599308b-618c-41f9-8aac-5249b20aff59" />


Includes:

- Top 10 Customers by Sales
- Category / Sub-Category Profitability
- Loss-Making Customers
- Sub-Category filtering

## Business Recommendations

- Review discounting above 20%, as these transactions are associated with negative overall profit margins.
- Investigate the Tables sub-category to understand whether pricing, discounting, shipping costs or product mix are driving losses.
- Evaluate customers using profit and margin alongside sales revenue.
- Continue monitoring regional and product profitability rather than focusing only on sales growth.

## Skills Demonstrated

- Data cleaning
- Exploratory data analysis
- KPI development
- SQL querying
- Profitability analysis
- Customer analysis
- Year-on-year analysis
- Power Query
- DAX
- Data visualisation
- Interactive dashboard development
- Business insight communication
