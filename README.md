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
![District Summary](https://user-images.githubusercontent.com/105124485/172473912-d6f33311-b246-4efd-8f4e-27d7a8ebb736.jpg)

The school summary 
(I formatted the columns for the percentages to print, then removed the formatting so as not to affect the calculations later in the coding)
![Per School Summary](https://user-images.githubusercontent.com/105124485/172473997-d0e4e7da-7175-4508-a4a5-3f1ee9cd3881.jpg)

The top 5 and bottom 5 performing schools, based on the overall passing rate
![Top Schools](https://user-images.githubusercontent.com/105124485/172474032-d05eae19-7db7-4458-9f08-479ea3a88937.jpg)
![Bottom Schools](https://user-images.githubusercontent.com/105124485/172474590-8b082191-f493-45a3-9de8-8aa11a6b7a1f.jpg)

The average math score for each grade level from each school
![Math Scores](https://user-images.githubusercontent.com/105124485/172474260-10ce8998-0eeb-4fd3-843f-6fde4a38fc31.jpg)

The average reading score for each grade level from each school
![Reading Scores](https://user-images.githubusercontent.com/105124485/172474141-cfb4d93f-2505-4558-9640-825e4a7681db.jpg)

The scores by school spending per student, by school size, and by school type
![School Summary Detailed](https://user-images.githubusercontent.com/105124485/172474301-7ff0d276-5c71-40de-8eb5-12f2f42b5b2c.jpg)

## Summary
The first analysis included the entire set of data.  The second analysis did not include the ninth-grade students from Thomas High School.  The scores from Thomas High School had their scores replaced with NaN. Replacing those scores resulted in changes to Thomas High School passing percentage, but changes were minimal.  Additionally, the entire overall passing percentage of the entire district also showed a drop in overall passing percentage. 

When we looked at the effects of the school budget and the size of the schools, we found that the average scores and passing percentages were not really affected as spending per student increased. It seems that the lowest spending budgets resulted in the highest overall passing percentage. The same could be said for the school’s size, the smaller size schools had the highest overall passing percentage.
![Spending Summary](https://user-images.githubusercontent.com/105124485/172474438-9f01412a-0eba-4657-a6ee-b0860c94a66d.jpg)
![Size Summary](https://user-images.githubusercontent.com/105124485/172474499-a00b20fa-a0a7-4723-8b54-9eda29126b5c.jpg)

Also, we noticed that the District Schools seem to not perform as well as the Charter Schools
![Type Summary](https://user-images.githubusercontent.com/105124485/172474672-fc788a87-97bd-4b6d-bf1f-751400cb1554.jpg)

## Challenge Summary
While the average math, reading and overall scores at Thomas High School were impacted with the update, the changes were not sufficient to change its ranking versus other schools. The changes only had a minor impact of less than a 1 percentage point the top 5 metric. When the outputs were formatted the changes were not noticeable, it was only when you looked at the unformatted number that the hundredth came into play. Thomas High School’s went from an overall passing percentage of 90.948012 to 90.630324.
![Before and After - Top 5](https://user-images.githubusercontent.com/105124485/172474753-0adc201b-2d0f-4b5c-98d7-74b0f256a0a6.jpg)


