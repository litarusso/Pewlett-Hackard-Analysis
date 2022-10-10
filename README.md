# MODUL 7 PEWLETT-HACKARD-ANALYSIS

## Overview of The Analysis

The purpose of the new analysis is to prepare Pewlett-Hackard for the upcoming “silver tsunami”. A big amound of employees will have to be retiring because of their age and their positions will need to be filled in the near future. This analysis focused to ensure a smooth transition. For that reason I worked on the tasks below:

### Focused On The Folowing Subjects

- Define retiring employees by their ages and group them by their titles.
- Find out create  the most recent title of each employee
- Separeted employees who have already left the company
- Find out the employees eligible for mentorship program. To be able to assign the eligible mentors to the new employees.

### Created New Datas From 6 csv Files Of HR Department.

- The csv files we had were [docs/departments.csv], [employees.csv], [dept_emp.csv], [dept_manager], [salaries], [titles]. They were Csv files converted from Excel.
- I prepared six more files to be able to prepare this analysis. I used the old datas titles and by using SQL and prepared the new ones. Those new files are [current_emp.csv], [mentorship_eligibility.csv], [retirement_info.csv], [retirement_titles.csv], [retiring_titles.csv], [unique_titles.csv].
- This project is based on those twelve files.

## Results

- Retiring Employees
  The table on "Figure 1" displays the list of employees who is going to retire in the next few years, without duplicate titles. Which means all employees are with their last titles in that list.
<p align="center">  
    <img width="496" alt="figure-1 retiring title_without_dublicates" src="https://user-images.githubusercontent.com/111788394/194944520-d1f8ac1e-ffe4-4f1d-a169-784752d477a1.png">
  <p align="center">   
   Figure 1: The list of retiring people with their title

- Total Amound of Retiring Employees By Titles
The table on "Figure 2" displays the amount of retiring people in each titles. As this is a time and money consuming program Bob has to show the importance of the project to the top management. This table is to show them how frajile can be the situation in a couple of years. With this table the top managers will be convinced to take the precotions.
   <p align="center">  
   <img width="250" alt="figure3-Total amound_of_ retiring_people" src="https://user-images.githubusercontent.com/111788394/194945211-0f5277b1-25e3-4911-a899-ee22954213af.png">
   <p align="center">  
     Figure 2: The list of retiring people with their title
   
 
 - Mentorship Eligibility
   
   -  The table on "Figure 3" is a sample  of the people who are eligible for the mentorship program. Those people will be able to give trainings to the new generation of the company. This table is 1549 employees who can be mentors. For further information please look to the [mentorship_eligibility.csv]
<p align="center">  
  <img width="738" alt="Figure4_Mentorship_eligibility" src="https://user-images.githubusercontent.com/111788394/194949898-97e099c4-67ec-42cb-8e5a-59ec8e3ef47b.png">
<p align="center">  
   Figure 3: Mentorship Eligible Employees
   
   -  The table on "Figure 4" is the amount of retiring people that are eligible to  mentorship program by title. I prepared this additional table to understand how many mentors will we have and in which departments.
 <p align="center">   
  <img width="253" alt="Screen Shot 2022-10-10 at 5 01 58 PM" src="https://user-images.githubusercontent.com/111788394/194952111-e1ff89a0-264b-429d-8735-fbc541083bb9.png">
<p align="center">  
   Figure 4: Mentorship Eligible Employees by Titles

## Summary
  
  Pewlett-Hackard will be facing a difficult time in some years. Howewer this wont be so bad because Bob is planing the future. To have a summary I prepared put here two more tables. 
  If we compare the "Figure 3" with "Figure 4" and "Figure 5", we will see that we have a big human resourse that we can train until 'Silver Tsunami' will come. The new generation is more than retiring people and Pewlett-Hackard has enough mentorship eligible people.
  <p align="center">  
  <img width="252" alt="new _generation" src="https://user-images.githubusercontent.com/111788394/194958486-ce225e28-6636-443e-a886-ca6c49ae5844.png">
   <p align="center">  
Figure 5: New Generation
  <p align="center">
  <img width="253" alt="Screen Shot 2022-10-10 at 5 01 58 PM" src="https://user-images.githubusercontent.com/111788394/194958854-2dc82ab3-ff6a-4971-bbc6-c757c0ee9050.png">
  <p align="center">
    Figure 6: Mentors
    

      
      
      
      
  
