# 📊 Palmoria Group HR Analysis
## 📁 Overview
The Palmoria Group HR Analysis project is a data-driven HR analytics case study for a Nigerian manufacturing company; Palmoria Group which is facing public scrutiny over gender inequality across its three operational regions. This analysis is to support strategic decision-making and mitigate reputational risk.

The insights generated from this report are intended to help Palmoria address internal gender-related issues, identify pay disparities, evaluate regional performance alignment, and ensure compliance with government-mandated compensation policies.

## 🎯 Objectives
- Assess gender representation and disparities in the organization

- Identify potential gender pay gaps across departments and regions

- Evaluate the organization’s compliance with minimum wage regulations

- Recommend strategic areas for intervention based on employee performance ratings

- Compute and distribute performance-based bonus payments

- Provide clear, visual insights to guide executive decision-making

## 📌 Key Questions Answered

### ✅ Gender Insights
- What is the overall gender distribution in the company?

- How does gender representation vary by region and department?

### ✅ Performance Ratings
- How do performance ratings vary across genders?

### ✅ Pay Gap Analysis
- Is there a gender pay gap?

- Which regions and departments are most affected?

### ✅ Salary Compliance
- Does Palmoria meet the minimum salary requirement of $90,000?

- Pay distribution grouped in $10,000 bands

- Salary distribution broken down by region

### ✅ Bonus Allocation
- What is the total bonus and salary + bonus for each employee?

- What is the total bonus payout per region and company-wide?

### 🧹 Data Cleaning Rules
- Employees with no salary data (no longer with the company) were removed

- Employees in departments labeled "NULL" were excluded

- Employees with undisclosed gender were assigned a default label: "Unspecified"

### 📊 Visualizations Used
The Power BI report includes the following:

- Gender Distribution: Pie and stacked column charts (by region and department)

- Performance Ratings by Gender: Line Chart

- Average Salary by Gender and Location: stacked bar chart

- Salary Distribution Bands: Clustered Column Chart with $10,000 intervals

- Salary Compliance Check: KPI visual and conditional column chart

- Bonus Allocation Summary: Matrix and stacked column visuals per region

- Total Compensation (Salary + Bonus): Table visual and cards

## 📎 Files Included
### Filename	Description
- Palmoria_HR_Data.pbix	Main Power BI report file with all visuals and insights
- Employee_Data.xlsx	Cleaned dataset of employees
- Bonus_Rules.xlsx	Rules used to calculate bonuses based on performance rating
- README.md	Project overview and documentation

### 🧮 Bonus Calculation Logic
- Bonus is computed using a join between the Employee Data and Bonus Rules table via performance rating

- Total Pay = Base Salary + Calculated Bonus

- Aggregated bonus payouts calculated per region and company-wide

### 📢 Recommendations
Based on the findings in the report, key recommendations were made to:

- Address gender imbalance in specific regions and departments

- Investigate and close gender pay gaps, especially in high-risk units

- Review and revise compensation policies to meet legal requirements

- Improve performance review transparency across gender lines

