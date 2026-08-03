# Bank Loan Analysis — SQL Project

## Overview
A comprehensive SQL analysis of 38,576 bank loan 
records using SQLite to uncover insights about 
loan performance, repayment trends, risk 
classification and customer demographics.

## SQL Queries
- `Bank_Loan_SQL_Queries.sql`

## Objectives
- Analyze loan applications, funded and received amounts
- Classify loans into Good vs Bad loans
- Perform trend analysis by month and region
- Identify factors affecting loan repayment
- Analyze customer demographics and loan patterns

## Tools Used
- SQL (SQLite)
- DB Browser for SQLite
- Excel (Data Preparation)

## Dataset
- Records: 38,576 rows
- Columns: 23
- Source: Financial Loan Dataset

## SQL Analysis Performed

### 1. Loan Summary KPIs
- Total Loan Applications
- Total Funded Amount
- Total Amount Received
- Average Interest Rate
- Average DTI

### 2. Good vs Bad Loan Analysis
- Good Loan Applications count and percentage
- Bad Loan Applications count and percentage
- Good Loan Funded Amount
- Bad Loan Funded Amount
- Good Loan Amount Received
- Bad Loan Amount Received

### 3. Monthly Trend Analysis
- Loan applications by month
- Monthly funded amounts
- Monthly received amounts
- Month over month growth

### 4. Regional Analysis (State)
- Loan applications by state
- Funded amount by state
- Amount received by state
- Top performing states

### 5. Loan Term Analysis
- Applications by loan term
- Funded amount by term
- Amount received by term

### 6. Employment Length Analysis
- Applications by employment length
- Funded amount by employment length
- Amount received by employment length

### 7. Home Ownership Analysis
- Applications by home ownership
- Funded amount by home ownership
- Amount received by home ownership

### 8. Grade Analysis
- Applications by loan grade
- Funded amount by grade
- Amount received by grade
- Interest rate by grade

### 9. Purpose Analysis
- Applications by loan purpose
- Funded amount by purpose
- Amount received by purpose
- Top loan purposes

### 10. Loan Status Analysis
- Applications by loan status
- Funded amount by status
- Amount received by status
- Fully Paid vs Charged Off analysis

## Business Questions Answered
1. What is the total number of loan applications 
   received and how much was funded?
2. What percentage of loans are Good vs Bad?
3. Which months have the highest loan applications?
4. Which states have the highest loan demand?
5. Which loan term is most preferred by borrowers?
6. Does employment length affect loan applications?
7. Which home ownership category has most borrowers?
8. Which loan grade has the highest applications?
9. What is the most common purpose for taking loans?
10. How does loan status affect funded and 
    received amounts?

## Key Insights
- Total of 38,576 loan applications received
  with $435.8M funded and $473.1M received
- Good Loans dominate the portfolio showing
  healthy repayment behavior
- Loan applications grow consistently month 
  over month showing increasing demand
- California, New York and Texas are top states
  for loan applications
- 60 month term is more popular than 36 months
  showing preference for longer repayment periods
- Borrowers with 10+ years employment have 
  highest applications showing stable income 
  drives loan demand
- Rent category dominates home ownership 
  showing most borrowers don't own homes
- Grade B loans have highest applications 
  showing moderate risk borrowers are dominant
- Debt consolidation is the number one purpose
  showing most people borrow to pay other debts
- Charged Off loans represent the Bad Loan 
  category requiring immediate attention

## Business Recommendations
1. Focus on Grade A & B borrowers
   These grades show best repayment behavior
   and should be prioritized for loan approval
2. Target high employment length customers
   Borrowers with 5+ years employment show
   better repayment — focus marketing here
3. Expand in top performing states
   California, New York and Texas show highest
   demand — increase loan offerings there
4. Review Charged Off loans immediately
   Bad loans need immediate intervention to
   recover funded amounts and reduce losses
5. Offer debt consolidation packages
   Since it's the top purpose, create special
   debt consolidation loan products with
   competitive interest rates
6. Monitor Q4 loan performance closely
   December shows highest applications —
   ensure enough funding is available
7. Review high DTI borrowers carefully
   Average DTI of 13.3% needs monitoring
   to prevent future defaults
8. Create targeted products for renters
   Most borrowers are renters — create
   special home loan products to help them
   transition to home ownership

## Recommendations Based on Findings

### For Risk Management:
- Implement stricter checks for Grade F and G loans
- Monitor Charged Off loans monthly
- Set DTI threshold at 13% for new applications

### For Business Growth:
- Increase marketing in top 5 states
- Create loyalty programs for repeat borrowers
- Offer competitive rates for Grade A borrowers

### For Customer Retention:
- Follow up with At Risk borrowers early
- Offer restructuring plans for struggling borrowers
- Create flexible repayment options for long term loans

## Project Structure
Bank-Loan-Analysis-SQL/
├── bank_loan_analysis.sql
├── financial_loan.csv
├── screenshots/
└── README.md

## Related Projects
- [Bank Loan Analysis Dashboard](link to Power BI repo)

