# School_District_Analysis
## Overview of Project

### Purpose
Maria, the chief data scientist for a school district, has requested assistance with analysis of student standardized test scores. At one of the schools, Thomas High School, there is evidence of academic dishonesty by nineth graders. Therefore, she is requesting an analysis of the data without the potentially altered scores. She is looking for school summaries, relative performance, scores by school spending, scores by school size, and scores by school type, and wants to know how these items may have been affected by the academic dishonesty. 

### Resources
- Data Source: clean_students_complete.csv, schools_complete.csv, students_complete.csv (all available in the Resources folder[https://github.com/baileyvo/School_District_Analysis/tree/main/Resources]
- Software: Python 3.7.6, Visual Studio Code 1.63.2

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The first piece of analysis looked at launch dates, particularly the months successful **theater** campaings were launched. This was done by creating a pivot table as formated in the following image: 

![Theater Outcomes by Launch Date Pivot Table](https://github.com/baileyvo/kickstarter-analysis/blob/main/Resources/Analysis_Launch_Dates.PNG)

The pivot table was then used to generate a pivot chart, to visualize the results of the analysis:
![Theater Outcomes Based on Launch Date Chart](https://github.com/baileyvo/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The second piece of analysis looked at goals, and the number of successful, failed, and canceled **play** crowdfunding campaigns. This was done by using the Excel formula "COUNTIFS" to count the number of plays in each of the aforementioned categories in groups of $5000. 
For example, to find the number of **successful** crowdfunding campaigns with a funding goal of **$1000 to $4999**, the following formula was used in Excel: **=COUNTIFS(Kickstarter!$F:$F,"successful",Kickstarter!$D:$D,">=1000",Kickstarter!$D:$D,"<5000",Kickstarter!$R:$R,"plays")**

From there, the sum of successful, failed, and canceled campaigns was calculated using the SUM formula, and then the percentage of successful, failed, and canceled campaigns were calculated. These percentages were used to generate the following line chart:
![Outcomes Based on Goal](https://github.com/baileyvo/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)
