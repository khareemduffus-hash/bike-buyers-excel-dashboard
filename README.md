# Bike Buyers Sales Dashboard (Excel)

An interactive Excel dashboard analyzing which customer characteristics are associated with buying a bike.

<img width="1270" height="756" alt="Dashboard" src="https://github.com/user-attachments/assets/b6335f5f-4b85-4ca0-aba9-2997ec4c7a04" />


## Objective
Identify which customer segments (by age, income, commute distance, and car ownership) are most likely to purchase a bike, to support marketing decisions.

## Dataset
1,000 customer records with fields including marital status, gender, income, education, occupation, cars owned, commute distance, region, age, and whether the customer purchased a bike.

## Process
1. **Data cleaning:** Removed duplicate records, expanded abbreviations (M/S, M/F) to Married/Single and Male/Female, and standardized income formatting.
2. **Feature engineering:** Created an `Age Brackets` column with nested IF statements (Young Adult, Middle Age, Senior).
3. **Analysis:** Built four PivotTables with linked charts.
4. **Dashboard:** Combined the charts with slicers for marital status, region, and education.

## Key Findings
- Customers aged 31 to 55 had the highest purchase rate (about 54%), versus about 32% for seniors and 36% for young adults.
- Purchase rate fell from about 60% for customers with 0 to 1 cars to about 36% for those with 2 or more.
- Customers with longer commutes (10+ miles) bought bikes least often.
- Buyers had a somewhat higher average income than non-buyers.

## Tools
Microsoft Excel: PivotTables, PivotCharts, slicers, nested IF, Find & Replace, Remove Duplicates

## Files
- `Bike_Owners_Data.xlsx`: the full workbook (raw data, working sheet, PivotTables, dashboard)
- `screenshots/`: dashboard images

## Credits
Based on the guided project by [Alex The Analyst](https://www.youtube.com/watch?v=opJgMj1IUrc). I extended it with an additional PivotTable and chart analyzing car ownership.
