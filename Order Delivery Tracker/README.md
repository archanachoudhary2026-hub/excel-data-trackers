# Order Delivery Tracker - Excel

An order delivery tracker with a dashboard. It follows each order from order date to promised date to actual delivery, flags late and at-risk orders, and reports the on-time rate. All customers, cities and figures are made up for practice only.

## What it tracks

- **Orders sheet** - 120 sample orders with city, order date, promised date, delivered date, status and priority. Status and priority are dropdowns. Formulas work out days late and whether each delivery was on time.
- **Calc sheet** - status counts and city-wise stats with COUNTIF and COUNTIFS.
- **Dashboard** - total orders, delivered, in transit/open, delayed, on-time delivery %, orders past promise and average days late, with charts.

## Sample data at a glance

- 120 orders: 72 delivered, 24 in transit or open, 21 delayed
- On-time delivery: 83.3% of completed deliveries
- 21 open orders are already past their promised date
- Average delay of late orders: about 4.2 days

## How to use it

1. Add orders as new rows in the Orders table; pick status and priority from the dropdowns.
2. Fill in the delivered date when an order arrives - the late and on-time columns calculate themselves.
3. The dashboard updates on its own.

Techniques used: COUNTIF, COUNTIFS, IF, MAX, TODAY for the past-promise check, AVERAGEIF, data validation and conditional formatting. The workbook lists them on its Formulas Used sheet.
