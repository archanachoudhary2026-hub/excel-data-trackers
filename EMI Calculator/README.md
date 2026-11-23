# EMI Calculator - Excel

A loan EMI calculator with a full payment schedule. Enter the loan details, pick how often you want to pay, and it works out the installment, the total interest and a month-by-month (or week-by-week) breakup of every payment.

## What it does

- **Inputs** - loan amount, downpayment, yearly interest rate, tenure in years, and payment frequency from a dropdown (weekly, monthly, quarterly, half-yearly and more, looked up with VLOOKUP).
- **Outputs** - the installment amount (PMT), total repayment and total interest.
- **Payment Schedule sheet** - a full amortization schedule that splits every installment into interest (IPMT) and principal (PPMT), with running dates handled by EDATE. It stretches or shrinks to match the frequency you pick.
- **What-If Data Table** - compares EMIs across loan amounts and tenures side by side.

## Sample numbers

A 5,00,000 loan at 10% for 2 years, paid monthly: EMI of about 23,072, total repayment about 5,53,739, so total interest of about 53,739.

## How to use it

1. Fill in the input cells on the EMI Calculator sheet.
2. Choose the payment frequency from the dropdown.
3. Read the EMI and totals, and open Payment Schedule for the full breakup.

Techniques used: VLOOKUP, PMT, IPMT, PPMT, IF, ROUND, EDATE, absolute references, a dropdown for frequency, and a What-If Data Table. The workbook lists all 7 functions on its Functions Used sheet.
