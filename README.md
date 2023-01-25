# Pewlett-Hackard-Analysis
Module 7
---
## Overview
---
The dataset includes varibales such as employee ID, first and last names, birth dates, the time spent at the job, and their job title. The dataset has been given to us in order to determine the count of retiring employees by work title. Additionally, we would like to determine which employees are eligible to participate in the mentorship program. With the help of SQL and ERDs, we will create tables, use join fuctions, request data, filter/sort, import/export functions, etc. The analysis of the data will allow the company to prepare for new staff, as well as begin recruiting individuals for the mentonship opportunity.
## Results
By extracting data from multiple sources, it can sometimes be difficult to picture.. which is why we have created an 'Entity Relationship Diagram' (ERD) before we dive deeper into the data and determine the structure of the data. This ERD can be seen below:
---
<img width="453" alt="ERDiagram" src="https://user-images.githubusercontent.com/119131202/214702749-3107fe0f-f203-45bd-aa32-61f2e45fafa9.png">
---
### Count of Retiring Employees by Title
We must first manipulate the original tables in order to breakdown the number of retiring employees by title. We must first create a table that outlines a table that consists of individuals who were born between 1952 and 1955, ordered by their employee number. This first table can be seen below:
---
![image](https://user-images.githubusercontent.com/119131202/214704169-097908a7-4132-426d-aa2a-b682cc818cc1.png)
---
Once this table was populated, we must use this information to create another table that excludes the employees that have already left the company by filtering on hire dates. This new datset will now be condensed into the table below:
---
![image](https://user-images.githubusercontent.com/119131202/214704594-6b512fbf-b33c-46fc-91c7-08ebcdd6349e.png)
---
Lastly, we now have the correct dataset to work with to determine the number of retring employees by job title. The data suggests that there are 25,916 Senior Engineers, 24,926 Senior Staff, 9,285 Engineers, 7,636 Staff, 3,603 Technique Leaders, 1,090 Assistant Engineers, and 2 Manangers retiring. The final table can be seen below.
---
![image](https://user-images.githubusercontent.com/119131202/214705159-1622ec7f-9214-4d3b-a856-e9ef25a894c4.png)
---
##Summary
