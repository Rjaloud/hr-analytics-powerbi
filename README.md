# HR Analytics Dashboard | Power BI

## Project Overview

This project presents an **HR Analytics Dashboard** developed using Microsoft Power BI to analyze workforce data and provide clear insights into employee demographics, workforce structure, compensation, performance, and employee movements.

The dashboard is based on data as of **August 8, 2026**. All dashboard figures represent the workforce situation as of this reporting date.

---

## Dashboard Structure

The dashboard consists of two main pages:

* **Workforce Overview** — provides an overview of the current workforce.
* **Movement & Attrition** — analyzes who joined, who left, and the reasons behind employee exits.

---

# 01 — Workforce Overview

![Workforce Overview](images/workforce-overview.png)

The Workforce Overview page provides a snapshot of the current workforce, including headcount, tenure, payroll, Saudization, salary, demographics, departmental distribution, age, and performance.

### Key KPIs

* **Active Headcount:** 165 employees
* **Average Tenure:** 3.1 years
* **Monthly Payroll:** SAR 1.60M
* **Saudization Rate:** 15.2%
* **Average Active Salary:** SAR 9,708

### Nationality & Gender Distribution

The dashboard shows:

* 140 non-Saudi employees and 25 Saudi employees.
* 85 female employees and 80 male employees.

### Active Headcount by Department

Finance has the highest active headcount with **25 employees**, while HR has the lowest with **10 employees**.

### Average Salary by Department

Marketing and Housekeeping have the highest average monthly salary at **SAR 10.9K**, while F&B has the lowest at **SAR 8.3K**.

### Age Distribution

The largest age group is **30–39**, with 48 employees. There are 4 employees aged 60 or above.

### Performance & Average Salary

The highest performance score, **5**, has the largest number of employees at 53. The average salary remains relatively similar across the performance scores.

---

# 02 — Movement & Attrition

![Movement & Attrition](images/movement-attrition.png)

This page focuses on employee movements, turnover, resignations, hiring trends, termination reasons, and departmental attrition.

### Key KPIs

* **Turnover Rate R12M:** 6.5%
* **Voluntary Turnover:** 2.0%
* **Total Leavers:** 35
* **Average Tenure at Exit:** 1.53 years
* **Performance Exit:** 51.4%

### Leavers by Nationality & Gender

Among employees who left:

* 26 were non-Saudi and 9 were Saudi.
* 18 were male and 17 were female.

### Hiring Trend

Hiring was highest in **2020**, with 35 hires. The 2026 figure is lower because the year is not yet complete.

### Resignation Trend

The number of resignations increased over time, reaching its highest point in **2025 with 10 employees**.

### Turnover Rate by Year

The annual turnover rate generally remained between 5% and 7%. The 2026 value of 3.8% represents only part of the year.

### Termination Reasons

Performance is the largest recorded termination reason, accounting for **18 employees**. Resignation accounts for 6 employees, while personal reasons account for 4.

### Cumulative Attrition by Department

HR has the highest cumulative attrition rate at **33.3%**, while F&B has the lowest at **4.2%**.

---

# Data Quality Findings

As part of the analysis, the underlying HR data was reviewed for inconsistencies.

Two issues were identified:

### 1. Status vs. Report Date

One employee is marked as **"Resigned"**, while the End of Contract Date is **January 15, 2029**.

Since this date is after the reporting date of August 8, 2026, the employee is counted as Active according to the dashboard rule.

### 2. Promotion After Resignation

Three employees have a **Promotion Date after their Resignation Date**, which requires validation because a promotion should not occur after an employee has left the company.

---

# Tools & Skills

* Microsoft Power BI
* Data Analysis
* Data Visualization
* HR Analytics
* Workforce Analytics
* Data Quality Review
* KPI Development
* Dashboard Design

---

## Project Highlights

This project demonstrates the use of Power BI to:

* Analyze workforce structure and employee demographics.
* Track employee movements and attrition.
* Build HR KPIs and interactive visualizations.
* Identify patterns across departments.
* Review data quality and identify inconsistencies requiring validation.
