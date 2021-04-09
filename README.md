# Pewlett-Hackard-Analysis
## Overview
The purpose of this analysis is to create queries from provided databases to Bobby's manager. The queries are to determine the number of retiring employees per title and identify employees who are eligible to participate in a mentorship program. We used DISTINCT ON, COUNT(), and other statements to create these queries.

## Results: Provide a bulleted list with four major points from the two analysis deliverables.
* According to the unique_titles.csv file, there are 90,398 unique employees that are eligible for retirement. The COUNT statement was implemented to show the total number of employees as shown below. 

![retiredemployees](https://user-images.githubusercontent.com/49353083/114113183-1049c900-98ac-11eb-882f-b1997e68c778.png)

* Majority of the employees who are eligible for retirement are the Senior Engineer and Senior Staff. The Pewlett Hackard company should try to get more employees to get positions related to this job title.

![retired](https://user-images.githubusercontent.com/49353083/114113733-5eab9780-98ad-11eb-8d41-a315d55cfae9.png)

* There are 1,549 employees who are eligible for the Mentorship program. 
* Although there are employees who are eligible for these Mentorship, there are no employees that are eligible for a Manager role. Pewlett Hackard should try to find employees who are eligible for the manager mentorship program.

## Summary: Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."

1) How many roles will need to be filled as the "silver tsunami" begins to make an impact?

The total number of roles that will need to be filled as the "silver tsunami" begins to make an impact is 90,398 roles. The first year of retirement there are 21,209 employees that will retire. That is nearly 23.4% of the total 90,398 employees that will retire in the span of 3 years. I have used the following query to calculate this number. 

![firstyearretirement](https://user-images.githubusercontent.com/49353083/114116073-f7dcad00-98b1-11eb-8da5-a4142a19e971.png)


2) Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

There are not enough retirement-ready employees in the department to mentor the next generation of Pewlett Hackard employees, which has been stated previously. There needs to be at least one employee under the Manager position to help mentor other employees in the near future. The query did not show any employees available in the Manager position shown in the image below.

![mentorship](https://user-images.githubusercontent.com/49353083/114114751-7dab2900-98af-11eb-8f11-c662303f2a63.png)
