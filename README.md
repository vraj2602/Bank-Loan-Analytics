BANK LOAN ANALYTICS DASHBOARD

1. Project Title:
Bank Loan Analytics Dashboard – Lending Performance and Portfolio Monitoring System
A data-driven Excel dashboard designed to analyze, visualize, and track key loan performance metrics, borrower risk indicators, and portfolio health across the bank’s lending pipeline.

2. Project Overview / Purpose: 
The Bank Loan Analytics Dashboard provides an integrated view of loan applications, funded amounts, repayments, interest rates, borrower characteristics, and loan risk distribution. It enables banking teams, credit analysts, managers, and decision-makers to monitor financial performance, evaluate lending risk, and support data-driven strategy development.

3. Tools and Technologies Used (Tech Stack): 
• Microsoft Excel – Primary platform for dashboard creation 
• Power Query – Data cleaning, transformation, and ETL operations 
• Excel Formulas & Functions – KPI calculations, logical derivations, ratio metrics 
• Excel Data Modeling – Structured tables, normalized fields, relationship mapping 
• Data Visualization Tools – Line charts, bar charts, donut charts, treemaps, filled maps

4. Data Source Dataset: https://www.kaggle.com/datasets/adarshsng/lending-club-loan-data-csv

Problem Statement:
The dataset includes detailed loan-level attributes such as: 
• Loan status (Fully Paid, Current, Charged Off) 
• Funded amount and received amount 
• Interest rates and DTI (Debt-to-Income Ratio) 
• Borrower employment length 
• Loan purpose categories 
• Home ownership type 
• Loan term duration 
• State/region information 
• Issue date for time-series analysis Data was cleaned, validated, transformed, and structured for accurate KPI reporting and dashboard automation.

5. Key Features and Insights:

A. Business Problem:
Banks often manage large volumes of loan applications and repayments across multiple customer segments. Raw datasets make it difficult to track: 
• How many loans were funded this month? 
• What percentage of loans are "good" vs. "bad"? 
• Which states are generating the highest loan volume? 
• How do interest rates vary by borrower type? 
• Which loan purposes carry higher risk? 
A centralized analytics dashboard was required to simplify loan monitoring, operational reporting, and strategic decision-making.

B. Dashboard Objectives: 
• Consolidate all critical lending metrics into a single analytical interface 
• Provide real-time tracking of applications, funding, and repayments 
• Segment loan performance into Good Loans and Bad Loans 
• Enable trend analysis using timeline-based visualizations 
• Support strategic insights on borrower demographics and loan attributes 
• Improve portfolio risk assessment and operational efficiency.

6. Detailed Breakdown of Dashboard Components:

Dashboard 1: Summary Dashboard 
A high-level portfolio overview focusing on KPIs, loan quality, and portfolio distribution.

KPI Metrics 
• Total Loan Applications 
• Total Funded Amount 
• Total Amount Received 
• Average Interest Rate 
• Average Debt-to-Income (DTI) 
Each KPI includes Month-to-Date and Month-over-Month change indicators.

Good Loan vs. Bad Loan Performance
Good Loans (Fully Paid + Current): 
• Good Loan Percentage 
• Total Good Loan Applications 
• Good Loan Funded Amount • Good Loan Amount Received

Bad Loans (Charged Off): 
• Bad Loan Percentage 
• Total Bad Loan Applications 
• Bad Loan Funded Amount 
• Bad Loan Amount Received 
This classification improves credit risk evaluation and decision-making.

Loan Status KPI Grid 
A comparative grid across three statuses: 
• Fully Paid 
• Current 
• Charged Off 
Metrics include: 
• Loan applications 
• Funded amounts 
• Amount received 
• Average interest rates 
• Average DTI values

Dashboard 2: Overview Dashboard 
Focused on trends, segmentation, and demographic-based loan analysis.

Monthly Trend Analysis (Line Chart):
Displays monthly values of: 
• Total Applications 
• Total Funded Amount 
• Total Received Amount 
Useful for identifying seasonal trends and lending cycles.

State-Level Loan Activity (Filled Map): 
Shows geographic distribution of: 
• Loan Applications 
• Funding 
• Payments Received 
Supports regional performance analysis and market targeting.

Loan Term Analysis (Donut Chart):
Breakdown of loan terms such as: 
• 36-month loans 
• 60-month loans 
Helps analyze borrower preferences and long-term exposure.

Employment Length Analysis (Bar Chart):
Compares applications, funded amounts, and payments across employment length categories (1 year, 5 years, 10+ years). 
Useful for understanding borrower stability and risk indicators.

Loan Purpose Analysis (Bar Chart):
Breakdown by major loan reasons such as: 
• Debt consolidation 
• Credit card refinancing 
• Home improvement 
• Small business 
• Medical 
Supports product strategy and market segmentation.

Home Ownership Analysis (Tree Map):
Segments borrowers into: 
• Rent 
• Own 
• Mortgage 
Reveals how ownership status influences borrowing patterns.


Dashboard 3: Details Dashboard 
A comprehensive, filter-driven table providing full loan-level insights. 
Includes fields such as: 
• Borrower details 
• Loan attributes 
• Status 
• Financial metrics 
• Repayment values 
• Filters for grade, purpose, term, home ownership, and location 
Useful for audits, deep dives, and operational monitoring.

7. Business Impact: 
• Improved visibility into loan portfolio performance 
• Faster identification of high-risk categories 
• Enhanced ability to detect lending trends and anomalies 
• Better segmentation for targeted lending strategies 
• Streamlined reporting for management and audit teams 
• Data-driven decision-making for credit policy and loan product design

8. Screenshots/Demos:
https://github.com/vraj2602/Bank-Loan-Analytics/blob/main/Bank%20Loan%20Summary.png 
https://github.com/vraj2602/Bank-Loan-Analytics/blob/main/Bank%20Loan%20Overview.png
