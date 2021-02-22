# School_District_Analysis

## Overview of Project
We used the school district's [school_data](Resources/schools_complete.csv) and [student_data](Resources/students_complete.csv) to identify key metrics in a school district summary:
- number of students
- number of schools
- total budget
- average math scores
- average reading scores
- passing percentages

### Purpose
Evaluating each school's performance and determine which key metrics that impact students' overall performace. 

## Results
- Schools with less students (smaller than 1000) performed signifcantly higher on combined percentages of math and reading.
- Charter schools scored signifantly higher on overall passing percentages than District schools.
- Schools with higher spending budget per student had lower overall passing percentages.
- After removing the 9th grade scores from Thomas High School, the reading, math and overall scores of that school significantly increased. 
- Reading scores ranged from 80% to 84%.
- Math scores ranged from 76% to 85%.
- There was no significant changes for reading, math and overall combined scores across grade levels for each school. 
![changes_in_scores_groupedBy_reading_grade.png](Resources/changes_in_scores_groupedBy_reading_grade.png] ![changes_in_scores_groupedBy_math_grade.png](Resources/changes_in_scores_groupedBy_math_grade.png]

## Summary
- After replacing the math and reading scores for Thomas High School, that school's reading, math and overall scores increased from the 60's to above 80's.
![graph](Resources/unchanged_THS_data.png] ![graph](Resources/changed_THS_data.png] 
- When comparing data with and without the 9th grade scores for Thomas High School in Charter and District performance, the data did not change. 
- Student count decreased by 461.
- Overall passing percentage increased from 65.17 to 65.95.
