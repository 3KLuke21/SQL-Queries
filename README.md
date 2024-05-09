# Applying Filters to SQL Queries

### Project Description:
As part of our organization's security efforts, we utilized SQL queries with filters to investigate security incidents and update employee computers. Below are examples of tasks we performed using SQL queries with filters to address security concerns effectively.

#### Retrieve After-Hours Failed Login Attempts:
**Objective**: Investigate failed login attempts occurring after business hours (after 18:00).
- **Query**: Selected data from the `log_in_attempts` table using a WHERE clause with an AND operator to filter for attempts after 18:00 and marked as unsuccessful.

![image](https://github.com/3KLuke21/SQL-Queries/assets/50923722/1209f6f4-09e7-4368-9a43-8441903d3f7f)

#### Retrieve Login Attempts on Specific Dates:
**Objective**: Investigate login activity on specific dates, such as the day before or after a security incident.
- **Query**: Selected data from `log_in_attempts` using a WHERE clause with an OR operator to filter for attempts on specific dates, like 2022-05-09 or 2022-05-08.

![image](https://github.com/3KLuke21/SQL-Queries/assets/50923722/1fcea6a9-70f3-4a15-9fc8-7aae9a351515)


#### Retrieve Login Attempts Outside of Mexico:
**Objective**: Investigate login attempts originating from countries outside of Mexico.
- **Query**: Selected data from `log_in_attempts` using a WHERE clause with NOT to filter for countries other than Mexico, using LIKE with the pattern MEX% to match variations of "Mexico".

![image](https://github.com/3KLuke21/SQL-Queries/assets/50923722/371b5849-4ab0-4e36-bc8e-a19f974ddc84)


#### Retrieve Employees in Marketing:
**Objective**: Identify machines used by employees in the Marketing department located in the East building.
- **Query**: Selected data from the `employees` table using a WHERE clause with AND to filter for employees in Marketing and in the East building.

![image](https://github.com/3KLuke21/SQL-Queries/assets/50923722/a07fbf3a-33b5-4b99-b654-83c834e24d44)


#### Retrieve Employees in Finance or Sales:
**Objective**: Identify machines used by employees in the Finance or Sales departments for security updates.
- **Query**: Selected data from `employees` using a WHERE clause with OR to filter for employees in either the Finance or Sales departments.

![image](https://github.com/3KLuke21/SQL-Queries/assets/50923722/fd8b41b4-9fca-4ff9-aa8f-617ee83bff07)


#### Retrieve All Employees Not in IT:
**Objective**: Identify machines used by employees not in the IT department for an additional security update.
- **Query**: Selected data from `employees` using a WHERE clause with NOT to filter for employees not in the IT department.

![image](https://github.com/3KLuke21/SQL-Queries/assets/50923722/b9085fab-417b-4843-9860-9a6e490742fc)

### Summary:
In summary, we effectively applied filters to SQL queries to gather specific information on login attempts and employee machines. By leveraging operators like AND, OR, and NOT, along with wildcard patterns like LIKE, we efficiently addressed various security tasks. These examples showcase the practical application of SQL queries in security investigations and updates.
