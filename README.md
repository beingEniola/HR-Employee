<img width="661" alt="Screenshot 2024-02-24 083902" src="https://github.com/beingEniola/HR-Employee/assets/100062989/f8e2de07-ab45-40c1-9039-78037fb987a5">

## DATA USED

Data - HR Data with over 22000 rows from the year 2000 to 2020.

Data Cleaning & Analysis - Postgresql

Data Visualization - PowerBI

## QUESTIONS

1. What is the gender breakdown of employees in the company?
2. What is the race/ethnicity breakdown of employees in the company?
3. What is the age distribution of employees in the company?
4. How many employees work at headquarters versus remote locations?
5. What is the average length of employment for employees who have been terminated?
6. What is the tenure distribution for each department?
7. How does the gender distribution vary across departments and job titles?
8. What is the distribution of job titles across the company?
9. Which department has the highest turnover rate?
10. What is the distribution of employees across locations by state?
11. How has the company's employee count changed over time based on hire and term dates?

## SUMMARY OF FINDINGS

- There are more male employees
- White race is the most dominant while Native Hawaiian and American Indian are the least dominant.
- The youngest employee is 21 years old and the oldest is 58 years old
- The age groups were divided into five categories: 18-24, 25-34, 35-44, 45-54, and 55-64. The majority of employees fell within the 25-34 age range, followed by the 35-44 age range, with the smallest group being those aged 55-64.
- Most of the employees work at the headquarters versus compared to remotely.
- The average length of employment for terminated employees is around 7 years.
- The average tenure for each department is about 7 years with Marketing, Sales and Auditing having the highest and Product Management and Legal, having the lowest.
- The gender distribution across departments is fairly balanced but there are generally more male than female employees in the company.
- The Auditing department has the highest turnover rate followed by Legal. The least turn over rate are in the Business development and Marketing departments.
- A large number of employees come from the state of Ohio.
- The net change in employees has increased over the years.

## LIMITATIONS
* Some records had negative ages and these were excluded during querying(967 records). Ages used were 18 years and above.
* Some termdates were far into the future and were not included in the analysis(1461 records). The only term dates used were those less than or equal to the current date.
