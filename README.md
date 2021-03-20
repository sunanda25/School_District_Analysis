# School_District_Analysis

## Overview
The chief data scientist for a city school district, Maria is given a task to analyze the test scores across all schools in a district and report performance trends and patterns. These insights will help school boards make strategic decisions for their school budgets and priorities. The list of deliverables for the analysis of the school district are as shown below:
- District Summary
- School Summary
- Top 5 and bottom 5 performing schools
- Average math score and reading score for each grade 
- School performance based on the budget per student
- School performance based on the school size
- School performance based on the type of school

After analyzing and reporting the trends, the school board has notified that there was evidence of academic dishonesty, and the statistics need to be recalculated. This requires replacing math and reading scores for Thomas high school ninth graders with NaNs while keeping the rest of the data intact. Using the modified data, the school district analysis needs to be recalculated. 

## Results
### 1.  District Summary
The dataset has a total of 15 schools with 39,170 students and their total budget is 24,649,428. The district summary calculations include averages of math and reading score, percentages of students passing math and reading, and overall percentage.  
####  Original District Summary:
![image](https://user-images.githubusercontent.com/76491891/111881208-d4df6d00-8985-11eb-8d4c-c8c3bbac0a6c.png)
#### District Summary After Removing 9th Grade Scores For Thomas High School:
![image](https://user-images.githubusercontent.com/76491891/111881227-eaed2d80-8985-11eb-8a69-51abbd7d464a.png)

Below is the comparison of the district summary before and after removing the dishonest grades:
- The average math score decreased by 0.1 points whereas the average reading score remains the same.
- The percentage of students passing math decreased by 0.2% and the percentage of students passing reading decreased by 0.1 %.
- The overall pass percentage decreased by 0.3%.

Note: The analysis performed includes 9th-grade students of Thomas high school but with grades for math and reading marked as NaNs.

### 2.  School Summary
The dataset has an index total of 15 schools. Analysis of each school includes the school type, total students, total school budget, school budget per student, averages of math and reading score, percentages of students passing math and reading, and overall percentage.  
####  Original School Summary:
![image](https://user-images.githubusercontent.com/76491891/111881311-415a6c00-8986-11eb-833a-00f0e5c1239b.png)
####  School Summary After Removing 9th Grade Scores For Thomas High School:
![image](https://user-images.githubusercontent.com/76491891/111881340-60f19480-8986-11eb-9550-81b0d0f39c0c.png)

Below is the comparison of the school summary for Thomas high school before and after removing the 9th-grade Scores:
- The average math score decreased by 0.1 points whereas the average reading score remains the same.
- The percentage of students passing math decreased by 0.1% and the percentage of students passing reading decreased by 0.3%.
- The overall pass percentage decreased by 0.3%.

Note: The analysis performed excludes 9th-grade students of Thomas high school.

### 3.  School Performance
The school performance was calculated using the overall passing percentage of students. Thomas high school performance decreased by 0.31%. The ranking for Thomas high school has not changed, it remained in second place.
####  Original School Performance:
![image](https://user-images.githubusercontent.com/76491891/111881389-9dbd8b80-8986-11eb-88a1-fbca6ffe4994.png)
#### School Performance After Removing 9th Grade Scores For Thomas High School:
![image](https://user-images.githubusercontent.com/76491891/111881421-b2018880-8986-11eb-83da-6278b52bba69.png)

### 4.  Math and Reading Scores by Grade
Math and reading scores of 9th, 10th, 11th,12th grades calculated for each school.
####  Math and Reading Scores:
![image](https://user-images.githubusercontent.com/76491891/111881475-e117fa00-8986-11eb-8255-927ff8451750.png)  ![image](https://user-images.githubusercontent.com/76491891/111881482-ebd28f00-8986-11eb-8554-d0bf761ed6d2.png)
####  Math and Reading Scores After Removing 9th Grade Scores For Thomas High School:
![image](https://user-images.githubusercontent.com/76491891/111881508-0dcc1180-8987-11eb-97e0-8fa23b2782e6.png)  ![image](https://user-images.githubusercontent.com/76491891/111881518-16bce300-8987-11eb-8bf6-cc390cd37ab6.png)

Below is the comparison of the math and reading scores by grade before and after removing the 9th-grade scores of Thomas high school:
- Math and reading scores for 9th grade Thomas school are NaNs. Apart from this, there are no other changes to the data.

### 5.  Scores By School Spending
The school spending ranges were divided into 4 bins (<$584, $585-629, $630-644, $645-675) per student. Using spending ranges, the averages of math and reading score, percentages of students passing math and reading, and overall percentages were calculated.
####  Scores by School Spending:
![image](https://user-images.githubusercontent.com/76491891/111881574-5aafe800-8987-11eb-9384-bb158bc25234.png)
####  Scores by School Spending After Removing 9th Grade Scores For Thomas High School:
![image](https://user-images.githubusercontent.com/76491891/111881590-70251200-8987-11eb-8db3-977371ef97d2.png)

Below is the comparison of the scores by school spending before and after removing the 9th-grade scores of Thomas high school:
- Removing 9th-grade scores has no impact on the summary based on school spending. Scores and percentages remain the same.

### 6.  Scores By School Size
The school sizes were calculated using total students for the school. School sizes are divided into 3 bins:
- Small (<1000)
- Medium (1000-2000)
- Large (2000-5000)
####  Scores by School Size:
![image](https://user-images.githubusercontent.com/76491891/111881619-a498ce00-8987-11eb-9e44-9e6f3dfb1b7e.png)
####  Scores by School Size after Removing 9th Grade Scores For Thomas High School:
![image](https://user-images.githubusercontent.com/76491891/111881629-b8dccb00-8987-11eb-9c31-b6333d8d1dd1.png)

Below is the comparison of the scores by school size before and after removing the 9th-grade scores of Thomas high school:
- Removing 9th-grade scores has no impact on the summary based on school size. Scores and percentages remain the same.

### 7.  Scores By School Type
Averages of math and reading score, percentages of students passing math and reading, and overall percentage were calculated for 2 school types (District, Charter).
####  Scores by School Type:
![image](https://user-images.githubusercontent.com/76491891/111881656-e88bd300-8987-11eb-9180-289be08ce675.png)
####  Scores by School Type after Removing 9th Grade Scores For Thomas High School:
![image](https://user-images.githubusercontent.com/76491891/111881669-fa6d7600-8987-11eb-998d-c2b09d46aee4.png)

Below is the comparison of the scores by school type before and after removing the 9th-grade scores of Thomas high school:
- Removing 9th-grade scores has no impact on the summary based on school type. Scores and percentages remain the same.

## Summary
1.	The percentage of students passing math for Thomas high school was 93.2%. After removing the 9th-grade scores from Thomas high school, the percentage of students passing math is 93.1%, which is lower by 0.1% compared to the original summary.
2.	The percentage of students passing reading for Thomas high school was 97.3 After removing the 9th-grade scores from Thomas high school, the percentage of students passing reading is 97.0%, which is lower by 0.3% compared to the original summary.
3.	The overall pass percentage of students for Thomas high school was 90.9%. After removing the 9th-grade scores from Thomas high school, the overall percentage of students passing math and reading is 90.6%, which is lower by 0.3% compared to the original summary.
4.	Average math and reading scores for Thomas high school 9th grade were 83.6% and 83.7% respectively. After replacing the 9th-grade scores for math and reading with NaNs, the average scores also show as NaNs. 
