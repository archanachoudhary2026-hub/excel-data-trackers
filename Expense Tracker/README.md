# Expense Tracker - Excel

A monthly expense tracker with a dashboard. Log each expense once, and the dashboard shows where the money went, which categories are over budget, and how this month is going. All entries and figures are made up for practice only.

## What it tracks

- **Expenses sheet** - 150 sample entries with date, category, description, amount (INR) and payment mode. Category and payment mode are dropdowns, and the month fills itself in with a TEXT formula.
- **Calc sheet** - monthly totals worked out with SUMIFS, budget vs actual, and the variance.
- **Dashboard** - key cards and charts: total spend, month-to-date spend, entries logged, over-budget areas, top category and average per entry.

## Sample data at a glance

- Total spend of 11,10,164 across 150 entries
- November month-to-date: 2,58,700
- Salaries is the biggest category; average expense about 7,401
- 2 categories are over budget

## How to use it

1. Add each expense as a new row in the Expenses table.
2. The darker column headers are formulas - leave them alone.
3. The dashboard and charts update on their own.

Techniques used: SUMIFS, COUNTIF, COUNTA, TEXT, AVERAGE, MAX with INDEX-MATCH, data validation, and data bars for the % of budget column. The workbook lists them on its Formulas Used sheet.
