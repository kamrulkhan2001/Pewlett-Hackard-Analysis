Pewlett Hackard Analysis*

1. Overview of the Pewlett Hackard Analysis
An HR analyst for Pewlett Hackard has been tasked with determining which employees will be retiring in the next few years and subsequently, how many positions will need to be filled.  

As the number of baby boomers are ready to retire are growing, we want to ensure that Pewlett Hackard is well on its way to begin its mentorship program.

We will assist the analyst identify the number of retiring employees by title, employees eligible for the mentorship program, and determine how well prepared the company is for the mas exodues of baby boomers.

2. Pewlett Hackard Results
Number of Retiring Employees by Title
-We  created an overall retirment table showing those born between 1952 and 1955, a second table from the first table data using the *DISTINCT ON* funtion to find unique values and we wrote a query to COUNT the employee number and GROUP BY title to get the number by title.

3. Pewlett Hackard Summary
- 90,398 roles will need to be filled.  
- Instead of manually adding up the "count" column in the retiring_titles table, we can run a simple query to sum up the count column.

The analysis shows that there are not enough qualified, retirement-ready employees in each department to mentor the next generation.

However, the current mentorship table showed the eligible employees to those born in the year 1965.  We should change this to include all employees who were born between 1956 and 1965.  new combined table showing retiring titles vs the expanded mentorship eligible titles, we now have more than enough employees who qualify for the mentorship program to prepare the next generation of employees at Pewlett Hackard. 
