# 🗄️ Database Practical Assignment / Практическое задание по базам данных

---

## 📘 Project Overview

This project is a practical database assignment designed to demonstrate basic SQL query skills.  
The goal is to create a database named `firm` with a table `employees` and perform several SQL queries to retrieve, filter, and display data based on given conditions.

### **Русская версия**

Этот проект — практическое задание по базам данных, созданное для демонстрации базовых навыков работы с SQL-запросами.  
Цель — создать базу данных `firm` с таблицей `employees` и выполнить несколько SQL-запросов для выборки, фильтрации и отображения данных по заданным условиям.

---

## 🧠 What I learned

- How to create a new database and table in SQL.
- How to use `SELECT`, `WHERE`, and comparison operators.
- How to filter data by conditions such as department, position, and salary.
- How to apply logical conditions using `AND` and `BETWEEN`.

### **Русская версия**

- Как создать новую базу данных и таблицу в SQL.  
- Как использовать команды `SELECT`, `WHERE` и операторы сравнения.  
- Как фильтровать данные по условиям: отдел, должность, зарплата.  
- Как применять логические условия с помощью `AND` и `BETWEEN`.

---

## 🧩 Task 1: Database and Table Creation

### **Goal**
Create a database named `firm` and a table `employees` with the following fields:
- `id` — unique employee identifier  
- `first_name` — employee's first name  
- `last_name` — employee's last name  
- `position` — job title  
- `department` — department name  
- `salary` — salary amount

### **Actions performed**
1. Created a new database:
   ```sql
   CREATE DATABASE firm;
Switched to the new database:

sql
Copy code
USE firm;
Created the employees table:

sql
Copy code
CREATE TABLE employees (
    id INT PRIMARY KEY,
    first_name VARCHAR(50),
    last_name VARCHAR(50),
    position VARCHAR(50),
    department VARCHAR(50),
    salary INT
);
Русская версия
Цель
Создать базу данных с именем firm и таблицу employees со следующими полями:

id — уникальный идентификатор сотрудника

first_name — имя сотрудника

last_name — фамилия сотрудника

position — должность

department — отдел

salary — зарплата

Выполненные действия
Создана новая база данных:

sql
Copy code
CREATE DATABASE firm;
Выполнен переход к новой базе:

sql
Copy code
USE firm;
Создана таблица employees:

sql
Copy code
CREATE TABLE employees (
    id INT PRIMARY KEY,
    first_name VARCHAR(50),
    last_name VARCHAR(50),
    position VARCHAR(50),
    department VARCHAR(50),
    salary INT
);
🧩 Task 2: SQL Queries
Goal
Execute SQL queries to retrieve employee information according to specific conditions.

Actions performed
List all employees (first and last names):

sql
Copy code
SELECT first_name, last_name FROM employees;
Find all employees who work in the IT department:

sql
Copy code
SELECT * FROM employees WHERE department = 'IT';
Retrieve names of employees with position 'Manager':

sql
Copy code
SELECT first_name, last_name FROM employees WHERE position = 'Manager';
Retrieve names of employees whose salary equals 40000:

sql
Copy code
SELECT first_name, last_name FROM employees WHERE salary = 40000;
Retrieve employees with salary greater than 60000:

sql
Copy code
SELECT first_name, last_name, position FROM employees WHERE salary > 60000;
Show employees from Marketing department with salary less than 20000:

sql
Copy code
SELECT first_name, last_name FROM employees
WHERE department = 'Marketing' AND salary < 20000;
Show employee IDs whose salary is between 30000 and 50000:

sql
Copy code
SELECT id FROM employees WHERE salary BETWEEN 30000 AND 50000;
📸 Screenshots:


Русская версия
Цель
Выполнить SQL-запросы для получения информации о сотрудниках по заданным условиям.

Выполненные действия
Список всех сотрудников (имя и фамилия):

sql
Copy code
SELECT first_name, last_name FROM employees;
Найти всех сотрудников, работающих в отделе IT:

sql
Copy code
SELECT * FROM employees WHERE department = 'IT';
Получить имена сотрудников, имеющих должность 'Manager':

sql
Copy code
SELECT first_name, last_name FROM employees WHERE position = 'Manager';
Получить имена сотрудников с зарплатой 40000:

sql
Copy code
SELECT first_name, last_name FROM employees WHERE salary = 40000;
Получить сотрудников с зарплатой более 60000:

sql
Copy code
SELECT first_name, last_name, position FROM employees WHERE salary > 60000;
Показать сотрудников из отдела Marketing с зарплатой менее 20000:

sql
Copy code
SELECT first_name, last_name FROM employees
WHERE department = 'Marketing' AND salary < 20000;
Показать идентификаторы сотрудников, у которых зарплата между 30000 и 50000:

sql
Copy code
SELECT id FROM employees WHERE salary BETWEEN 30000 AND 50000;