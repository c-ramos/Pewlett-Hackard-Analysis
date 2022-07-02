# Pewlett Hackard Analysis
Analysis of employee database using SQL, pgAdmin, and PostgreSQL

## Overview of the Analysis
Data modeling, data engineering, and data analysis: The purpose of this analysis was to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. I sketched an ERD of the tables to hold data, imported the CSVs into the database, and analyzed and evaluated new data to answer questions about title gaps in the company.

## Results

![image](https://user-images.githubusercontent.com/96538067/177014954-3f5d77c2-68aa-4ea5-b4e3-996d6649b7ae.png)

* Use Distinct On: Removed duplicates and left one job titlte to create an accurate list of retiring employees
* Two managers are retiring
* The majority of retiring employees holde senior titles (i.e., "Senior Engineers"). The company will need to recruit extensively and train non-retirees.
* Retiring Employee counts based on Title (90,398 potential retirees)
* Number of eligible employees for mentorship program is low compared to potential employees retiring (1,549 vs 90,398). See below.
![image](https://user-images.githubusercontent.com/96538067/177015611-b017b9fe-d4be-4a91-ba9e-2b0ba9fc2eb9.png)

## Summary 
* How many roles will need to be filled as the "silver tsunami" begins to make an impact?

The "silver tsunami" will leave 90,398 vacancies.

* Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

Using the DOB criteria, the mentee list is comprised of 1,549 employees. There is a significant gap between approximately 1,500 employees and 90,300 mentors/retirees.
