# School District Challenge
Module 4 – Jupyter Notebook

## Program Overview
The assignment consists of two technical analysis deliverables and a written report to present your results. We need to complete and submit the following deliverables:
•	Deliverable 1: Replace ninth-grade reading and math scores
Using the Pandas loc method with conditional statements and comparison and logical operators, select the ninth-grade reading and math scores for Thomas High School. Then, use the Pandas NumPy module to change the reading and math scores to NaN.
•	Deliverable 2: Repeat the school district analysis, and recreate the following metrics:
•	The district summary
•	The school summary
•	The top 5 and bottom 5 performing schools, based on the overall passing rate
•	The average math score for each grade level from each school
•	The average reading score for each grade level from each school
•	The scores by school spending per student, by school size, and by school type
•	Deliverable 3: A written report for the school district analysis (README.md)
## Resources
>> Data Sources: 
•	clean_students_complete.csv file
•	missing_grades.csv file
•	schools_complete.csv file
•	students_complete.csv file

>> Software: Jupyter Notebook 6.4.8
•	Language Python 3/10.4 (PythonData)
•	Libraries: Pandas, Numpy

## Results
The district summary
![District Summary](https://user-images.githubusercontent.com/105124485/172476053-7301a8c0-40a9-4880-8edf-e3e5e815f76d.jpg)

The school summary 
_(I formatted the columns for the percentages to print, then removed the formatting so as not to affect the calculations later in the coding)_
![Per School Summary](https://user-images.githubusercontent.com/105124485/172476120-9da42efc-0ea2-491e-80df-22ca224d23d0.jpg)

The top 5 and bottom 5 performing schools, based on the overall passing rate
![Top Schools](https://user-images.githubusercontent.com/105124485/172476161-5c5bb8f5-1a87-494a-902e-dd00c36d7138.jpg)
![Bottom Schools](https://user-images.githubusercontent.com/105124485/172476177-a6695635-4358-4813-95eb-4cffc1997e36.jpg)

The average math score for each grade level from each school
![Math Scores](https://user-images.githubusercontent.com/105124485/172479065-3d630209-a2e9-4345-81b1-4352bd4dc431.jpg)

The average reading score for each grade level from each school
![Reading Scores](https://user-images.githubusercontent.com/105124485/172479082-5958b280-1931-4cf7-9e81-1ccad7dde989.jpg)

The scores by school spending per student, by school size, and by school type
![School Summary Detailed](https://user-images.githubusercontent.com/105124485/172476278-ad0b05ce-3343-4d3d-8d66-d83d458b1eef.jpg)

## Summary
The first analysis included the entire set of data.  The second analysis did not include the ninth-grade students from Thomas High School.  The scores from Thomas High School had their scores replaced with NaN. Replacing those scores resulted in changes to Thomas High School passing percentage, but changes were minimal.  Additionally, the entire overall passing percentage of the entire district also showed a drop in overall passing percentage. 

When we looked at the effects of the school budget and the size of the schools, we found that the average scores and passing percentages were not really affected as spending per student increased. It seems that the lowest spending budgets resulted in the highest overall passing percentage. The same could be said for the school’s size, the smaller size schools had the highest overall passing percentage.
![Spending Summary](https://user-images.githubusercontent.com/105124485/172476327-cdd89106-be2b-4029-9c01-46539af5d369.jpg)
![Size Summary](https://user-images.githubusercontent.com/105124485/172476350-abdf9e25-fcb6-4c07-b7fd-df670087ca81.jpg)

Also, we noticed that the District Schools seem to not perform as well as the Charter Schools
![Type Summary](https://user-images.githubusercontent.com/105124485/172476395-f7913ba9-88c8-48ec-973a-478f02c9369d.jpg)

## Challenge Summary
While the average math, reading and overall scores at Thomas High School were impacted with the update, the changes were not sufficient to change its ranking versus other schools. The changes only had a minor impact of less than a 1 percentage point the top 5 metric. When the outputs were formatted the changes were not noticeable, it was only when you looked at the unformatted number that the hundredth came into play. Thomas High School’s went from an overall passing percentage of 90.948012 to 90.630324.
![Before and After - Top 5](https://user-images.githubusercontent.com/105124485/172474753-0adc201b-2d0f-4b5c-98d7-74b0f256a0a6.jpg)


