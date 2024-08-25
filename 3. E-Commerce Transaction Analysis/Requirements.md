
**Business Analytics Project Overview**

_Part 1: Build a Conversion Funnel_
Create a Conversion Funnel:
Use the raw_user_activity data.
Create a pivot table in a new sheet named conversion_funnel.
Count unique users at each stage: Product Page Views, Add to Cart, and Purchase.
Calculate total conversion rates and conversion rates to the next step.

_Part 2: Prepare Data for Cohort Analysis_
Filter and Isolate Purchase Data:

Create a new sheet purchase_activity.
Filter and copy only purchase events from raw_user_activity.
Ensure there are 4,845 rows.
Calculate First Purchase Dates:

Create a pivot table first_purchase to find the minimum purchase date per user.
Use VLOOKUP to add first_purchase_date to the purchase_activity sheet.
Set Up Monthly Data:

Add columns for event_month, first_purchase_month, and cohort_age using TEXT() and DATEDIF() functions.

_Part 3: Calculate Retention Rates_
Group Data into Cohorts:

Create a pivot table cohort_analysis with cohorts based on the month of the first purchase.
Include counts of unique users for each cohort_age (1-4 months).
Calculate Retention Rates:

Create a new sheet retention_rates.
Calculate and display retention rates for each cohort and cohort_age.

_Part 4: Organize and Document Your Spreadsheet_

Document and Organize:
Fill in the Executive Summary sheet with results and analysis.
Reorder sheets: Table of Contents, Executive Summary, analytical results, calculations, and raw data.
Format spreadsheets for readability (e.g., number formatting, borders, bold headers).
Deliverables
Conversion Funnel: Pivot table showing conversion rates.
Cohort Analysis: Pivot table showing user counts per cohort and cohort_age.
Retention Rates: Table displaying retention rates for each cohort and cohort_age.
Executive Summary: Detailed summary of results and analysis.
