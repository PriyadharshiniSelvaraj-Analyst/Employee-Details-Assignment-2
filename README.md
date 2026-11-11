# SQL Assignment: Employee Database Analysis

This repository contains a structured SQL assignment script showcasing relational database management, data manipulation, and advanced querying techniques using MySQL.

## 📂 Dataset Structure
The database consists of three core related tables:
1. **`department`**: Stores department IDs and names (e.g., Software Development, Data Science, Finance).
2. **`location`**: Stores office city locations (Chennai, Bangalore, Hyderabad, Pune).
3. **`employee`**: Stores comprehensive employee records including personal details (`employee_id`, `employee_name`, `gender`, `age`), professional details (`designation`, `hire_date`, `salary`), and foreign keys (`department_id`, `location_id`).

---

## 🛠️ Concepts & Operations Covered
The script demonstrates mastery of the following SQL concepts:
* **Data Manipulation Language (DML):** `INSERT` and `UPDATE` statements (including handling `NULL` values).
* **Data Filtering & Sorting:** `DISTINCT`, `WHERE`, `AND`/`OR` conditions, and `ORDER BY` (ascending/descending multi-column sorting).
* **Limiting Results:** Using the `LIMIT` clause with date range filters (`BETWEEN`).
* **Aggregate Functions:** `SUM`, `MAX`, `AVG`, and `COUNT`.
* **Grouping & Filtering Groups:** `GROUP BY` paired with `HAVING` clauses for conditional aggregate filtering.
* **Table Joins:** Implementing `INNER JOIN`, `LEFT JOIN`, and `RIGHT JOIN` to query across related entities.

---

## 🚀 Sample Queries Included
* Filtering salaries and hire dates with conditional logic.
* Updating missing designations.
* Finding total department salaries and maximum ages.
* Calculating maximum salaries per location and average salaries for specific designations (e.g., analysts).
* Counting employees per department and filtering using `HAVING`.
* Combining data across employee, department, and location tables using various SQL joins.

---
