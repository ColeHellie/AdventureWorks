# Adventure Works
  

## Project Background
  Adventure Works Cycles, a global bicycle manufacturer that sells bikes, components, and accessories, recently discovered that the company was losing money on one of its popular models, the LL Road Frame–Black 60. Even though this model has a strong reputation, sales have declined, and the reason behind the drop is not immediately clear. Leadership requested an investigation into potential causes affecting the product’s performance.

  There are many variables that can contribute to a decrease in sales, but the initial research focused on specific areas such as production and sales data, including total sales, list price, order dates, and unit price. Historical data from the AdventureWorks2017 database was analyzed by creating SQL queries, temporary tables, and stored procedures. This approach made it possible to break down the problem and gain a better understanding of each variable that could be influencing the decline in sales for the LL Road Frame–Black 60.

## Data Structure
<p align="center">
  <img src="ERD.png" width="700">
</p>

  The ERD above shows the core tables used in this analysis and how product, pricing history, and sales data are connected through shared keys like ProductID and SalesOrderID. These tables served as the foundation for creating temporary tables that helped compare product performance and analyze pricing and discount history.

- Sales Order Header: Provided order dates needed to analyze product performance within specific time periods.
- Sales Order Detail: Captured line‑item data such as ProductID, quantity, and unit price for each sale.
- Product List Price History: Tracked historical list price changes to evaluate pricing and discount trends.
- Product: Stored core product attributes used to link sales and pricing data back to each item.

## Executive Summary

## Insights Deep Dive

## Recommendations
