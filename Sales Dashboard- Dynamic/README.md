# Sales Dashboard (Dynamic) - Excel

A fully dynamic sales dashboard driven by PivotTables and slicers. Filter by product, payment method, salesperson or location and every chart and card updates together. All customers, products and sales are fictional demo data for practice only.

## What it tracks

- **Sales Data sheet** - 60 sample orders from 19 customers, September 2026, stored as an Excel Table.
- **Report sheet** - 13 PivotTables that summarise the data and feed the dashboard.
- **Dashboard** - KPI cards, six top-performer cards, 8 charts and 4 slicers.

## How the numbers are defined

- Total Price = Quantity x Unit Price, before discount.
- Net Sales = Total Price after Discount %, before tax.
- Tax Amount = 5% of Total Price (a made-up practice rate, not a real tax rule).
- Total Bill = Net Sales + Tax Amount.
- Total Profit = Net Sales x an assumed profit margin, not actual costs.

## Sample data at a glance

- Net sales 2,11,641; total bill 2,22,525
- Total profit 58,328 (about 27.6%)
- Top salesperson SP005, top location Chennai, top product Product D

## How to use it

1. Use the 4 slicers at the top of the dashboard to filter by product, payment method, salesperson and location.
2. All charts, KPI cards and top-performer cards update together. PivotTables refresh when the file opens.

Techniques used: PivotTables, slicers, GETPIVOTDATA, COUNTA, INDEX-MATCH, MAX, TEXT, IFERROR, Excel Tables, bar and pie charts, and text boxes linked to cells.
