Here is your lab in the exact format you requested, with `../../` before each image and your wording unchanged:

---

# Lab #5(SQL): Using SQL Joins to Combine Data Across Tables

**Platform**: Google Cybersecurity Certificate
**Lab Focus**: SQL Joins (`INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`)

---

## 🧠 Overview

This lab focused on joining data from multiple tables using `INNER JOIN`, `LEFT JOIN`, and `RIGHT JOIN`. These techniques are essential for cross-referencing related datasets and retrieving complete or filtered records based on relational keys.

---

## ✅ Key Tasks and Learnings

* Used `INNER JOIN` between the `machines` and `employees` tables on `device_id`, retrieving 185 records that linked machines with employees.
  ![INNER JOIN Machines and Employees](../../images/sql_lab5_inner_join_machines_employees.png)

* Applied `LEFT JOIN` from `machines` to `employees` to find all machines and their assigned users. Machines without users showed `NULL` in the `username` column.
  ![LEFT JOIN to Find Unassigned Machines](../../images/sql_lab5_left_join_unassigned.png)

* Used `RIGHT JOIN` from `employees` to `machines` to identify employees without machines, such as `areyes`.
  ![RIGHT JOIN to Find Employees Without Machines](../../images/sql_lab5_right_join_employees.png)

* Performed `INNER JOIN` between `employees` and `log_in_attempts` on `username` to retrieve 200 login records and trace user activity.
  ![INNER JOIN on Login Attempts](../../images/sql_lab5_inner_join_login_attempts.png)

---

## 💻 Skills Demonstrated

* Used `INNER JOIN` to retrieve matched data from two tables based on a shared column
* Applied `LEFT JOIN` to include all records from the left table (`machines`) and matched data from the right table (`employees`)
* Applied `RIGHT JOIN` to include all records from the right table (`employees`) regardless of machine assignment
* Joined tables on both string (`username`) and key (`device_id`) fields
* Identified `NULL` values as indicators of unmatched records in join operations

---

## 🔁 Reflection

This lab reinforced the core SQL skill of joining tables, a fundamental process in data analysis and database management. Mastery of JOIN operations enables deeper insights by connecting related datasets across systems.
