# Graduate Employment Trends in Singapore (2018–2023)

## Project Overview
This project analyzes graduate employment and salary trends across major Singapore universities over a 5-year period (2018–2023).  
Using the **Ministry of Education’s Graduate Employment Survey (GES)** data, the goal is to identify which fields of study demonstrate the strongest employability, salary growth, and post-pandemic recovery patterns.

The analysis supports students, educators, and policymakers in understanding how graduate outcomes evolve across time and disciplines.

---

## Objectives
- Examine **full-time permanent employment rates** and **median starting salaries** by degree and university.  
- Identify fields with the **highest salary growth** and **most stable employability** over 5 years.  
- Visualize employment trends before and after the COVID-19 period.  
- Build an **interactive Power BI dashboard** for dynamic exploration of results.

---

## Tools and Technologies
| Category | Tools |
|-----------|--------|
| Data Cleaning | Microsoft Excel |
| Data Modeling & Visualization | Power BI |
| Data Source | Singapore MOE – Graduate Employment Survey (GES) |
| Supporting Analysis | Power Query, DAX Expressions |

---

## Data Source
Data was obtained from the official  
[Singapore Ministry of Education – Graduate Employment Survey (GES)](https://www.data.gov.sg/datasets/d_3c55210de27fcccda2ed0c63fdd2b352/view)

Each dataset includes:
- University name  
- Degree programme  
- Employment rate (overall and full-time)  
- Median gross monthly salary  

Years covered: **2018–2023**

---

## Data Preparation
1. **Data Collection** – Downloaded yearly Excel sheets (2018–2023) from MOE’s website.  
2. **Standardization** – Renamed inconsistent columns and standardized degree names.  
3. **Data Integration** – Combined all yearly tables using Power Query (Append Queries).  
4. **Data Cleaning** –  
   - Removed blank rows and duplicates  
   - Converted text to numeric values for employment rates and salary  
5. **Feature Engineering** – Added “Year” column and calculated year-over-year salary growth.

---

## Dashboard Design

**Page 1 – Overview**
- KPIs: Average Employment Rate (%), Median Salary ($), Number of Universities  
- Line chart: Employment rate trend over time  
- Bar chart: Median salary by university  

**Page 2 – Degree Breakdown**
- Bar chart: Top 10 degrees by salary  
- Line chart: Employment rate trend (2018–2023)  
- Scatter plot: Salary vs Employment Rate (by degree)  
- Filters: Year, University, Degree Category  

---

## Key Insights
1. **Overall Employment Stability** – Despite pandemic disruptions in 2020, full-time employment rebounded strongly by 2023.  
2. **Salary Growth** – IT and Engineering degrees experienced the largest median salary increase (~25%).  
3. **Consistent Employability** – Education and Nursing programmes maintained above-average employment rates (>95%).  
4. **University Comparison** – NUS and SMU reported the highest median salaries across most disciplines.

---

## Sample Visuals
*(Add your dashboard screenshots here once available)*

```markdown
![Dashboard Overview](visuals/overview.png)
![Degree Trends](visuals/degree_trends.png)
