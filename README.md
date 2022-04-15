# Pewlett-Hackard-Analysis

## Overview
An entity relationship diagram was developed utilizing quick database diagrams to extract and organize the main elements from multiple data tables after evaluating the employee files for Pewlett Hackard. Postgres and the pgAdmin interface were used to import the data. The leadership is concerned about a silver tsunami, in which a large number of staff retire, leaving a large number of employment openings. A list of departing employees by title and a list of employees eligible for mentorship were generated using SQL queries.

# Results 
*Employee database relationship diagram:
![EmployeeDB png](https://user-images.githubusercontent.com/96156893/163578609-3fd4f505-378d-4070-99ef-f5f4a91ea313.png)

## Retirement Titles
•	The birth dates were filtered to retrieve the employees who were born between 1952 and 1955. Then, order by the employee number .
.![retirement_title](https://user-images.githubusercontent.com/96156893/163580661-3d77ab61-a1fe-4a3f-8532-ccf11f241752.png)

## Unique Titles 
•	Created a table that excluded employees that had left company
![unique_titles](https://user-images.githubusercontent.com/96156893/163580924-79ce83b8-c336-4657-b37e-1fe54ad2b9cd.png)

## Retiring Titles
•	A Count of Retiring employees
![retiring_titles](https://user-images.githubusercontent.com/96156893/163581050-2e9275f0-4a5c-45a4-b9c9-5d0655f61484.png)

## Mentorship Eligibilty
•	Mentorship Eligibility table for current employees who were born between January 1, 1965 and December 31, 1965.
![mentorship_eligibilty](https://user-images.githubusercontent.com/96156893/163581157-50aa0786-0f6f-447b-a83c-8184e07dc183.png)

# Summary 
At the moment, a large number of Pewlett Hackard employees are preparing to retire or are being redirected to their mentorship efforts, implying that they will need to go through a lengthy hiring process in the future. A large number of prospective retirees will hold senior positions, the mentorship program should act as a buffer for the vast experience that will be leaving the organization in the coming years.
