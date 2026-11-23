# Clients CRM - Excel

A client and deals tracker built in Excel. It keeps a pipeline of sales deals, a customer database and a company list, and rolls everything up into a CRM dashboard. All names, companies and figures are made up for practice only. No real clients.

## What it tracks

- **Clients sheet** - the deals pipeline. 68 sample deals with stage (New Lead, Contacted, Proposal Sent, Negotiation, Won, Lost), deal value and follow-up dates. A formula assigns a win probability to each stage, and another flags follow-ups as overdue, due today or upcoming.
- **Customer Database** - 60 sample contacts with their details.
- **Companies** - 60 sample companies. Formulas count the deals per company and sum the value of won deals automatically.
- **Summary sheet** - the CRM dashboard: total deals, open pipeline value, won deal value, and a stage-wise breakdown with a chart.

## Sample data at a glance

- 68 deals worth 14,09,500 in the open pipeline (INR)
- 15 deals won, worth 3,93,000
- Stage mix runs from 11 new leads to 4 lost deals

## How to use it

1. Add or edit deals in the Clients sheet. Pick the stage from the dropdown.
2. Keep customer and company details in their own sheets.
3. The Summary dashboard updates on its own - no refresh needed.

Techniques used: COUNTIF, SUMIFS, nested IF, date checks for follow-ups, data validation dropdowns, a hidden status list, and a dashboard chart.
