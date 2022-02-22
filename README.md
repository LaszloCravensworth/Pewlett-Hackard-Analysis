# Pewlett-Hackard-Analysis

## Overview of Project
&nbsp;&nbsp;&nbsp;A large company, Pewlett Hackard, has many employees who are approaching retirement age.  The purpose of this project was to: determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program.  In addition, a written report will summarize the analysis to prepare for a "silver tsunami" as many current employees reach retirement age.

## Resources
&nbsp;&nbsp;&nbsp;* departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv
<br/>
&nbsp;&nbsp;&nbsp;* Software: Visual Studio Code v.1.63.2, pgAdmin 4 v.6.4

### Results
* After applying the COUNT function and the SELECT DISTINCT ON statement to remove duplicates, the number of retirees dropped from 133,776 to 72,458.
* When producing a COUNT by title table it is clear that the majority of retirees are high level engineers and staff.
<br/><br/>![retirees](https://github.com/LaszloCravensworth/Pewlett-Hackard-Analysis/blob/main/Data/retirees.png)<br/>
* By using the SELECT COUNT from the mentorship_eligibility table, it revealed there were 1,549 qualified mentors.
<br/><br/>![mentorship](https://github.com/LaszloCravensworth/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.png)
* Filtering the to_date to equal '9999-01-01', made it possible to drop all employees who had already left the company.

### Summary
&nbsp;&nbsp;&nbsp;In conclusion, 72,458 employees will be retiring at Pewlett Hackard and those positions will need to be filled.  Since the number of qualified mentors is 1,549 there is a severe disproportion to the number of new employees that will need mentored.  Pewlett Hackard will likely have to hire or outsource high level experts to train new employees.
