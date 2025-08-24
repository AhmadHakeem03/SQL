# Data Analyst Skills & Salary SQL Project

This project analyzes job postings for Data Analyst roles to identify the most optimal skills to learn—those that are both in high demand and associated with high-paying remote positions. The analysis uses SQL queries on provided CSV datasets.

## Project Structure

- `csv_files/`  
  Contains source data:
  - `company_dim.csv`
  - `job_postings_fact.csv`
  - `skills_dim.csv`
  - `skills_job_dim.csv`

- `sql_load/`  
  SQL scripts for database setup:
  - `1_create_database.sql` – Create database
  - `2_create_tables.sql` – Create tables
  - `3_modify_tables.sql` – Table modifications

- `sql_load/project_sql/`  
  Analytical SQL queries:
  - `optimal_skills.sql` – Finds top skills by demand and salary
  - `top_demanded_skills.sql` – Lists most demanded skills
  - `top_paying_job_skills.sql` – Skills with highest average salaries
  - `Top_paying_jobs.sql` – Highest paying jobs
  - `top_paying_skills.sql` – Highest paying skills

## Usage

1. **Load Data**  
   Use scripts in `sql_load/` to set up the database and import CSVs.

2. **Run Analysis**  
   Execute queries in `sql_load/project_sql/` to generate insights.

   Example:  
   - `optimal_skills.sql` identifies skills for Data Analyst roles that are both in high demand and offer high average salaries for remote positions.

## Insights

- Focuses on remote Data Analyst jobs with specified salaries.
- Targets skills that offer both job security and financial benefits.
- Results help guide career development in data analysis.

## Requirements

- PostgreSQL or compatible SQL database
- CSV import capability

## License

MIT License

---

*Update this README as the project evolves.*
