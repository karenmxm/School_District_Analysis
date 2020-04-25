# School_District_Analysis
Analysis on student performence trends and patterns.

## Project Overview

The list of deliverables for the analysis of the school district: 

- A high-level snapshot of the district's key metrics, presented in a table format.
- A high-level snapshot of the district's key metrics, presented in a table format.
- Tables presenting each of the following metrics: 
  - Top 5 and bottom 5 performing schools, based on the overall passing rate
  - The average math score received by students in each grade level at each school
  - The average reading score received by students in each grade level at each school
  - School performance based on the budget per student
  - School performance based on the school size 
  - School performance based on the type of school

## Resources
Data Source: schools_complete.csv
             students_complete.csv

Software: Python 3.7.7, 
Anaconda, Jupyter Notebook

## Summary

The analysis include the following and results are shown in tables:

- School District Summary key metircs
- Per School Summary key metrics
  - Total Student Number
  - Total School number
  - Total Budget. 
  - Average Math Score.
  - Average reading Score.
  - % Passing Math
  - % Passing Reading
  - % Overall Passing

- Top five and bottom five school performence.
- Average Math and Reading Score by Grade.
- Scores by School Spending per student
- Scores by School Size
- Scores by School type
  
## Challenge Overview

The grades of the ninth graders at Thomas High School have been changed. While administrators do not know the full extent of this academic dishonesty, they want to uphold the standards of state testing. After assessing the situation with the school superintendent and Maria, the best approach prosed is to:

1. Replace the ninth-grade math and reading scores from Thomas High School with NaN.
2. Keep all other data associated with the ninth-grade students and Thomas High School intact.
3. Explain how PyCitySchools analysis changes after handling the incorrect data.

## Challenge Summary

After replacing Thomas High School 9th grade reading and math scores with NaN, the following results show the changes:

1. District summary: 

  - Average Math Score changes from 79.0 to 78.9
  - Average reading Score is consistant at 81.9
  - % Passing Math changes from 75% to 74%
  - % Passing Reading changes from 86% to 85%
  - % Overall Passing changes from 65% to 64% 

2. Per School summary

  - Average Math Score changes from 79.0 to 78.9
  - Average reading Score is consistant at 81.9
  - % Passing Math changes from 75% to 74%
  - % Passing Reading changes from 86% to 85%
  - % Overall Passing changes from 65% to 64% 
  
3. Thomas High School’s % Overall Passing, relative to the other schools changes from #2 to #8.

4. Math and Reading Scores by Grade
  - Thomas High School 9th grade Math and Reading scores are changed to NaN.
  
5. Scores by School Spending per studen
   Thomas High School Spending is in $630 -$644 category. In this category:
  - Average Math Score does not change
  - Average reading Score does not change 
  - % Passing Math changes from 73% to 67%
  - % Passing Reading changes from 84% to 77%
  - % Overall Passing changes from 63% to 56%

6. Scores by School Size
   Thomas High School is medium size (1000 - 2000). In this category:
   
  - Average Math Score does not change
  - Average reading Score does not change 
  - % Passing Math changes from 94% to 88%
  - % Passing Reading changes from 97% to 91%
  - % Overall Passing changes from 91% to 85%

7. Scores by School Type
   Thomas High School is a Charter School. Charter School performence:

  - Average Math Score does not change
  - Average reading Score does not change 
  - % Passing Math changes from 94% to 90%
  - % Passing Reading changes from 97% to 93%
  - % Overall Passing changes from 90% to 87%
