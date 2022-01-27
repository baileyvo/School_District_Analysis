# School_District_Analysis
## Overview of Project

### Purpose
Maria, the chief data scientist for a school district, has requested assistance with analysis of student standardized test scores. At one of the schools, Thomas High School, there is evidence of academic dishonesty by ninth graders. Therefore, she is requesting an analysis of the data with and without the potentially altered scores. She is looking for school summaries, relative performance, scores by school spending, scores by school size, and scores by school type, and wants to know how these items may have been affected by the academic dishonesty. Therefore analysis is defined as before removal and after removal (of Thomas High School Ninth Graders).

### Resources
- Data Source: clean_students_complete.csv, schools_complete.csv, students_complete.csv (all available in the [Resources folder](https://github.com/baileyvo/School_District_Analysis/tree/main/Resources))
- Software: Python 3.7.11, Visual Studio Code 1.63.2, Jupyter Notebook 6.4.6

## Results

### Analysis of Affects of Academic Dishonesty
- The district summaries are as follows: 

**Before Removal District Summary**
![Before District Summary](https://github.com/baileyvo/School_District_Analysis/blob/main/Images/Before_District_Summary.PNG)

**After Removal District Summary**
![After District Summary](https://github.com/baileyvo/School_District_Analysis/blob/main/Images/After_District_Summary.PNG)

Removing the Thomas High School ninth graders caused a small decrease in Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing. 

- The school summaries are as follows:

**Before Removal School Summary**
![Before School Summary](https://github.com/baileyvo/School_District_Analysis/blob/main/Images/Before_School_Summary.PNG)

**After Removal School Summary**
![After School Summary](https://github.com/baileyvo/School_District_Analysis/blob/main/Images/After_School_Summary.PNG)

The only differences in the school summaries come in the Thomas High School row. Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, and % Overall Passing all showed small decreases when the ninth grader's scores were removed. 

- The top five performing schools are as follows:

**Before Removal Top Schools**
![Before Top Schools](https://github.com/baileyvo/School_District_Analysis/blob/main/Images/Before_Top_Schools.PNG)

**After Removal Top Schools**
![After Top Schools](https://github.com/baileyvo/School_District_Analysis/blob/main/Images/After_Top_Schools.PNG)

Even after removing the Thomas High School ninth grader's math and reading scores, Thomas High School remained the number two performing school when comparing % Overall Passing.

- The average math scores by school and by grade are as follows:

**Before Removal Average Math Scores**

![Before Math Scores Grades](https://github.com/baileyvo/School_District_Analysis/blob/main/Images/Before_Math_Scores_Grade.PNG)


**After Removal Average Math Scores**

![After Math Scores Grades](https://github.com/baileyvo/School_District_Analysis/blob/main/Images/After_Math_Scores_Grade.PNG)

Here, the fact that the ninth grade scores were removed is obvious, as the only change between the before and after is that the Thomas High School 9th column reads "nan" because all of the data has been removed. 

- The average reading scores by school and by grade are as follows:

**Before Removal Average Reading Scores**

![Before Reading Scores Grades](https://github.com/baileyvo/School_District_Analysis/blob/main/Images/Before_Reading_Scores_Grade.PNG)


**After Removal Average Math Scores**

![After Reading Scores Grades](https://github.com/baileyvo/School_District_Analysis/blob/main/Images/After_Reading_Scores_Grade.PNG)

Here, the fact that the ninth grade scores were removed is obvious, as the only change between the before and after is that the Thomas High School 9th column reads "nan" because all of the data has been removed. 

- The data on scores by school spending is as follows:

**Before Removal Spending Summary**
![Before Spending Summary](https://github.com/baileyvo/School_District_Analysis/blob/main/Images/Before_Spending_Summary.PNG)

**After Removal Spending Summary**
![After Spending Summary](https://github.com/baileyvo/School_District_Analysis/blob/main/Images/After_Spending_Summary.PNG)

Removing the Thomas High School ninth graders had no affect on these outcomes, possibly due to rounding.

- The data on scores by school size is as follows:

**Before Removal Size Summary**
![Before Size Summary](https://github.com/baileyvo/School_District_Analysis/blob/main/Images/Before_Size_Summary.PNG)

**After Removal Size Summary**
![After Size Summary](https://github.com/baileyvo/School_District_Analysis/blob/main/Images/After_Size_Summary.PNG)

Removing the Thomas High School ninth graders had no affect on these outcomes, possibly due to rounding.

- The data on scores by school type is as follows:

**Before Removal Type Summary**
![Before Type Summary](https://github.com/baileyvo/School_District_Analysis/blob/main/Images/Before_Type_Summary.PNG)

**After Removal Type Summary**
![After Type Summary](https://github.com/baileyvo/School_District_Analysis/blob/main/Images/After_Type_Summary.PNG)

Removing the Thomas High School ninth graders had no affect on these outcomes, possibly due to rounding.

## Summary
There were four changes to the school district analysis after reading and math scores were replaced for all Thomas High School Ninth Graders:
- There were fewer total students included in the analysis.
- The average for all students in the district combined decreased in Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing.
- Average Math Score, Average Reading Score, % Passing Math, % Passing Reading, and % Overall Passing all showed small decreases for Thomas High School overall.
- No information was able to be generated for Thomas High School Ninth Grade average math, reading, or overall passing percentages.
