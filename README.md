# Udemy-Data-Analysis

Udemy-Dashboard

This project analyzes Udemy course data to uncover insights into trends, pricing strategies, and learner preferences. Using Power BI, the project creates interactive dashboards to help stakeholders make data-driven decisions regarding course offerings and market positioning.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : Visual filters (Slicers) were added for four fields named "Year", "Language", "Courses".
- Step 6 : Four card visuals were added to the canvas, one representing total courses, paid courses, free courses and total students in udemy subscribed. 
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.           
           Although, by default, while calculating average, blank values or zero values are ignored.

Data Sources
Udemy Dataset: Publicly available dataset containing course metadata, enrollment numbers, reviews, rating, no. of lectures and pricing details.

![Udemydashboard](https://github.com/user-attachments/assets/edd496e7-0309-4562-92df-ac743a19aa93)


