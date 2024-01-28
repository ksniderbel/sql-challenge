# Pewlett Hackard Employee Analysis
For this project, we will analyze employee data for Pewlett Hackard from the 1980s and the 1990s.  Data files were received in the form of .csv files:  employees, titles, departments, salaries, dept_emp (employees by department) and dept_manager (managers by department).

Data was modeled based on observations of fields in each file and mapped to the appropriate data type, and the relationships between the different tables are mapped out using the ERD tool in PGAdmin as well as QuickDB.  The results are respectively provided in three files, employees_db.pgerd and employees_db.png from PGAdmin, and ERD.png from QuickDB.

Tables were then created with the same names as the .csv viles with primary keys and using foreign keys to indicate the relationships between the SQL tables.  This code can be found in create_tables.sql

Each .csv was imported into a table with the same name as the corresponding .csv.

Specific data sets were requested by the client as follows:
1. List the employee number, last name, first name, sex, and salary of each employee.
2. List the first name, last name, and hire date for the employees who were hired in 1986.
3. List the manager of each department along with their department number, department name, employee number, last name, and first name.
4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
6. List each employee in the Sales department, including their employee number, last name, and first name.
7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

Each of these queries is contained in the query_tables.sql.

Assistance was obtained from the Teaching Assistants and multiple sites that were obtained via Google.

Final observation:  This company employs a statistically unlikely amount of people named Hercules B.
