# Bank Loan Analysis Dashboard (Power BI)

## Overview
This project analyzes and visualizes bank loan data to monitor lending activities, assess portfolio health, and support data-driven decision-making.  
It includes three interactive dashboards (Summary, Overview, Details) built in Power BI, leveraging **Power Query** and **DAX** for data transformation, modeling, and calculation of key metrics.

## Key Features
- **Summary Dashboard:**  
  - KPIs: Total Loan Applications, Funded Amount, Amount Received, Average Interest Rate, and DTI (with MTD & MoM tracking)
  - Good vs. Bad Loan KPIs based on loan status (Fully Paid, Current, Charged Off)

- **Overview Dashboard:**  
  - Monthly Trends (Line Chart)
  - Regional Analysis (Filled Map)
  - Loan Term Distribution (Donut Chart)
  - Employment Length Breakdown (Bar Chart)
  - Loan Purpose Breakdown (Bar Chart)
  - Home Ownership Analysis (Tree Map)

- **Details Dashboard:**  
  - Grid view with loan status categories
  - Detailed borrower and loan performance information for deeper analysis

## Tools & Skills Used
- **Power BI Desktop** – Built three interactive dashboards (Summary, Overview, Details)
- **Power Query** – Imported and cleaned raw loan data, handled null values, changed data types, removed duplicates, filtered records, and created a structured dataset ready for modeling
- **DAX** – Created calculated columns and measures (e.g., MoM growth, Good vs. Bad Loan KPIs, Average Interest Rate, Average DTI)
- **Data Modeling** – Established relationships between tables and optimized data model for performance
- **Interactive Visual Design** – Used slicers, drill-downs, and multiple chart types (Line, Map, Donut, Bar, Tree Map) to enable easy insights

## Files Included
- `Bank_Loan_Report.pbix` – Power BI Desktop file  
- `Bank_Loan_Report.pdf` – PDF snapshot of dashboards  
- `screenshots/` – Folder with dashboard screenshots  

## How to Use
1. Download the `.pbix` file from this repository.  
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/).  
3. Explore interactive filters, slicers, and visuals across three dashboards.  

## 📈 Key Insights
- Tracks MoM changes in loan applications, funded amounts, and repayments.
- Identifies regions, loan terms, and borrower profiles contributing to portfolio performance.
- Differentiates between good and bad loans for better risk assessment.

## Author
**Shravani Deodare**  
*Data Enthusiast | SQL Learner*

---

