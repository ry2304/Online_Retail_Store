# Online Retail Store Analysis

This project contains a full data analysis process for a UK-based e-commerce company using Python.  
The work focuses on data cleaning, exploration, visualization, insights, and actionable recommendations.  

---

## Project Background

**Online Retail** is a UK-based e-commerce company specializing in wholesale giftware distribution.  
They have been operating mainly across Europe since 2009, serving both businesses and direct consumers.  
Key business metrics include customer acquisition, order volumes, revenue trends, and product return rates.  

---

## Insights and Recommendations are Provided on the Following Key Areas

- Sales Performance Analysis
- Customer Segmentation
- Geographic Market Analysis
- Product Return Trends

---

> The Jupyter Notebook containing the data cleaning and analysis process is available [here](Online Retail Store Analysis.ipynb).  
> The dataset used for this project is available [here](Online Retail.xlsx).   
---

## Data Structure and Initial Checks

The company's database for this project consists of a single table:

- **Transactions Table**: 541,909 records across 8 fields, including InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, and Country.

Initial steps taken:

- Checked for missing values
- Removed cancelled transactions
- Removed duplicates
- Handled negative or zero quantities

---

## Executive Summary

### Overview of Findings

- The United Kingdom accounted for about 80% of total sales volume.
- A small percentage of customers generated a large percentage of the revenue.
- Product returns were heavily concentrated in a few categories.
- Sales peaked during the months of October to December, aligning with holiday seasons.

These findings can guide marketing strategies, customer loyalty programs, and operational improvements.

---

## Insights Deep Dive

### Sales Performance Analysis

- Total revenue peaked in November, likely due to holiday shopping.
- The top 5 best-selling products accounted for over 20% of total sales.
- Large quantity purchases were associated with wholesale buyers.
- There was a seasonal dip in sales during the summer months.

### Customer Segmentation

- Most customers made only one purchase during the year.
- A loyal segment of repeat buyers contributed significantly to the overall revenue.
- High-value customers were mainly based in the UK, Netherlands, and Germany.
- Lower-tier customers showed sensitivity to product prices.

### Geographic Market Analysis

- The UK had the highest transaction count but lower average order values compared to other countries.
- The Netherlands and Ireland had higher average transaction values despite lower sales volume.
- Germany, France, and Norway were identified as potential markets for expansion.
- Some countries had very low sales and may not be cost-effective to target.

### Product Return Trends

- About 16% of total transaction volume involved returns.
- Certain product types showed high return rates.
- Most returns were processed within 7 days after purchase.
- Negative quantities often represented returns or order corrections.

---

## Recommendations

Based on the findings above, the following actions are recommended:

- Develop a loyalty program targeting high-value and repeat customers.
- Focus inventory and marketing efforts on the top-selling products.
- Expand into international markets with high-value customers, such as Germany and the Netherlands.
- Implement stricter return policies or quality checks for products with high return rates.
- Plan marketing campaigns around Q4 seasonal trends to maximize revenue.
