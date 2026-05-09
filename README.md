# Company Financial Analysis Dashboard

## Project Overview
This project analyzes a company's financial performance using Power BI.  
The dashboard focuses on sales, profit, profit margin, product performance, market behavior, and customer segments across different countries.

The goal is to transform raw financial data into actionable business insights through data cleaning, modeling, DAX measures, and interactive visualizations.

---

## Tools Used
- Power BI
- Power Query
- DAX
- Excel / CSV Dataset

---

## 📌 Dataset Information

Source: Sample financial dataset
Records: 700 rows × 16 columns

Fields include:
- Segment, Country, Product
- Discount Band, Units Sold
- Manufacturing Price, Sale Price
- Gross Sales, Discounts, Net Sales
- COGS, Profit
- Date, Month, Year

---

## Data Modeling
Created a star schema model including:

### Dimension Tables
- DimProduct
- DimCountry
- DimSegment
- DimDiscount
- DimDate

### Fact Table
- FactSales

---

## Key DAX Measures
Some measures used in the project:

- Total Sales
- Total Profit
- Profit Margin
- Total Units Sold
- YoY Growth
- Sales Last Month
- Highlight MaxMin Sales
- 
---

# Key Business Insights

## Product Insights
- Paseo generated the highest revenue and profit but did not have the highest profit margin.
- VTT showed strong profit margin performance across multiple countries, making it a high-potential product.

## Segment Insights
- Government segment produced the highest sales but relatively low profit margin.
- Channel Partners had the highest profit margin (~73%).
- Enterprise segment showed negative profitability despite relatively high sales.

## Country Insights
- USA generated the highest revenue but had the lowest profit margin.
- Germany showed stronger performance under low discount conditions, suggesting lower price sensitivity.
- Customers in USA and Canada appeared more price-sensitive due to higher sales concentration in heavily discounted products.

---

# Dashboard Preview

## Overview Dashboard
![Overview](screenshots/overview.png)

## Product Analysis
![Product](screenshots/product-insight.png)

## Segment Analysis
![Segment](screenshots/segment-insight.png)

## Country Analysis
![Country](screenshots/country-insight.png)

---

## Files Included
- Power BI dashboard (.pbix)
- Presentation slides (.pdf)
- Dataset (.csv)
- Dashboard screenshots

---

## Author
Lê Xuân Việt
