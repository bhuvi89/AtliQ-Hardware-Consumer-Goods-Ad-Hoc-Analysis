# AtliQ-Hardware-Consumer-Goods-Ad-Hoc-Analysis

## Project Overview
This project aims to analyze the sales performance of Atliq Hardware across different channels and provide insights into market trends, customer behavior, and product performance. The analysis focuses on fiscal year 2020,2021 and includes various ad-hoc requests to answer specific business questions.
## Objectives
- To identify the markets in which the customer "Atliq Exclusive" operates in the APAC region.
- To calculate the percentage increase in unique products in 2021 compared to 2020.
- To provide a report of unique product counts for each segment, sorted in descending order.
- To determine which segment had the most increase in unique products in 2021 vs. 2020.
- To identify the products with the highest and lowest manufacturing costs.
- To generate a report which contains the top 5 customers who received an average high pre_invoice_discount_pct for the fiscal year 2021 and in the Indian market.
- To generate a report of the gross sales amount for "Atliq Exclusive" for each month.
- To determine the quarter of 2020 with the maximum total sold quantity.
- To find the channel that contributed the most gross sales in fiscal year 2021 and its percentage contribution.
- To identify the top 3 products in each division by total sold quantity in fiscal year 2021.

## Datasets
- **dim_customer**: Contains customer-related data.
- **dim_product**: Contains product-related data.
- **fact_gross_price**: Contains gross price information for each product.
- **fact_manufacturing_cost**: Contains the cost incurred in the production of each product.
- **fact_pre_invoice_deductions**: Contains pre-invoice deductions information for each product.
- **fact_sales_monthly**: Contains monthly sales data for each product.
  
## Key Insights
1. **Market Presence**: Atliq Exclusive operates in key APAC markets including Australia, Bangladesh, India, Japan, South Korea, Philippines, New Zealand, and Indonesia.
2. **Product Growth**: There was a 36.32% increase in unique products in 2021 compared to 2020, with the accessories segment seeing the largest increase.
3. **Sales Performance**: In fiscal year 2021, the retailer channel contributed the highest gross sales, while the distributor channel had the lowest.
4. **Seasonal Trends**: The highest total sold quantity was in Quarter 1 of 2020 (September, October, November), with a significant drop in Quarter 3 (March, April, May) likely due to the COVID-19 pandemic.

## Queries and Analysis
- SQL queries were used to extract and analyze data from the provided datasets.
- Various SQL concepts such as joins, CTEs, group by, aggregate functions, and window functions were employed.
- Detailed analysis was conducted for each ad-hoc request to derive actionable insights.

## Conclusion
The analysis provides valuable insights into Atliq Hardware's sales performance, customer behavior, and market trends. These findings can help inform strategic decisions to optimize sales and enhance market presence.
