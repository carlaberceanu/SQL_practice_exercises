# SQL_practice_exercises

This repository contains my solutions to SQL questions solved on [sql-practice.com](https://www.sql-practice.com). The queries provided here demonstrate the skills I've developed in extracting, filtering, aggregating, and analyzing data across multiple tables.

## Database Schema Overview

I queried data from the following four tables:

### 1. **patients**
- `patient_id`, `first_name`, `last_name`, `gender`, `birth_date`, `height`, `weight`, `allergies`, `province_id`, `city`

### 2. **doctors**
- `doctor_id`, `first_name`, `last_name`, `specialty`

### 3. **admissions**
- `patient_id`, `admission_date`, `discharge_date`, `diagnosis`, `attending_doctor_id`

### 4. **province_names**
- `province_id`, `province_name`

---

## Topics and SQL Concepts Covered

These queries demonstrate my SQL proficiency in:

- **Basic data retrieval** (`SELECT`, `WHERE`, `LIKE`, `BETWEEN`)
- **Conditional logic** (`CASE`, handling `NULL` values)
- **Data aggregation** (`GROUP BY`, `HAVING`, `COUNT()`, `SUM()`, `AVG()`, `MAX()`, `MIN()`)
- **Table relationships** (`INNER JOIN`, joining multiple tables)
- **String manipulation** (`CONCAT`, `UPPER`, `LOWER`)
- **Date and time functions** (`YEAR`, `MONTH`, `DAY`)
- **Window functions** (`LAG()`, `OVER()`)
- **Filtering with complex conditions** (`AND`, `OR`, `IN`, nested queries)
- **Custom sorting** (`ORDER BY`, conditional ordering with `CASE`)

---

## Sample Questions Solved

Here are some examples of questions I've answered, categorized by difficulty:

### 🔹 Easy
- Show first and last names of patients without allergies (`NULL` values).
- Update patient allergies from `NULL` to `'NKA'`.

### 🔸 Medium
- Find the patient with the greatest height.
- List patients admitted multiple times for the same diagnosis.
- Count patients per city and province.
- Display patient names in various custom formats.

### 🔺 Hard
- Calculate the percentage of male patients.
- Determine obesity status (`boolean`) using BMI calculations.
- Generate temporary passwords using patient-specific data.
- Analyze daily admissions with changes from the previous day (`LAG()`).

---

## Usage
The solutions included here are useful as reference material for anyone looking to improve their SQL skills, particularly in the context of healthcare data analysis. You can directly explore or reuse queries tailored to specific analytical tasks and database structures.

---

## Explore the Notebook
All solutions are neatly organized and readable in the provided Jupyter Notebook [`SQL_Practice_Solutions.ipynb`](SQL_Practice_Solutions.ipynb). Feel free to explore, comment, or contact me if you have questions or suggestions.

---

## Source and Acknowledgment

All questions and datasets were sourced from the interactive SQL learning platform:

[sql-practice.com](https://www.sql-practice.com)
