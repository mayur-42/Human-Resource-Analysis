# Human-Resource-Analysis
Human Resource Analysis using Power BI

## Overview

This project provides an in-depth analysis of employee data using a Power BI dashboard and a dataset. The dashboard includes various insights, such as employee demographics, service years, age group distribution, performance ratings, and more. The aim is to help HR departments make data-driven decisions.

---

## Data Story: HR Insights Through Visualizations

Using the Power BI dashboard, we can explore key insights that tell the story of workforce dynamics and employee performance.

### 1. **Total Employees Overview**
   - **Total Employees**: 8,950 employees are represented in the dataset.
   - **Gender Distribution**:
     - Male: 4,801 employees (54%)
     - Female: 4,149 employees (46%)
   - **Actionable Insights**:
     - Gender balance is close to equal, but departments with gender disparities could be analyzed further.

---

### 2. **Service Years Analysis**
   - The horizontal bar chart categorizes employees based on years of service:
     - Most employees have 0–7 years of service.
     - Peaks are observed at 1 year (1,344 employees) and 2 years (1,205 employees).
   - **Actionable Insights**:
     - High turnover in early years suggests the need for stronger retention strategies.
     - Departments with longer service employees could serve as models for improving retention.

---

### 3. **Performance Rating and Termination Trends**
   - Line chart highlights terminations and hires by performance rating:
     - Employees with “Good” ratings have the highest hire and termination counts.
     - Those needing “Improvement” are significantly fewer in both hires and terminations.
   - **Actionable Insights**:
     - Focus on converting “Satisfactory” performers to “Good” by targeted training.
     - Employees with “Needs Improvement” ratings may require further coaching.

---

### 4. **Employee Age Group Distribution**
   - Age groups are visualized in a bar chart:
     - Largest group: 35–44 years (2,762 employees).
     - Young employees (18–24 years) are the smallest group, at 795 employees.
   - **Actionable Insights**:
     - Target younger talent pools to ensure long-term workforce sustainability.
     - Explore retention programs for employees in the 25–44 age range.

---

### 5. **Employee Details Table**
   - Provides granular data on individual employees, including:
     - `Employee_ID`, `Name`, `Job Title`, `City`, and `Salary`.
   - **Use Case**:
     - Ideal for HR professionals to drill down into individual profiles for salary benchmarking and performance reviews.

---

## Files Included

1. **`Human_Resource_Analysis.pbix`**: Power BI report file containing the HR dashboard visualization.

   - Visualizations include:
     - Total Employees by Gender.
     - Service Years distribution.
     - Count of Terminations and Hires by Performance Ratings.
     - Employee Age Group distribution.
     - Employee details table.

2. **`Human_Resources_Analysis.PNG`**: Screenshot of the Power BI dashboard for a quick preview.

3. **`HumanResources_Data.csv`**: Dataset used for analysis. Contains the following columns:
   - `Employee_ID`, `First Name`, `Last Name`
   - `Gender`, `State`, `City`
   - `Education Level`, `Birthdate`
   - `Hiredate`, `Termdate`
   - `Department`, `Job Title`
   - `Salary`, `Performance Rating`

---

## Dashboard Features

- **Filters**:
  - Age Group, Department, Gender, Education Level
  - Hire Date Range, Performance Rating
- **KPIs**:
  - Total Employees
  - Count of Male and Female Employees (with percentages)
- **Visualizations**:
  - Service Years: Distribution of employee tenure.
  - Count of Hires and Terminations: Trends by performance ratings.
  - Employee Age Groups: Breakdown by age range.
  - Detailed Employee Table: Key employee information.

---

## Getting Started

### Prerequisites
- Power BI Desktop: To open and explore the `Human_Resource_Analysis.pbix` file.
- Text Editor/Excel: To view and edit `HumanResources_Data.csv` if needed.

### Steps
1. Clone the repository or download the files.
2. Open `Human_Resource_Analysis.pbix` in Power BI Desktop.
3. Use `HumanResources_Data.csv` to update or modify the dataset.
4. Refer to `Human_Resources_Analysis.PNG` for a snapshot of the dashboard.

---

## Use Cases
- Monitor employee performance and trends.
- Analyze hiring and termination patterns.
- Understand workforce demographics.
- Identify areas requiring performance improvement.

---
