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

# Most Important Deliverables 
### A list of retiring employees and their title (90,398)
![retirees](https://github.com/dgeroux/MPLN_SQL_Demo/blob/main/Images/unique_titles.png)
### The number of retiring employees per title
![retirees_per_title](https://github.com/dgeroux/MPLN_SQL_Demo/blob/main/Images/retiring_titles.png)
### A list of employees eligible for the mentorship program (1,549)
![mentorship_program](https://github.com/dgeroux/MPLN_SQL_Demo/blob/main/Images/mentorship_eligibility.png)

# Summary
To determine how many roles will need to be filled as the "silver tsunami" begins to make an impact, we can create a table to categorize the retirees into age groups. The company can hire (internally or externally) the amount of people that would be retiring, assuming that the retirement age is 65. Currently, we have a list of people who were born between 1952 and 1955. Therefore, we would have a different hiring quota for each of the following four years.

If we look at the current projection of potential mentors and the amount of people retiring, we do not have enough retirees to mentor the next generation of employees. Moving forward, we can create a query that gives us a list of people who are retiring at the end of the current year (and for each following year). From there, the company can prioritize how many younger employees need to be trained to fill up the retired positions. It would also be beneficial if we created a query that grouped mentor-eligible employees into position titles. With this table, the company can plan the mentorship program, specifically, how many mentees a mentor can take on to fulfill the retired roles. 
