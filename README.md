### Module-7-Challenge
SQL/Pgadmin

## 1) Overview of the analysis:  
To determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. A report is summarized based on the analysis.

      Resources:
      Data Source: departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv
      Software: Postgres, pgAdmin
    
## 2) Results: 

a) Retirement_titles:  
<img width="717" alt="Screen Shot 2021-11-25 at 2 03 32 PM" src="https://user-images.githubusercontent.com/91294352/143491133-9bea4436-519d-40cb-ac06-f1ffa41c6ce0.png">

b) Unique_titles:

<img width="461" alt="Screen Shot 2021-11-25 at 2 06 20 PM" src="https://user-images.githubusercontent.com/91294352/143491300-2829883c-efbf-4016-994c-8a960816e76c.png">

c) Retiring_titles:

<img width="218" alt="Screen Shot 2021-11-25 at 2 08 16 PM" src="https://user-images.githubusercontent.com/91294352/143491449-959e64a0-0db2-4e11-a205-8ccfc386337f.png">

d) Mentorship_eligibility:

<img width="712" alt="Screen Shot 2021-11-25 at 2 09 35 PM" src="https://user-images.githubusercontent.com/91294352/143491566-f52ba61e-956a-4806-b2d8-458e32f8003f.png">

## 2) Results: 

** Based on the criteria given for employees born in 1965 and 1955, we can run a SELECT COUNT statement to get the number of retirees by title. The Result is 90,398.

<img width="331" alt="Screen Shot 2021-11-25 at 3 08 53 PM" src="https://user-images.githubusercontent.com/91294352/143496331-d76ea786-0315-4287-95b3-909d479d07ab.png">


** Based on the criteria given for employees born in 1965 and have current roles - From the mentorship program table we can run a SELECT COUNT statement to get the number of employees that are available for the mentorship role. The Result is 1,549.

<img width="328" alt="Screen Shot 2021-11-25 at 2 54 47 PM" src="https://user-images.githubusercontent.com/91294352/143495231-5dfc61c3-9adc-4505-9350-a0253ab53e17.png">

** How many roles will need to be filled as the "silver tsunami" begins to make an impact?

<img width="351" alt="Screen Shot 2021-11-28 at 11 41 12 AM" src="https://user-images.githubusercontent.com/91294352/143777575-0b5fad0e-6b46-4c13-85f7-bcb7b75cdb07.png">
** Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
