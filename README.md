📊 HR Analytics Dashboard

A comprehensive Power BI HR Analytics Dashboard designed to identify key workforce insights such as attrition rate, job satisfaction, employee demographics, salary patterns, and tenure trends.
This dashboard helps HR teams make data-driven decisions to improve employee retention and optimize organizational performance.

🚀 Project Overview

This project analyzes employee data to answer critical HR questions:

What is the company’s attrition rate?

Which age groups, job roles, and education fields have the highest attrition?

What is the average age, salary, and tenure of employees?

How do job satisfaction ratings vary across job roles?

Which groups need the most attention for retention strategies?

The dashboard provides a visual, interactive, and actionable summary of employee trends.

🖼️ Dashboard Preview

(Replace the placeholder with your GitHub image path)

📌 Key Insights (Executive Summary)
💼 Overall Workforce Profile

Total Employees: 1470

Total Attrition: 237

Attrition Rate: 16.1%

Average Age: 36.9 years

Average Salary: 6.5K

Average Years at Company: 7 years

🔥 Attrition Analysis
1️⃣ Attrition by Age Group

Highest attrition occurs among 26–35 years (116 employees).

Lowest attrition in the 55+ age group (8 employees).

Younger to mid-career employees show a higher turnover tendency.

2️⃣ Attrition by Education

Life Sciences, Medical, and Marketing fields represent majority of attrition.

Employees with Technical degrees show relatively lower attrition.

3️⃣ Attrition by Job Role

Laboratory Technicians, Sales Executives, and Research Scientists show high attrition.

HR Employees have the lowest attrition numbers.

4️⃣ Attrition by Years at Company

Sharp attrition peak at around 1–2 years, indicating lack of early engagement.

Attrition decreases after 4–5 years of service.

5️⃣ Attrition by Salary Slab

Employees earning under 5K show extremely high attrition.

Higher salary brackets show significantly lower turnover.

👥 Demographic Insights

Male employees show higher attrition than female employees.

Job roles with lower satisfaction scores correspond to higher attrition.

🛠️ Tools & Technologies Used

Power BI Desktop

DAX (Data Analysis Expressions)

Excel / CSV dataset

Power Query for data cleaning

📂 Project Files Included

HR_Analytics.pbix – Power BI dashboard

dataset.csv – Raw employee dataset

README.md – Project documentation

Dashboard screenshot(s)

📈 Key DAX Measures Used
AttritionCount = SUM('HR Data'[AttritionCount])

EmployeeCount = COUNTROWS('HR Data')

Attrition Rate % =
DIVIDE([AttritionCount], [EmployeeCount], 0)

🔍 What You Can Learn From This Project

Building professional dashboards in Power BI

Using DAX to calculate business metrics

Cleaning HR datasets

Creating interactive visuals (slicers, matrices, donut charts, etc.)

HR domain understanding (attrition, job satisfaction, demographics)

📎 Future Enhancements

Predictive attrition model (Machine Learning)

Adding drill-down pages

Integration with live HRMS data

Employee performance scorecards
