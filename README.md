# Pewlett-Hackard-Analysis

## Overview of the analysis: 
The purpose of this analysis is to...
  1. Determine the number of retiring employees per title
  2. Identify employees who are eligible to participate in a mentorship program. 
  3. Write a report that summarizes the analysis as well as helps prepare our friend's manager for the “silver tsunami” as many current employees reach retirement age.

## Resources
* Data Sources: departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv
* Software: SQL, PostgreSQL, pgAdmin

## Results: 
1. Number of retiring employees per title

* The number of retirement-age employees by most recent job title is shown below:
* The left most column is the count for the numnber of people per job title and the right column lists those jobs.

<img width="273" alt="Screen Shot 2021-08-08 at 9 00 58 PM" src="https://user-images.githubusercontent.com/85847344/128659103-ac090bde-5f66-4ae5-bf64-f90f5de2b776.png">

2. Employees who are eligible to participate in a mentorship program. 

* Using the ERD created in this module as a reference, the image below shows a mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965.
<img width="273" alt="Screen Shot 2021-08-08 at 9 00 58 PM" src="https://user-images.githubusercontent.com/85847344/128659416-2e40558e-90fe-48b5-ae34-0d2f6399e0c7.png">

* Below here is the ERD (Entity Relationship Diagram) used in the module to visualize the relationship between the data sources and the structure of the company's employee plan. This helped to facilitate the analysis. 

![Employee](https://user-images.githubusercontent.com/85847344/128658893-c23b17a5-ef75-4bb0-b32b-fb37b486d245.png)


## Summary: 

1. How many roles will need to be filled as the "silver tsunami" begins to make an impact?
    
   * 90,398 roles are needed and need to be filled out as soon as the workforce starts retiring at any given time.

2. Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
   
   * No, there are only 1,940 employees who are eligible to participate in a mentorship program.
  
<img width="507" alt="Screen Shot 2021-08-08 at 9 14 50 PM" src="https://user-images.githubusercontent.com/85847344/128659837-2c295e45-708b-45eb-b60c-12a1ce58ef7a.png">

