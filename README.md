# 📊 Pewlett Hackard Employee Database Reconstruction & Analysis (SQL)
## 🧭 Business Problem

  Pewlett Hackard’s legacy employee database from the 1980s–1990s was no longer stored in a structured system. Instead, historical HR data existed as six disconnected CSV files containing employee, department, title, salary, and assignment information.

  The goal of this project was to reconstruct a relational database from raw files and use SQL to analyze workforce structure, hiring trends, and department composition.

  This project simulates a real-world HR analytics scenario where organizations must rebuild or modernize legacy data systems to enable reporting and decision-making.

## 🧱 Data Approach

This project followed a full end-to-end SQL workflow:

  1. Data Modeling
    - Inspected raw CSV files
    - Designed an Entity Relationship Diagram (ERD)
    - Defined relationships between employees, departments, salaries, titles, and department assignments
    - Identified primary and composite keys to ensure data integrity
  2. Data Engineering
    - Built a relational database using PostgreSQL
    - Created normalized table schemas for six datasets
    - Defined primary keys, foreign keys, and constraints
    - Ensured correct table creation order for referential integrity
    - Imported CSV data into structured SQL tables
  3. Data Analysis
    - Wrote SQL queries using joins, aggregations, filtering, and grouping
    - Transformed raw employee data into structured workforce insights

## 📊 Key Analysis Performed

The following business questions were answered using SQL:

  - Employee salary distribution across the organization
  - Employees hired during specific time periods (e.g., 1986 cohort)
  - Department manager assignments by department
  - Employee-to-department relationships across the company
  - Employees working in Sales and Development departments
  - Frequency distribution of employee last names

## 💡 Key Insights (Example – Customize if you want stronger impact)

  - The dataset shows a highly structured departmental workforce with clear separation of roles and reporting lines.
  - Multiple departments share overlapping talent pools, indicating cross-functional staffing patterns.
  - Certain last names appear at unusually high frequency, suggesting possible data duplication patterns or generational hiring clusters.
  - Historical hiring patterns (1980s–1990s) can be used to simulate retirement wave analysis and succession planning.

## 🛠️ Tools & Skills

  - SQL (PostgreSQL)
  - Data modeling (ERD design)
  - Database schema design
  - Relational database normalization
  - Joins (INNER, LEFT)
  - Aggregations (GROUP BY, COUNT)
  - Data cleaning and validation
  - Analytical thinking and business interpretation

## 📌 Business Value

  - This project demonstrates how raw, disconnected datasets can be transformed into a structured relational database capable of supporting business intelligence and workforce analysis.

The workflow mirrors real-world data engineering tasks:

rebuilding legacy systems
enabling HR reporting
supporting workforce planning and organizational analysis
