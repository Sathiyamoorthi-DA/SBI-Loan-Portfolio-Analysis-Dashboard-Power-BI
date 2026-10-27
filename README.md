# SBI Loan Portfolio Analysis Dashboard | Power BI

An interactive banking dashboard designed to help management monitor credit trends, portfolio composition, risk metrics, approval rates, and customer demographics for State Bank of India (SBI).

**Created by:** S. Sathiyamoorthi  
**Tool:** Microsoft Power BI  
**Reporting Period:** Multi-Year Banking Data (2018 – 2023+)  
**Domain:** Financial Analytics | Credit Risk & Loan Portfolio Management

## Dashboard Preview

[![SBI Loan Portfolio Analysis Dashboard](Screenshots/sbi-loan-portfolio-dashboard.png)](https://github.com/Sathiyamoorthi-DA/SBI-Loan-Portfolio-Analysis-Dashboard-Power-BI/blob/main/Screenshot/Sbi_Loan_analysis_dashboard.png)

## Business Objective

The objective of this project is to build an executive credit analytics dashboard that aggregates key metrics on loan applications, total funding, credit risk grades, approval percentages, and default rates into a single reporting view. It enables credit officers and bank leadership to evaluate lending growth, risk exposure, and borrowing trends across customer profiles.

## Key Performance Indicators

- **Total Applications:** 38.6K
- **Total Funded Amount:** ₹ 4,032 Cr
- **Average Loan Amount:** ₹ 12.7 L
- **Approval Rate:** 82.50%
- **Default Rate:** 7.14%

*Note: These values are captured directly from the dashboard screenshot and should be validated against the underlying dataset.*[cite: 8]

## Dashboard Features

### 1. Executive Metric Header
Provides quick top-level insights into total applications, total disbursed/funded capital, average borrowing per customer, overall approval percentage, and default rate.

### 2. Loan Applications Trend
Tracks application volumes alongside approved loans annually (from 2018 onward) to show demand trajectory over time.

### 3. Funded Amount (Cr) by Year
Visualizes year-over-year disbursement growth, rising from ₹ 377 Cr (2018) to ₹ 1,002 Cr.

### 4. Loan Distribution by Purpose
Ranks the top customer borrowing reasons:
- **Debt Consolidation:** 13K applications
- **Home Improvement:** 9K applications
- **Major Purchase:** 6K applications
- **Medical:** 4K applications
- **Business:** 4K applications

### 5. Approval Rate by Employment Type
Analyzes loan approval rates across employment categories:
- **Full Time:** 90.92%
- **Part Time:** 76.73%
- **Self-Employed:** 70.14%
- **Not Employed:** 61.98%

### 6. Loan Status Distribution
Donut chart breakdown of portfolio loan statuses out of 38.6K total loans:
- **Fully Paid:** 17K (42.8%)
- **Current:** 12K (30.32%)
- **Rejected:** 7K (17.5%)
- **Charged Off / Late (16–30 days)**

### 7. Loan Amount by Credit Grade
Bar chart illustrating median loan amounts granted across risk tiers ranging from high quality (**Grade A**) to higher risk (**Grade G**).

### 8. Interactive Slicers & Dynamic Filtering
Filters the entire dashboard view by **Year**, **State**, **Loan Purpose**, **Loan Term (Yr)**, **Employment Type**, and **Home Ownership**.

## Business Questions Addressed

- How are loan application volume and approved loans trending year-over-year?
- How much total capital has been disbursed across the loan portfolio?
- Which borrowing purposes drive the highest volume of loan applications?
- How does an applicant's employment status affect their approval probability?
- What proportion of loans are current vs. fully paid, charged off, or rejected?
- How does loan size scale across different risk/credit grades (A to G)?

## Tools and Skills

- Microsoft Power BI
- Financial Analytics & Banking KPIs
- Credit Risk & Portfolio Analysis
- DAX (Data Analysis Expressions)
- Data Modeling & Relationships
- Executive Dashboard Layout & Dark Theme UI Design

## Data Disclaimer
This dashboard was created as a portfolio/demo project. All figures represent synthetic or anonymized banking data created solely for visualization purposes and do not represent confidential data of State Bank of India.

## Author
S. Sathiyamoorthi

Portfolio Project: SBI Loan Portfolio Analysis Dashboard

Focus: Banking Analytics | Credit Risk | Power BI | MIS Reporting


## Project Structure

```text
sbi-loan-portfolio-powerbi/
├── README.md
├── Screenshots/
│   └── sbi-loan-portfolio-dashboard.png
├── data/
│   └── sbi_loan_data.csv
├── powerbi/
│   └── SBI_Loan_Portfolio_Analysis.pbix
└── DAX_Measures.md
