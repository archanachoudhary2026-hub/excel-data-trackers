# Sales Dashboard - Excel

A sales performance dashboard built with formulas. Log orders in the data sheet and the dashboard reports revenue, orders, average order value and progress against an editable annual target. All names and figures are made up for practice only.

## What it tracks

- **Sales Data sheet** - 260 sample orders with date, region, category, product, quantity, unit price and sales rep. The month and revenue columns are formulas.
- **Calc sheet** - monthly revenue with SUMIFS, a top-5 ranking with LARGE and INDEX-MATCH, and the annual target cell (yellow = editable input).
- **Dashboard** - total revenue, total orders, average order value and target achievement, plus charts for the monthly trend and revenue by region.

## Sample data at a glance

- Total revenue 2,15,50,680 (INR) across 260 orders
- Average order value about 82,887
- Target achievement 86.2% against a 2,50,00,000 annual target

## How to use it

1. Add orders as new rows in the Sales Data table.
2. Change the annual target in the yellow cell on the Calc sheet if needed.
3. The dashboard and charts update on their own - this workbook uses no PivotTables, everything is formula-driven.

Techniques used: SUMIFS, COUNTA, SUM, TEXT, DATE with EDATE, MAX, LARGE with INDEX-MATCH. The workbook lists them on its Formulas Used sheet.
