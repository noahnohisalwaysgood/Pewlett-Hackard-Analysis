# Pewlett-Hackard-Analysis

# Overview of the analysis:

* Determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. 
* Using the ERD I created in this module as a reference and my knowledge of SQL queries, create a Retirement Titles table that holds all the titles of employees who were born between January 1, 1952 and December 31, 1955. Because some employees may have multiple titles in the database. 
* Using the ERD I created in this module as a reference and my knowledge of SQL queries, create a mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965.

# Results

* Expecting 133,776 employees, who were born bettwen 1952-01-01 and 1955-12-31, are going to retire.
![image](https://user-images.githubusercontent.com/105985796/180588856-2406e490-93ff-46c5-b7f9-699813340951.png)

* Creating another table in order to avoid duplication of those employees that have already left the company. As a result, the number of expecting employees decreased 133,776 to 90,398.
![image](https://user-images.githubusercontent.com/105985796/180589094-d232cb76-8db7-4f98-9c4a-d17cb60c7067.png)

* Calculating soon-to-retire employees' job titles.
![image](https://user-images.githubusercontent.com/105985796/180589407-c5f01c61-5ca3-483f-805a-2e9afa247f8a.png)

* finding a result that the number of 1,549 employess with mentorship_eligibility, who were born bettwen 1965-01-01 and 1965-12-31.
![image](https://user-images.githubusercontent.com/105985796/180589550-36acc586-3921-4538-ad80-128ebc7495f9.png)

# Summary
Pros and Cons
Pros
* Pewlett-Hackard has 1,549 employess with mentorship_eligibility that is most important for the success of the company because It is important for employees with mentorship_eligibility to be good mentors to their new employees because effective mentorship can help improve new employees' work performance.

Cons
* Pewlett-Hackard is expecting 90,398 employees, who were born bettwen 1952-01-01 and 1955-12-31, are going to retire. The company is going to need to replace 90.398 roles within the company.

