![](https://www.bing.com/th?id=OIP.lZrXmWJRDLqIImJThs5LrwHaDZ&w=300&h=137&c=7&o=5&pid=1.7)
# PostgreSQL
# Background
In this project, tables will be designed to hold data from .csv, import the .csv files into a SQL database, and query for answers from the data in the database. (Data Modeling, Data Engieering, Data Analysis Project)

## Data Modeling
nspect the CSVs and sketch out an ERD of the tables. 

## Data Engineering
  * Use the information to create a table schema for each of the six CSV files.
  * Import each CSV file into the corresponding SQL table.


## Data Analysis

###### List the following details of each employee: employee number, last name, first name, gender, and salary.
###### List employees who were hired in 1986.
###### List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name, and start and end employment dates.
###### List the department of each employee with the following information: employee number, last name, first name, and department name.
###### List all employees whose first name is "Hercules" and last names begin with "B."
###### List all employees in the Sales department, including their employee number, last name, first name, and department name.
###### List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
###### In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.


## Instructions
Jupyter notebook folder contains jupyter notebook required for pulling data and creating plots using sqlalchemy. Please note that the password required for this notebook file has been redacted with asterisks as to not upload it to this GitHub repository.
The SQL folder contains 3 .sql files.  HWschema.sql was used to create the tables in PostgreSQL and HW Queries 2.sql was used to query the database and answer the required questions.  The QuickDBD-export(3).sql was exported after creating the ERD; however it would not run in PostgreSQL but it was only added as a reference.  
The Salaries Plot folder contains a plot of average salaries per title that was made in Jupyter notebooks.
The Screenshot folder contains a screenshot of the ERD used for this project along with a PDF report of the ERD.
The csv files folder contains the .csv files that were used to create the database as a courtesy and for convenience. 
