# BANK-LOAN-ANALYSIS-

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [TOOLS](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratoy Data Analysis ](#exploratory-data-analysis)
- [Insights](#insights)
- [Recommendations](#recommendations)
 
  


### Project Overview

This report presents a comprehensive analysis of the bank loan data-set, which contains detailed customer information. The objective of this analysis is to identify patterns and key factors influencing loan approvals, uncover actionable insights for targeted promotional strategies, and support data-driven decision-making within the organization.

### Data Sources
Bank Data:The primary dataset used for this analysis is the 'bank loan_data.csv" file, containing information about customers transactions with the bank.

### Tools
- Excel - Data Cleaning
- SQL Server - Data Analysis
- PowerBI - Data Visualisation

### Data Cleaning

The dataset was loaded in Excel and data cleaning and transformation was done to prepare the data for exploration and modeling.The steps includes;
1. Columns containing similar and related data were combined using the CONCATENATE function in Excel.
2. Handling Missing Values
3. Columns, such as the age column, were created to enhance dashboard design and reduce complexity and clutter.
4. Standardize formats for dates and other fields to ensure consistency. 
5. Validate relationships between tables and rectify any referential integrity issues.
6. Ensured fields are in the correct data type, such as converting dates to date format.
7. Removed unnecessary columns or rows that are not needed for the analysis.

### Exploratory Data Analysis
Exploratory Data Analysis (EDA) on the Bank Loan Approval dataset involves thoroughly examining the data to understand its key characteristics   and answer key question, such as;

- What kind of Customer is Likely to have their loan approve?
- Does account balance influence loan Approval? 
- What Factor influences Loan the most?
- 
### Insights 
1. Valid transactions dominate loan activity with balanced outcomes,showing strong trust.
2. Scammy transactions are few and likely face stricter checks due to risk.
3. Customers with average balances show the highest and most balanced loan activity, reflecting financial stability.
4. Owing account holders show the least activity, suggesting limited approval due to higher financial risk.
5. Newcomers have the lowest approval rates, with rejections nearly equal, suggesting the bank is more cautious with newer clients.

### Recommendations

1. Prioritize customers with strong loan performance and offer loyalty programs to retain them.
2. Give higher importance to account balance as a predictor in loan approval models due to its strong correlation with outcomes.
3. Provide personalized feedback and tips to help rejected applicants improve and reapply successfully.
4. Include transaction type (valid vs scammy) as a key feature in predictive models to assess risk and eligibility.
5. Continue strengthening fraud detection systems, adding manual verification or KYC checks where necessary.
6. Offer micro-loans, financial education, and credit-building programs to improve their approval chances.
7. Use age as a predictive feature for approval and risk management.

 
