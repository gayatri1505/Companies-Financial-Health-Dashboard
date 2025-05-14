# Companies-Financial-Health-Dashboard
This Power BI dashboard delivers a deep dive into the financial strength and performance of companies using real-world financial indicators. Built from scratch with carefully modeled data and custom DAX measures, this dashboard allows users to explore profitability, leverage, and efficiency across industries and regions—unlocking powerful business insights for analysts, executives, and investors alike.

## Project Summary

This dashboard is the result of a comprehensive data analysis pipeline that involved:

- Sourcing and modeling structured company-level financial data
- Creating reusable and dynamic DAX measures
- Building interactive visualizations and filters in Power BI
- Highlighting key financial performance metrics like **Net Income Margin**, **ROA**, **ROE**, and more

## Impact
This tool transforms raw financial figures into **decision-ready insights**—enabling business stakeholders to **benchmark companies**, **assess financial health**, and **spot risk indicators** with ease.

## Business Problem Solved

Financial data is often complex and overwhelming, especially when dealing with multiple companies and indicators. This dashboard simplifies it by:

- Consolidating key financial metrics in a single view
- Allowing flexible filtering by industry, location, and company age
- Surfacing insights to support investment decisions, peer benchmarking, or operational health reviews


## Dataset Overview

### Table: `Companies_1_Oct_2023-31_May_24`

| Category             | Fields Included                                                                 |
|----------------------|----------------------------------------------------------------------------------|
| Company Info         | `companyName`, `hqLocation`, `yearFounded`, `primaryIndustryCode`, `ownershipStatus` |
| Investors & Funding  | `activeInvestors`, `lastFinancingDate`, `lastFinancingSize`, `lastFinancingDebtSize`, `lastFinancingDealType` |
| Financial Data       | `revenue`, `netIncome`, `grossProfit`, `ebitda`, `marketCap`, `netDebt`, `enterpriseValue` |

---

## DAX Measures

All critical financial KPIs were created using **custom DAX logic** to ensure reusability and consistency across visuals.

### Financial KPIs Modeled

- **Asset Turnover Ratio**  
- **Gross Profit Margin**
- **Net Income Margin**
- **Return on Equity (ROE)**
- **Return on Assets (ROA)**
- **Debt to Equity Ratio**
- **Interest Coverage Ratio**

These measures allow the dashboard to dynamically reflect financial performance for any selected subset of companies.

---

## Dashboard Features

![image](https://github.com/user-attachments/assets/b50b98d5-9467-40f6-a43a-5ec2cb5282f9)


### Visual Components

- **KPI Cards**: Instantly highlight performance on key ratios
- **Dynamic Slicer**: Filter data by:
  - Primary Industry Category
  - HQ Location
  - Year Founded
- **Charts**:
  - Bar charts for **Revenue by Company** and **EBITDA**
  - Line chart for **Revenue Growth** across companies
- **Company Table**:
  - Shows name, investors, HQ, year founded, and net income


## Impact of My Work

- **Transformed static data into interactive intelligence** for business users
- **Revealed performance trends** across companies, helping detect under- and over-performers
- Enabled **real-time exploration** of financial performance across industries and geographies
- Applied **advanced DAX modeling** for accurate and scalable metric calculation


## Tools & Technologies Used

- **Power BI Desktop** – Visualization & DAX Modeling
- **DAX** – Custom KPIs & business rule logic
- **Relational Data Model** – Linking financials with metadata
- **Cleaned Tabular Dataset** – Real company data across time



> *"Behind every number lies a story. This dashboard helps you hear it clearly, quickly, and confidently."*
