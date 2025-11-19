# 📊 HR Analytics Dashboard

A comprehensive Power BI HR Analytics Dashboard designed to unlock actionable workforce insights—identifying patterns in attrition, job satisfaction, employee demographics, salary distributions, and tenure trends.

This dashboard empowers HR teams to make data-driven decisions, enhance employee retention, and optimize organizational performance.

---

## 🚀 Project Overview

This project analyzes employee data to address key HR questions:

- **Attrition Rate:** What is the company’s employee turnover rate?
- **Group Analysis:** Which age groups, job roles, and education fields show the highest attrition?
- **Employee Profile:** What are the average age, salary, and tenure statistics?
- **Job Satisfaction:** How do ratings differ across roles?
- **Retention Strategy:** Which segments need the most attention to reduce attrition?

The dashboard delivers a visual, interactive, and actionable summary of workforce dynamics.

---

## 🖼️ Dashboard Preview

> **Note:** Replace the placeholder below with an actual dashboard screenshot.
>
> ![Dashboard Screenshot](path/to/dashboard-image.png)

---

## 📌 Executive Summary: Key Insights

### 💼 Workforce Profile

- **Total Employees:** 1470
- **Total Attrition:** 237
- **Attrition Rate:** 16.1%
- **Average Age:** 36.9 years
- **Average Salary:** 6.5K
- **Average Tenure:** 7 years

### 🔥 Attrition Analysis

**1️⃣ Attrition by Age Group**
- Highest attrition: 26–35 years (116 employees)
- Lowest attrition: 55+ years (8 employees)
- Younger/mid-career employees are more likely to leave

**2️⃣ Attrition by Education**
- Life Sciences, Medical, and Marketing fields drive majority of attrition
- Technical degrees see lower attrition

**3️⃣ Attrition by Job Role**
- High attrition: Laboratory Technicians, Sales Executives, Research Scientists
- Lowest attrition: HR Employees

**4️⃣ Attrition by Tenure**
- Highest attrition: 1–2 years at company (early disengagement risk)
- Decline in attrition after 4–5 years

**5️⃣ Attrition by Salary Slab**
- Employees earning under 5K show extremely high attrition
- Higher salary brackets experience lower turnover

### 👥 Demographic Insights

- **Gender:** Male employees have higher attrition than female employees
- **Job Satisfaction:** Roles with lower satisfaction scores show higher attrition

---

## 🛠️ Tools & Technologies Used

- **Power BI Desktop**: Interactive dashboards
- **DAX (Data Analysis Expressions)**: Calculated business metrics
- **Excel / CSV Dataset**: Data source
- **Power Query**: Data cleaning

---

## 📂 Project Files

- `HR_Analytics.pbix` — Power BI dashboard file
- `dataset.csv` — Employee dataset
- `README.md` — Project documentation
- Dashboard screenshot(s)
- Executive Summary

---

## 📈 Key DAX Measures

```DAX
AttritionCount = SUM('HR Data'[AttritionCount])
EmployeeCount = COUNTROWS('HR Data')
Attrition Rate % = DIVIDE([AttritionCount], [EmployeeCount], 0)
```

---

## 🔍 What You'll Learn

- How to build professional dashboards in Power BI
- Using DAX for business calculations
- Cleaning and structuring HR datasets
- Creating interactive visuals (slicers, matrices, donut charts, etc.)
- Gaining HR domain understanding (attrition, job satisfaction, demographics)

---

## 📎 Future Enhancements

- Predictive attrition model (Machine Learning)
- Drill-down analytics pages
- Integration with live HRMS data
- Employee performance scorecards

---
