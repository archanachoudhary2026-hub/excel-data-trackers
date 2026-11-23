# Inventory Stock Tracker - Excel

A stock register with a live dashboard. It tracks each product from opening stock through purchases and sales, flags what needs reordering, and values the stock on hand. All products and figures are made up for practice only.

## What it tracks

- **Stock sheet** - 32 sample SKUs with unit cost, sale price, opening stock, purchased, sold, reorder level and status. In-stock quantity, stock value and status (OK / Low Stock / Reorder Now) are all formula-driven.
- **Calc sheet** - category-wise totals for stock value, units and reorder counts, plus a top-5 ranking with LARGE and INDEX-MATCH.
- **Dashboard** - total SKUs, stock value, units in stock, reorder-now count, low-stock count and potential sale value, with charts.

## Sample data at a glance

- 32 SKUs, 2,792 units in stock
- Stock value 22,30,741 (INR); potential sale value 31,35,940
- 8 items at or below reorder level, 4 more running low

## How to use it

1. Add products as new rows in the Stock table; set the reorder level for each.
2. Enter purchases and sales as they happen.
3. The status column and dashboard update on their own.

Techniques used: nested IF for status, SUMIFS and COUNTIFS for category totals, SUMPRODUCT for sale value, conditional formatting, LARGE with INDEX-MATCH for top 5. The workbook lists them on its Formulas Used sheet.
