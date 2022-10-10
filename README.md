# MODUL 7 PEWLETT-HACKARD-ANALYSIS

## Overview of The Analysis

The purpose of the new analysis is to prepare Pewlett-Hackard for the upcoming “silver tsunami”. A big amound of employees will have to be retiring because of their age and their positions will need to be filled in the near future. This analysis focused to ensure a smooth transition. 

### For that purpose we focused on the folowing subjects

- Define retiring employees by their ages and group them by their titles.
- Find out create  the most recent title of each employee
- Separeted employees who have already left the company
- Find out the employees eligible for mentorship program. To be able to assign the eligible mentors to the new employees.

### I created new datas from six csv files that HR Department had.

- Those six csv files were [docs/departments.csv], [employees.csv], [dept_emp.csv], [dept_manager], [salaries], [titles]. They were Csv files converted from Excel.
- I prepared six more Csv files to be able to prepare this analysis. I used the old datas titles and by using SQL I did the new ones. Those new files are [current_emp.csv], [mentorship_eligibility.csv], [retirement_info.csv], [retirement_titles.csv], [retiring_titles.csv], [unique_titles.csv].
- This project is based on those twelve files.

## Results
- The table on "Figure 1" displays the list of employees who is going to retire in the next few years, without duplicate titles. Which means all employees are with their last titles in that list.

    <img width="496" alt="figure-1 retiring title_without_dublicates" src="https://user-images.githubusercontent.com/111788394/194944520-d1f8ac1e-ffe4-4f1d-a169-784752d477a1.png">
   
   Figure 1: The list of retiring people with their title

- The table on "Figure 2" displays the amount of retiring people in each titles. As this is a time and money consuming program Bob has to show the importance of the project to the top management. This table is to show them how frajile can be the situation in a couple of years. With this table the top managers will be convinced to take the precotions.

   <img width="250" alt="figure3-Total amound_of_ retiring_people" src="https://user-images.githubusercontent.com/111788394/194945211-0f5277b1-25e3-4911-a899-ee22954213af.png">
   
   Figure 2: The list of retiring people with their title
   
 - The last table on "Figure 3" is a sample  of the people who are eligible for the mentorship program. Those people will be able to give trainings to the new generation of the company. This table is 1550 employees who can be mentors.

  <img width="733" alt="Figure4_Mentorship_eligible_pepople" src="https://user-images.githubusercontent.com/111788394/194948057-837b8034-a9c8-425b-86b2-e3b81e0b7221.png">



## Summary
