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

### Analysis of Outcomes Based on Goals
The second piece of analysis looked at goals, and the number of successful, failed, and canceled **play** crowdfunding campaigns. This was done by using the Excel formula "COUNTIFS" to count the number of plays in each of the aforementioned categories in groups of $5000. 
For example, to find the number of **successful** crowdfunding campaigns with a funding goal of **$1000 to $4999**, the following formula was used in Excel: **=COUNTIFS(Kickstarter!$F:$F,"successful",Kickstarter!$D:$D,">=1000",Kickstarter!$D:$D,"<5000",Kickstarter!$R:$R,"plays")**

From there, the sum of successful, failed, and canceled campaigns was calculated using the SUM formula, and then the percentage of successful, failed, and canceled campaigns were calculated. These percentages were used to generate the following line chart:
![Outcomes Based on Goal](https://github.com/baileyvo/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)
