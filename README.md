## 🔍 Loan Default Prediction & Analysis Dashboard (Power BI + SQL)
This project analyzes a loan dataset to identify patterns and risk factors associated with loan defaults. The goal is to clean the data using SQL in SQL Server and build a Power BI dashboard that provides actionable insights for financial institutions to make better lending decisions and for clear insights. <br>
[Click here to view the project](https://app.powerbi.com/links/lGDMFxh7QI?ctid=a3a31cf5-d129-4352-ab9d-a803b01de947&pbi_source=linkShare&bookmarkGuid=caca3de6-44b4-46b9-ac44-0ccf0f650c57)

## 📊 Dataset Features:
### The dataset includes the following features:

- **Loan Details:** `LoanID`, `LoanAmount`, `InterestRate`, `LoanTerm`, `LoanPurpose`, `Loan Date`  
- **Borrower Profile:** `Age`, `Income`, `CreditScore`, `MonthsEmployed`, `NumCreditLines`, `Education`, `EmploymentType`, `MaritalStatus`, `HasMortgage`, `HasDependents`, `HasCoSigner`
- **Target Variable:** `Default` (indicates whether a loan was defaulted)

- **Financial Metrics:** DTIRatio (Debt-to-Income Ratio)

- **Target Variable:** Default (indicates whether a loan was defaulted)

## 🧠 Key Objectives:
- Analyze demographic and financial factors that influence loan default rates
- Explore the relationship between credit score, DTI ratio, and interest rates
- Identify high-risk borrower segments
- Visualize trends over time using the `YOY Amount Change by year`, `YTD Loan Amount by Marital Status`,`Loan by Education type`

## 🛠 Tools Used:
- **Power BI** – for interactive dashboards, slicers, conditional formatting, and bookmarks
- **SQL** – for data transformation and querying
- **Excel** – for initial data preprocessing and data validation (cross checking the counts)

## 💡 Features of the Power BI Dashboard:
- Loan default distribution by age group, income level, and loan purpose
- Trends of loan disbursement and defaults over time
- Conditional formatting to highlight high-risk borrowers
- Filters by employment type, education level, and marital status

## ☁️ Deployment & Automation:

- ✅ Published to Power BI Service for real-time sharing and collaboration
- 🔄 Scheduled Refresh set up to keep data updated on a daily basis
- 🧠 Incremental Refresh enabled to optimize large dataset performance
- 🔐 Row-Level Security (RLS) configured to control access based on user role

This is how first slide of dashboard looks like. ![Alt-text](https://github.com/amitdev3/Loan-Default-Data-Analysis/blob/main/Loan%20Default%20%26%20Overview.png)

