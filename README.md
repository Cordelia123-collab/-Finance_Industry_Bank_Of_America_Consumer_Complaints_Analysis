# Bank of America Consumer Complaints Analysis (2017–2023)

## Project Overview

This project analyzes Bank of America Consumer Complaints (2017–2023) using data from the Consumer Financial Protection Bureau (CFPB). The analysis identifies complaint trends, evaluates response performance, and uncovers insights to improve customer experience, operational efficiency, and risk management.

## Problem Statement

Financial institutions receive thousands of customer complaints annually, making it difficult to identify recurring issues and improve service delivery. This project transforms complaint data into actionable business insights to support informed decision-making.


## Business Questions

The analysis answers the following questions:

1. Which states recorded the highest customer complaints?
2. Which banking products generated the most complaints?
3. How have customer complaints changed over time?
4. How effective is the bank's complaint response process?
5. What opportunities exist to improve customer satisfaction?


## Dataset

Source: Consumer Financial Protection Bureau (CFPB)

Period: 2017–2023

### Dataset Summary

- Records: 62,516
- Columns: 12

### Features

- Complaint ID
- Date Submitted
- Date Received
- State
- Product
- Sub-product
- Issue
- Sub-issue
- Submitted Via
- Company Public Response
- Company Response to Consumer
- Timely Response


## Tools Used

- Microsoft Excel
- Power BI


## Data Cleaning

The following data preparation steps were completed:

- Converted the dataset into an Excel Table
- Checked for duplicates (none found)
- Expanded abbreviated state names
- Replaced missing values with:
  - Pending (Timely Response)
  -To be confirmed (Sub-product, Sub-issue, Company Public Response)
- Prepared the dataset for analysis in Power BI


## Data Analysis

### Power BI

Created:

- Date Table
- DAX Measures including:
  - Total Complaints
  - Timely Response Rate
  - Pending Response Rate
  - Total Products
  - Total States
  - Timely Responses
  - Pending Responses
  - Untimely Responses

## Dashboard

The report consists of two interactive dashboard pages.

### Page 1 — Customer Complaints Overview

Displays:

- KPI Cards
- Top 10 Complaints by State
- Top 10 Products
- Monthly Complaint Trend
- Complaints by Submission Channel
- Complaints by Issue
- Interactive Filters

### Page 2 — Complaint Trends & Response Performance

Displays:

- Response Performance KPIs
- Timely Response Distribution
- Quarterly Complaint Trend
- Timely Responses by Product
- Product Response Matrix
- Interactive Filters

## Key Insights

### Complaint Hotspots

California recorded the highest number of complaints (13,709), followed by Florida and Texas.

###  Checking & Savings Accounts Generated the Most Complaints

Checking & Savings Accounts accounted for 24,814 complaints, making them the most complained-about banking product.

###  Strong Response Performance

The bank achieved a 93.77% Timely Response Rate, demonstrating efficient complaint handling.


### Pending & Late Responses Remain

Although response performance is strong, over 3,800 complaints were either pending or responded to late.

### Complaint Volume Declined in Q4

Complaint volume reduced noticeably in the fourth quarter, suggesting improvements in service delivery or complaint prevention.

## Recommendations

- Prioritize service improvements in high-complaint states.
- Review and simplify processes for Checking & Savings Accounts.
- Conduct root cause analysis for recurring complaints.
- Reduce pending complaints through SLA monitoring.
- Replicate successful practices from low-complaint regions.

## Skills Demonstrated

- Data Cleaning
- Data Transformation
- Power BI
- DAX
- Dashboard Design
- Data Visualization
- Business Intelligence
- Data Storytelling

## Project Files

- Cleaned Dataset
- Power BI Dashboard (.pbix)
- Excel Workbook
- README
- Dashboard Screenshots

## Prepared By:

Cordelia O. Jiakponna

Corporate Governance | Data Analytics | Power BI | Excel | AI for Business

GitHub: https://github.com/Cordelia123-collab
