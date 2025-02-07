# Factory-Report

### Report Link : https://app.powerbi.com/groups/me/reports/d8d9c289-2e78-4232-af9e-17f6bd292f07?ctid=5412e9e5-be21-4c79-ad0f-e2a64e63fbb6&pbi_source=linkShare

## Problem Statement

The Main Problem Was That some of the Machines breakdown so often and that costs alot of time and money to fix 


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Arrival Delay".
- Step 5 : For calculating average delay time, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Type") 
- Step 6 : In the report view, under the view tab, theme was selected.

  


### A little Problem

most of the process of data cleaning and organization was done on MS Excel in a Static was like how i dealt with the null values in type column and adding the latitude & magnitude of every Factorylocation if i needed to add a map in the future 

