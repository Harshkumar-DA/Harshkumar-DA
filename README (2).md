# 👥 HR Attrition & Workforce Analysis

### Exploring Workforce Trends and Employee Attrition

**MySQL · Power BI · SQL Analysis**

A business-focused HR analytics project that examines employee attrition, workforce distribution, department performance, and workplace-related factors.

---

## 📌 Project Overview

Employee attrition can affect workforce stability and organisational planning. This project uses employee-level data to explore how attrition is distributed across departments, job roles, age groups, and other workforce characteristics.

MySQL is used to answer structured HR business questions and create reusable views, while Power BI provides a four-page dashboard for visual exploration of workforce metrics and attrition patterns.

## 🎯 Business Objectives

- Understand the overall workforce size and employee attrition rate.
- Compare employees who have left with those who are still working.
- Explore attrition across departments and job roles.
- Review average monthly income by department.
- Examine attrition patterns by overtime and job satisfaction.
- Compare attrition across age groups and years at the company.
- Present HR metrics in a clear, visual dashboard.

## 🧰 Tools & Technologies

| Tool | Purpose |
|---|---|
| **MySQL** | Querying, aggregation, analysis, and SQL views |
| **Power BI** | Dashboard development and data visualisation |
| **CSV** | Dataset format and data source |

## 📊 Dataset Overview

The file **`IBM_HR-Employee-Attrition.csv`** contains **1,470 employee records and 35 columns**. It includes employee demographics, department and job information, compensation, satisfaction ratings, work-related factors, and attrition status.

### Key Dataset Fields

| Field | Description |
|---|---|
| `Age` | Employee age |
| `Attrition` | Whether the employee left the organisation |
| `Department` | Employee department |
| `JobRole` | Employee job role |
| `MonthlyIncome` | Employee monthly income |
| `OverTime` | Whether the employee works overtime |
| `JobSatisfaction` | Job satisfaction rating |
| `YearsAtCompany` | Total years at the company |
| `WorkLifeBalance` | Work-life balance rating |
| `Gender` | Employee gender |

## 🔍 SQL Analysis

The SQL script covers **12 HR business questions** across three analysis areas.

| Analysis Area | Questions Explored |
|---|---|
| **Overall HR Analysis** | Total employees, employees who left or stayed, overall attrition rate, and gender distribution |
| **Department & Job Role Analysis** | Attrition by department and job role, employee status by department, and average monthly income |
| **Employee Behaviour Analysis** | Attrition by overtime, job satisfaction, age group, and years at the company |

### SQL Concepts Applied

`SELECT` · `COUNT` · `DISTINCT` · `GROUP BY` · `ORDER BY` · Aggregate Functions · `CASE WHEN` · SQL Views

The SQL script also includes a duplicate Employee ID check and creates views to organise key analysis results.

## 📈 Power BI Dashboard

The project includes a **four-page Power BI dashboard** designed to present workforce and attrition information in a visual format.

The dashboard supports exploration of:

- Overall employee and attrition metrics.
- Department and job-role performance.
- Employee-related factors and attrition patterns.
- Age-group and workforce analysis.

**Dashboard file:** `HR ATTRITION DASHBOARD.pbix`

Open the file in **Microsoft Power BI Desktop** to explore the report and its available visuals and interactions.

## 📁 Repository Structure

```text
HR-Attrition-Workforce-Analysis/
├── HR ATTRITION DASHBOARD.pbix
├── IBM_HR_Analytics_SQL_Analysis.sql
├── IBM_HR-Employee-Attrition.csv
└── README.md
```

## 💡 Key Learning Outcomes

- Translated HR requirements into practical SQL queries.
- Used SQL views to organise reusable analysis.
- Calculated and compared employee attrition metrics.
- Explored workforce patterns across departments, roles, and employee characteristics.
- Developed a multi-page Power BI dashboard to communicate HR data.

---

<div align="center">

**Thanks for visiting this project!**

*Turning workforce data into meaningful insights.*

</div>
