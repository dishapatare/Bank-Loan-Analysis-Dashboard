# Bank Loan Analysis Dashboard (Tableau)
An interactive Tableau dashboard built to visualize and analyze bank loan performance, trends, and borrower profiles. This project showcases the power of data analytics to support smarter lending decisions by tracking key loan KPIs, risk indicators, and borrower demographics.

## Purpose
This project provides an end-to-end analysis of a bank's loan portfolio using Tableau. It helps identify trends in loan issuance, repayment behavior, interest rates, defaults, and more. The dashboard supports financial institutions in understanding customer risk profiles and improving lending strategies through interactive visual insights.

## Requirements
1. **Key Performance Indicators**
    - Total Loan Applications (Month to Date, Month over Month)
    - Total Funded Amount (Month to Date, Month over Month)
    - Total Amount Received (Month to Date, Month over Month)
    - Average Interest Rate (Month to Date, Month over Month)
    - Average Debt-to-Income Ratio (Month to Date, Month over Month)
      
2. **Good/Bad Loan KPI's**
    - Good/Bad Loan Application Percentage
    - Good/Bad Loan Total Applications
    - Good/Bad Loan Total Funded Amount
    - good/Bad Loan Total Received Amount

3. **Loan-Related Metrics and Trends**
    - Monthly Trends by Issue Date
    - Regional Trends by State
    - Loan Term Analysis
    - Employee Length Analysis
    - Loan Purpose Breakdown
    - Home Ownership Analysis

## Tech Stack
The dashboard was developed using the following tools:

📊 Tableau Public – Main data visualization platform used for building interactive dashboards.  
📋 Microsoft Excel / CSV – Source of raw loan data for import into Tableau.  
🔍 Calculated Fields in Tableau – Used for Month-To-Date (MTD), Good/Bad Loan classification, Avg Interest, DTI, and KPIs.  
🧮 SQL Queries - Used to prepare calculated metrics later replicated in Tableau.  

## Data Source
- CSV File: [financial_loan.csv](./financial_loan.csv)
- Total Records: 38,576 loan applications
- Fields Include:
loan_status, loan_amount, total_payment, issue_date, int_rate, dti, purpose, term, grade, home_ownership, emp_length, address_state, etc.

## Features / Highlights
**Business Problem**<br>
Financial institutions need an efficient way to analyze loan performance and borrower behavior across a large number of applications. Identifying default trends, good vs bad loans, and understanding funding performance is essential for risk management and growth.

**Goal of the Dashboard**<br>
To develop a Tableau dashboard that:

  - Tracks key lending metrics over time.<br>
  - Identifies the proportion of good and bad loans.<br>
  - Analyzes loan purposes, repayment patterns, and borrower characteristics.<br>
  - Highlights state-wise lending behavior and loan term preferences.

## Key Insights
  - Debt Consolidation is the most common loan purpose (~18.2K applications).
  - Majority loans are for a 36-month term (73.2%).<br>
  - California, New York and Florida have the highest number of applications.<br>
  - Good loans (fully paid/current) dominate the dataset, indicating strong repayment behavior.<br>
  - Renters applied slightly more than mortgage holders.<br>
  - People with more than 10 years of work history made the maximum loan applications.<br>
  - Slight linear growth in number of loan applications every following month.

## Live Dashboard / Report
https://public.tableau.com/views/BankLoanAnalysisDashboard_17535083405840/SUMMARY?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Screenshots of Dashboard / Report
![dash1]<img width="1999" height="1124" alt="SUMMARY" src="https://github.com/user-attachments/assets/59fb0002-b960-4b89-aea4-8e1a2718290e" />
