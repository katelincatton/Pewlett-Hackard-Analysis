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
Count of Retiring Employees by Title
---
We must first manipulate the original tables in order to breakdown the number of retiring employees by title. We must first create a table that outlines a table that consists of individuals who were born between 1952 and 1955, ordered by their employee number. This first table can be seen below:

![1](https://user-images.githubusercontent.com/119131202/214705806-b763f73c-8f8c-4387-a98a-ffeb4e3c59e7.png)

Once this table was populated, we must use this information to create another table that excludes the employees that have already left the company by filtering on hire dates. This new datset will now be condensed into the table below:

![2](https://user-images.githubusercontent.com/119131202/214705841-a958df05-5da6-479e-b36a-bce559d8c22c.png)

Lastly, we now have the correct dataset to work with to determine the number of retring employees by job title. The data suggests that there are 25,916 Senior Engineers, 24,926 Senior Staff, 9,285 Engineers, 7,636 Staff, 3,603 Technique Leaders, 1,090 Assistant Engineers, and 2 Manangers retiring. The final table can be seen below.

![3](https://user-images.githubusercontent.com/119131202/214705863-ff82f2d1-4b15-4a62-8c14-28910ea5d814.png)
---
Eligible Employees for Mentorship Program
---
Next, we will retrieve the the correct dataset by joining tables, filtering data, and sorting the values. After the construction of the dataset, we were able to determine which employees were eligible for the mentorship program. You'll notice that the data is mostly grabbing the senior staff since they clearly have the most experieince.
![5](https://user-images.githubusercontent.com/119131202/214707354-fbf13287-eb2d-4748-a544-47a64ab2872b.PNG)

## Summary
The data suggests that there will be many employees retiring, thus, there will need to be a lot of new staff hired to fill those positions. There is nearly 70% of senior employees retiring, which suggests that many of the current employees will receive a promotion in order to fill those senior positions. To conclude, some retirees may choose to not accept the mentorship opportunity, which could result in some issues. By examining the data, the company will need to fill the senior positions with the most apporiate current employees, and begin the hirng process for many engineers, technique leaders, and assistant engineers. This would help fill the gaps and allow the business to continue running smoothly.
---
Analysis Performed by Katelin Catton
1/26/2023
