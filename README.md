# HR Analytics Dashboard | Power BI

An interactive Human Resources analytics project built with **Power BI** to explore workforce composition, employee turnover, salary patterns, performance, engagement, and demographics.

> **Portfolio project:** This repository demonstrates a BI reporting workflow using a public HR sample dataset. The figures below describe the dataset represented in this report and should not be interpreted as findings about a real employer.

## Dashboard Preview

### 1. Global HR Dashboard
![Global HR Dashboard](screenshots/Screenshot%202026-10-12%20061816.png)

Highlights: total workforce, active employee rate, turnover rate, average salary by department, employee distribution by department, and gender split.

### 2. Turnover & Retention Analysis
![Turnover and Retention Analysis](screenshots/Screenshot%202026-10-12%20061842.png)

Highlights: terminated employees by department and gender, average salary of leavers, average tenure of terminated employees, and terminations by year.

### 3. Performance & Salary Analysis
![Performance and Salary Analysis](screenshots/Screenshot%202026-10-12%20061903.png)

Highlights: average salary, performance rating, high-performance share, satisfaction, salary distribution, and engagement versus salary.

### 4. Diversity & Demographics Analysis
![Diversity and Demographics Analysis](screenshots/Screenshot%202026-10-12%20061939.png)

Highlights: gender distribution, age groups, average age and tenure, employee positions, and department-level demographics.

## Business Questions

- How is the workforce distributed across departments, gender, age groups, and positions?
- Which departments account for the largest number of employees and terminations?
- What do the available data indicate about salary distribution and differences between departments?
- How do performance ratings, satisfaction, and engagement appear alongside salary?
- How does the recorded termination count vary across years?

## Key Metrics Shown

The report includes measures such as total employees, terminated employees, active employee rate, turnover rate, average salary, average tenure, average performance rating, and average satisfaction.

Some displayed values are report-specific calculations. Check the Power BI model and measures for exact definitions before comparing them with other HR reports.

## Tools & Skills

- **Power BI Desktop** — report development and interactive visualizations
- **Power Query** — data import and transformation
- **DAX** — KPI and measure calculations
- **Data visualization** — KPI cards, bar charts, line charts, donut charts, and scatter plots
- **HR analytics** — workforce composition, compensation, performance, and attrition analysis

## Repository Structure

    hr-analytics-dashboard/
    ├── data/
    │   ├── raw/       # Original sample dataset
    │   └── cleaned/   # Prepared dataset used in the analysis
    ├── dashboard/
    │   └── HR Project.pbix
    ├── screenshots/   # Dashboard page previews
    └── README.md

## Open the Report

Download [HR Project.pbix](dashboard/HR%20Project.pbix) and open it in **Power BI Desktop**. If Power BI requests a data source location, update the source path to the CSV in data/cleaned/ or to your local copy, then refresh the model.

- [Raw dataset](data/raw/HRDataset_v14.csv)
- [Cleaned dataset](data/cleaned/HRDataset_v14.csv)
- [Power BI report](dashboard/HR%20Project.pbix)
- [Dashboard screenshots](screenshots/)

## Data Notes & Limitations

- The repository contains raw and cleaned CSV versions; transformations should be documented based on the steps actually performed in Power Query or other tools.
- This README does not claim that specific missing-value, duplicate-removal, or outlier-handling rules were applied unless those steps are documented in the project.
- HR data can be sensitive. The dataset and report should contain only sample or anonymized data that you are authorized to publish.
- Metrics depend on the dataset definitions and the DAX logic used in the report. Review the model before using the numbers for real business decisions.

## Author

**Marouane Boulifa** — Data & Business Intelligence portfolio project.

- [GitHub profile](https://github.com/Marouane-BLF)
