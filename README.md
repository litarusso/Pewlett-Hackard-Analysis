# MODUL 7 PEWLETT-HACKARD-ANALYSIS

## Overview of The Analysis

The new analysis aims to prepare Pewlett-Hackard for the upcoming "silver tsunami". Many employees will have to retire because of their age, and their positions will need to be filled shortly. This analysis focused on ensuring a smooth transition. For that reason, I worked on the tasks below:

### Focused On The Following Subjects

- Define retiring employees by their ages and group them by their titles.
- Find out create  the most recent title of each employee
- Separate employees who have already left the company
- Find out the employees eligible for the mentorship program. To be able to assign eligible mentors to the new employees.

### Created New Data From 6 csv Files Of HR Department.

- The csv files we had were [docs/departments.csv], [employees.csv], [dept_emp.csv], [dept_manager], [salaries], [titles]. They were csv files converted from Excel.
- I prepared six more files to be able to prepare this analysis. I used the old data titles by using SQL, and prepared the new ones. Those new files are [current_emp.csv], [mentorship_eligibility.csv], [retirement_info.csv], [retirement_titles.csv], [retiring_titles.csv], [unique_titles.csv].
- This project is based on those twelve files.

## Results

- Retiring Employees.

   The table in "Figure 1" displays the list of employees who will retire in the next few years without duplicate titles. Which means all employees are with their last titles in that list.
<p align="center">  
    <img width="496" alt="figure-1 retiring title_without_dublicates" src="https://user-images.githubusercontent.com/111788394/194944520-d1f8ac1e-ffe4-4f1d-a169-784752d477a1.png">
  <p align="center">   
   Figure 1: The list of retiring people with their title

- Total Amount of Retiring Employees By Title.
  
    The table in "Figure 2" displays the number of retiring people in each title. As this is a time and money-consuming program, Bob has to show the importance of the project to the top management. This table shows them how fragile the situation can be in a couple of years. With this table, the top managers will be convinced to take precautions.
   <p align="center">  
   <img width="250" alt="figure3-Total amound_of_ retiring_people" src="https://user-images.githubusercontent.com/111788394/194945211-0f5277b1-25e3-4911-a899-ee22954213af.png">
   <p align="center">  
     Figure 2: The list of retiring people with their title
   
 
 - Mentorship Eligibility
   
   -  The table in "Figure 3" is a sample of the eligible people for the mentorship program. Those people will be able to give training to the new generation of the company. This table shows 1549 employees who can be mentors. For further information, please look at the [mentorship_eligibility.csv]
<p align="center">  
  <img width="738" alt="Figure4_Mentorship_eligibility" src="https://user-images.githubusercontent.com/111788394/194949898-97e099c4-67ec-42cb-8e5a-59ec8e3ef47b.png">
<p align="center">  
   Figure 3: Mentorship Eligible Employees
   
   -  The table in "Figure 4" shows the number of retiring people eligible for the mentorship program by title. I prepared this additional table to understand how many mentors there will be and in which department.
 <p align="center">   
  <img width="253" alt="Screen Shot 2022-10-10 at 5 01 58 PM" src="https://user-images.githubusercontent.com/111788394/194952111-e1ff89a0-264b-429d-8735-fbc541083bb9.png">
<p align="center">  
   Figure 4: Mentorship Eligible Employees by Titles

## Summary
  
  Pewlett-Hackard will be facing a difficult time in some years. However, this will be all right because Bob plans the future. To summarize, I prepared put here two more tables. 
  If we compare "Figure 4" with "Figure 5" and "Figure 6", we will see that the company has a great human resource that mentors can train until the 'Silver Tsunami' comes. The new generation (born on 1980 and later [new_generation.csv]) is more than retiring people, and Pewlett-Hackard has enough mentorship-eligible people.
  <p align="center">  
  <img width="252" alt="new _generation" src="https://user-images.githubusercontent.com/111788394/194958486-ce225e28-6636-443e-a886-ca6c49ae5844.png">
   <p align="center">  
   Figure 5: New Generation
     
   <p align="center">  
   <img width="253" alt="Screen Shot 2022-10-10 at 5 01 58 PM" src="https://user-images.githubusercontent.com/111788394/194960511-cd3a814b-20fb-4daa-a18f-5152d687b62b.png">
   <p align="center">  
   Figure 6: Eligible Mentors


    

      
      
      
      
  
