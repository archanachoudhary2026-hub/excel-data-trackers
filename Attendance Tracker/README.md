# Team Attendance Tracker - Excel

An Excel attendance tracker I built as a practice project, using fictional demo data for a 15-member team in October 2026.

## About this project

I made this tracker to practise Excel reporting for a real operations need: marking daily attendance, watching who needs attention, and working out monthly payout for contractual staff. All names and figures are made up for practice only. No real employees or payroll.

![Dashboard preview](Attendance%20Dashboard%20-%20Oct%202026.png)

## What's in the workbook

- **Attendance** - the daily grid. Each day is marked P (Present), A (Absent), WFH, L (Leave) or WO (Weekly Off) using dropdowns, with automatic colour coding. Saturdays and Sundays are days off and highlighted.
- **Dashboard** - key metrics and charts that update on their own: team size, average attendance, absences, WFH days, perfect attendance, members below 85%, total payout and average payout per member.
- **Calc** - payout settings in editable yellow cells: hourly rate, paid hours per day, and whether leave or days off are paid.
- **Formulas Used** - a sheet listing every formula and what it does.

## Business questions this tracker answers

- What is the team's overall attendance this month?
- Who has perfect attendance, and who is falling below 85% and needs attention?
- How many days were worked from home versus in office?
- What is the month's total payout, and the average per member?
- Which team (Support, Operations, Quality) is ahead on attendance?

## What the demo data shows

- Average team attendance is 91.2% across 15 members, with 16 absence days and 36 work-from-home days in the month.
- Two members have perfect attendance: Vikram Rao and Ananya Bose (100%).
- Two members fall below 85% and are flagged for attention: Arjun Mehta and Kavya Reddy (both 81.8%).
- Quality leads the teams at 93.2% average attendance, ahead of Operations (92.7%) and Support (88.6%).
- Total payout for the month is $35,217, an average of $2,348 per member, at demo rates of $13/hour and a 9-hour paid day.
- Work-from-home varies a lot by person, from none to 7 days, without hurting attendance: the two 100% members include the heaviest WFH user.

## How the numbers are defined

- Attendance % = (Present + WFH) / (Present + Absent + WFH + Leave). Days off are not counted against anyone.
- Paid days = Present + WFH. Leave and days off are unpaid for contractual work, but this can be changed on the Calc sheet.
- Payout = paid days x paid hours per day x hourly rate. Rates are demo values, not linked to any employer.

## Using the tracker

Mark each day in the grid with the dropdown. The colours, totals, percentages, charts and payout all update on their own. It fits up to 49 members by copying the total formulas down.

## What I practised

COUNTIF, AVERAGE, AVERAGEIF, SUM, IF with division, conditional formatting, data validation dropdowns, editable settings cells, and charts that refresh from formulas.
