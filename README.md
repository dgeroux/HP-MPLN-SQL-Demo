# Pewlett-Hackard Analysis
Pewlett Hackard is a large company boasting several thousand employees and has been around for a long time. As baby boomers begin to retire at a rapid rate, Pewlett-Hackard is looking towards the future in two ways. First, it's offering retirement packages for those who meet certain criteria. Second, it's starting to think about which positions will need to be filled in the near future. The number of upcoming retirements will leave thousands of job openings.

After creating a database, importing data, and using SQL to query the database, Pewlett Hackard's HR Analyst has a few more tasks for me. He wants me to determine the number or retiring employees per title, and identify employees who are eligible to participate in a mentorship program.

# Tools
**PostgreSQL** - Relational database system (RDS) for holding data. Creates a local server on your computer.

**pgAdmin** - Interface that talks to PostgreSQL ; specifically built for PostgreSQL. It's where queries are written, executed, and where results are viewed.

**Structured Query Language (SQL)** - A programming language used to manage and manipulate relational databases. It allows users to create, modify, and query databases.

# Raw Data
[Employees](https://raw.githubusercontent.com/dgeroux/MPLN_SQL_Demo/main/Datasets/employees%20(1).csv)

[Titles](https://raw.githubusercontent.com/dgeroux/MPLN_SQL_Demo/main/Datasets/titles%20(1).csv)

[Salaries](https://raw.githubusercontent.com/dgeroux/MPLN_SQL_Demo/main/Datasets/salaries%20(1).csv)

[Departments](https://raw.githubusercontent.com/dgeroux/MPLN_SQL_Demo/main/Datasets/departments%20(2).csv)

[Department Managers](https://raw.githubusercontent.com/dgeroux/MPLN_SQL_Demo/main/Datasets/dept_manager%20(1).csv)

[Department Employees](https://raw.githubusercontent.com/dgeroux/MPLN_SQL_Demo/main/Datasets/dept_emp%20(1).csv)

# Relevant Documentation
https://www.postgresql.org/docs/

https://www.pgadmin.org/docs/

https://www.tutorialspoint.com/postgresql/

# Understanding Joins
![joins](https://github.com/dgeroux/MPLN_SQL_Demo/blob/main/Images/PostgreSQL_joins.png)

# Entity Relationship Diagram (ERD)/Schema
![ERD](https://github.com/dgeroux/MPLN_SQL_Demo/blob/main/Images/ERD_schema.png)

# Deliverables 

### Employee Information: A list of employees containing their unique employee number, their last name, first name, gender, and salary
### Management: A list of managers for each department, including the department number, name, and the manager's employee number, last name, first name, and the starting and ending employment dates
### Department Retirees: An updated current_emp list that includes everything it currently has, but also the employee's departments
