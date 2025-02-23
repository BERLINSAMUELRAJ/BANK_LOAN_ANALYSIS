# Comprehensive Analysis of Bank Loan Transactions for Enhanced Decision-Making
![](https://github.com/BERLINSAMUELRAJ/BANK_LOAN_ANALYSIS/blob/main/digital-banking-loans-data.webp)
## Introduction
The banking sector is pivotal in managing personal and business finance through loan offerings. Understanding the dynamics of loan transactions, customer profiles, and repayment behaviors is essential for optimizing lending strategies and minimizing default risks. This project focuses on a bank loan dataset that captures critical information about loan transactions. By analyzing this data, we aim to uncover insights that can enhance the bank's lending policies and improve customer service.

## Project Objective
The primary objective of this project is to analyze the bank loan dataset and extract meaningful insights that can assist the business in the following areas:
- **Loan Status Analysis**: Understanding the status of loans (approved, declined, paid, defaulted) and their impact on revenue.
- **Customer Profiling**: Analyzing borrower characteristics, such as income and credit history, to identify trends among high-risk and low-risk borrowers.
- **Repayment Behavior**: Evaluating repayment patterns to enhance collection strategies and minimize defaults.
- **Loan Purpose Evaluation**: Examining the reasons for borrowing and their correlation with repayment success.

## Dataset Overview
The dataset includes the following key attributes:
- **issue_date**: Date when the loan was issued.
- **last_credit_pull_date**: Most recent date the borrower’s credit was reviewed.
- **last_payment_date**: Date when the last payment was made.
- **loan_status**: Current status of the loan (e.g., Current, Late, Charged Off).
- **next_payment_date**: Scheduled date for the next payment.
- **member_id**: Unique identifier for each borrower.
- **purpose**: Reason for the loan (e.g., debt consolidation, home improvement).
- **sub_grade**: Subcategory of the loan grade based on credit risk.
- **term**: Duration of the loan (in months).
- **verification_status**: Indicates if the borrower’s income is verified.
- **annual_income**: Borrower’s annual income.
- **dti**: Debt-to-income ratio, a measure of borrowing capacity.
- **installment**: Monthly payment amount.
- **int_rate**: Interest rate on the loan.
- **loan_amount**: Total amount of the loan.
- **total_acc**: Total number of accounts held by the borrower.
- **total_payment**: Total amount paid by the borrower till date.

This dataset provides a comprehensive view of bank loan transactions, enabling in-depth analysis and actionable insights.

## Analytical Approach

### Data Preprocessing
Before analysis, the dataset will undergo the following steps:
- **Cleaning**: Handling missing values, duplicates, and outliers to ensure data integrity.
- **Transformation**: Converting date fields into datetime objects and categorical variables into numerical values for analysis.
- **Feature Engineering**: Creating new features, such as loan age, repayment duration, and risk categories based on loan status and borrower profile.

### Exploratory Data Analysis (EDA)
This phase will focus on:
- **Loan Status Distribution**: Analyzing the distribution of loan statuses to understand risk exposure.
- **Customer Income Analysis**: Evaluating the relationship between annual income and loan approval rates.
- **Loan Purpose Impact**: Identifying which loan purposes are associated with higher repayment rates.
- **DTI Ratio Analysis**: Analyzing the correlation between DTI ratio and loan default rates.

### Performance Analysis
- **Loan Performance by Grade**: Assessing the performance of loans based on sub-grade classification.
- **Interest Rate Impact**: Evaluating how interest rates affect repayment behavior and loan status.
- **Repayment Timeliness**: Analyzing factors influencing timely repayments and defaults.
- **Total Payments Analysis**: Assessing the total payment patterns across different loan types and customer segments.

### Customer Satisfaction and Risk Analysis
- Evaluating customer satisfaction metrics related to loan processing times and repayment experiences.
- Identifying risk factors that lead to loan defaults and developing strategies to mitigate them.

## Tools and Techniques
To conduct this analysis, the following tools and techniques will be used:
- **Python** or **R** for data manipulation, analysis, and visualization (Pandas, NumPy, Matplotlib, Seaborn).
- **SQL** for querying the dataset and extracting specific insights.
- **Microsoft Excel**/Google Sheets for basic data exploration and visualization.
- **Tableau**/Power BI for advanced data visualization and dashboard creation.

## Key Deliverables
- **Comprehensive Analysis Report**: A detailed report outlining key findings from the data analysis.
- **Dashboards/Visualizations**: Interactive visualizations highlighting trends, performance metrics, and customer insights.
- **Strategic Recommendations**: Actionable insights and recommendations for improving lending strategies, customer satisfaction, and risk management.
- **Presentation**: A slide deck summarizing the project findings and recommendations for stakeholders.

## SNAPSHOT OF THE DASHBOARD
SEE THE FULL DASHBOARD HERE - [APP POWER BI LINK](https://app.powerbi.com/view?r=eyJrIjoiNDZkNDY3YzYtMmZjMS00NzA0LThmYzUtOTJmM2ZlNmNlZGQ4IiwidCI6ImI1NzkyOWNlLTZjNDMtNDUzZC1hZDdiLTc2MTJiNDA4NWQyMCJ9)

![](https://github.com/BERLINSAMUELRAJ/BANK_LOAN_ANALYSIS/blob/main/Page%201.png)

![](https://github.com/BERLINSAMUELRAJ/BANK_LOAN_ANALYSIS/blob/main/Page%202.png)

![](https://github.com/BERLINSAMUELRAJ/BANK_LOAN_ANALYSIS/blob/main/Page%203.png)

![](https://github.com/BERLINSAMUELRAJ/BANK_LOAN_ANALYSIS/blob/main/Page%204.png)

![](https://github.com/BERLINSAMUELRAJ/BANK_LOAN_ANALYSIS/blob/main/Page%205.png)

## Conclusion
This project aims to provide a holistic understanding of bank loan performance by leveraging available transaction data. The insights generated from this analysis will support enhanced decision-making, optimize lending strategies, and improve overall customer satisfaction. The findings will be valuable for banking decision-makers and financial analysts.
