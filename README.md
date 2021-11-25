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

** Based on the criteria "employees born between 1952 and 1955", there are 90,396 employees who are likely to retire soon.
** Based on the criteria given for employees born in 1965 and have current roles - From the mentorship program table we can run a SELECT COUNT statement to get the number of employees that are available for the mentorship role. The Result is 1,549.


Based on the criteria given we can find retirement count by department and also count of eligible mentorship available. So, more Senior and experienced employees should be given mentorship. So, junior employees can be trained efficiently for seniority roles.
