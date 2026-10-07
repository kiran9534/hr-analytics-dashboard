# HR Analytics Dashboard

## Overview

This project is a Power BI dashboard designed to give an HR team a simple view of employee headcount, employee status, salary, attendance, and performance.

The dashboard was built around three related datasets:
- Employees
- Attendance
- Performance

## Business questions

- How many employees are there?
- How many employees are active and how many have resigned?
- How many employees are in each department?
- What is the average salary?
- Which department has the highest average salary?
- What is the employee distribution by gender and age group?
- What is the overall attendance percentage?
- How does average performance vary by department?
- Is training time related to performance score?

## Dataset

The project contains:
- 300 employee records
- 1,800 attendance records
- 300 performance records

The datasets are connected through `Employee_ID`.

## Tools

- Power BI
- Excel

## Dashboard design

The dashboard requirements call for:
- KPI cards for total employees, active employees, average salary, and attendance
- Slicers for department, gender, age group, status, and job role
- Employee count by department
- Employee status distribution
- Average salary by department
- Employees by age group
- Average performance by department
- Training hours vs. performance score

## Key findings from the project data

- Total employees: 300
- Active employees: 266
- Resigned employees: 34
- Average salary: approximately ₹72,825
- Overall attendance: approximately 88.8%
- IT has the highest average salary among the departments in the supplied employee data.

The supplied performance data can also be joined to employee department information through `Employee_ID`, allowing department-level performance analysis.

## Files

- `hr-analytics-dashboard.pbix` — Power BI report
- `data/HR_Analytics_Dataset.xlsx` — source data
- `docs/hr_dashboard_requirements.docx` — dashboard requirements used for the project

## Portfolio takeaway

This project demonstrates how I use Power BI to turn employee-level data into a dashboard that an HR team could use for quick workforce and performance analysis.
