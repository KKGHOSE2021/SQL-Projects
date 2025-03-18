In this project, different SQL window functions are used to perform data aggregation, reporting, manipulation, and querying for database insights using the projectdb database.

# Project Structure
The hands-on project on Introduction to SQL Window Functions is divided into the following tasks:

## Task 1: Getting Started
In this task, the project will get started by retrieving all the data in the project-db database

## Task 2: ROW_NUMBER() - Part One
Assign numbers to each row of the departments table

Exercise 2.1: Assign numbers to each row of the department for the Entertainment division

## Task 3: ROW_NUMBER() - Part Two
Retrieve all the data from the employees table

Retrieve a list of employee_id, first_name, hire_date, and department of all employees in the sports department ordered by the hire date

Order by multiple columns

Ordering in- and outside the OVER() clause

## Task 4: PARTITION BY
Retrieve the employee_id, first_name, hire_date of employees for different departments

Exercise 4.1: Order by the hire_date

## Task 5: PARTITION BY WITH CTE
Retrieve all data from the sales and customers tables

Create a common table expression to retrieve the customer_id, customer_name, segment, and how many times the customer has purchased from the mall

Number each customer by how many purchases they've made

Exercise 5.1: Number each customer by their customer segment and by how many purchases they've made in descending order

## Task 6: Fetching: LEAD() & LAG()
Retrieve all employees first name, department, salary, and the salary after that employee

Retrieve all employees first name, department, salary, and the salary before that employee

Retrieve all employees first name, department, salary, and the salary after that employee in order of their salaries

Exercise 6.1: Retrieve all employees first name, department, salary, and the salary before that employee in order of their salaries. Call the new column closest_higher_salary

Exercise 6.2: Retrieve all employees first name, department, salary, and the salary after that employee for each department in order of their salaries. Call the new column closest_lowest_salary

## Task 7: FIRST_VALUE() - Part One
Retrieve the first_name, last_name, department, and hire_date of all employees. Add a new column called first_emp_date that returns the hire date of the first hired employee

Find the difference between the hire date of the first employee hired and every other employees

Exercise 7.1: Partition by department

Exercise 7.2: Find the difference between the hire date of the first employee hired and every other employees partitioned by department

## Task 8: FIRST_VALUE() - Part Two
Exercise 8.1: Return the first salary for different departments, Order by the salary in descending order

Exercise 8.2: Return the first salary for different departments. Order by the first_name in ascending order

Return the fifth salary for different departments. Order by the first_name in ascending order

Wrap up the project
 
