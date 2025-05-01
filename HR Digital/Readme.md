# HR Digital Data Report Dashboard

This project provides a detailed view and analysis of employee benefit plans including medical, dental, vision, and other related options. The data is presented through a series of visual reports and tables for easier filtering and decision-making.

## 📊 Overview

The dashboard includes data on:
- Employee benefit plans by type (e.g., Medical, Dental, Vision)
- Employee classifications (e.g., Full-time, Part-time)
- Plan elections and enrollment data
- Plan cost details (Employee and Employer contributions)

The tabs allow users to drill down into specific aspects of the benefits data.

## 📁 Tabs Overview

| Tab Name                      | Description                                                                  |
|-------------------------------|------------------------------------------------------------------------------|
| `Home`                        | Overview dashboard with a high-level summary of key metrics                  |
| `Long-Term Employee`          | Breakdown of employees with long tenure, categorized by department or role  |
| `Digital Transformation Source` | Insights on where digital transformation data originates (e.g., systems/tools) |
| `Employee Count`              | Total employee counts with possible segmentation by department, role, etc.  |
| `Digital Training Hour`       | Total hours spent by employees on digital training initiatives              |
| `plan_data.csv`               | The raw data file powering the dashboards                                   |

## 📊 Data Description

The `plan_data.csv` file likely contains the following columns:

| Column Name              | Description                                          |
|--------------------------|------------------------------------------------------|
| Employee ID              | Unique identifier for each employee                  |
| Employee Name            | Name of the employee                                 |
| Department               | Department/Team they belong to                       |
| Tenure                   | Length of time the employee has been with company    |
| Role                     | Employee’s job title or classification               |
| Training Hours           | Digital training hours completed                     |
| Data Source              | Source of digital transformation data                |
| Employment Status        | Active, Resigned, Terminated, etc.                   |
