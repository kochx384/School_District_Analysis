# School District Analysis
## Overview
After the completion of the first school district analysis, it was discovered that there was evidence of academic dishonesty. In particular, the reading and math grades for Thomas High School ninth graders appear to have been altered. In order to uphold state-testing standards, the decision was made to replace the ninth grade math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once those scores were replaced, the entire overall analysis needed to be repeated. 
## Results
### District Summary
After conducting the second analysis, in the District Summary, the numbers from four categories had been changed:
- The Average Math Score changed from **79.0** to **78.9**.
- The % Passing Math changed from **75.0** to **74.8**.
- The % Passing Reading changed from **85.8** to **85.7**.
- The % Overall Passing changed from **65.2** to **64.9**.

**District Summary First Analysis:**
![Image](https://github.com/kochx384/School_District_Analysis/blob/main/images/district_summary_old.PNG)

**District Summary Second Analysis:**
![Image District Summary](https://github.com/kochx384/School_District_Analysis/blob/main/images/district_summary_new.PNG)
### School Summary
After conducting the second analysis, in the School Summary for Thomas High School,  the numbers from five categories had been changed:
- The Average Math Score changed from **83.418349** to **83.350937**.
- The Average Reading Score changed from **83.84893** to **83.896082**.
- The % Passing Math changed from **93.272171** to **93.18569**.
- The % Passing Reading changed from **97.308869** to **97.018739**.
- The % Overall Passing changed from **90.948012** to **90.630324**.

**School Summary Thomas High School First Analysis:**
![Image](https://github.com/kochx384/School_District_Analysis/blob/main/images/school_summary_old.PNG)

**School Summary Thomas High School Second Analysis:**
![Image](https://github.com/kochx384/School_District_Analysis/blob/main/images/school_summary_new.PNG)
### Math and Reading Scores by Grade
After conducting the second analysis, in the Average Math and Reading Scores by Grade per School, for Thomas High School, the numbers for the 9th grade had changed:
- The Average Math Score for the 9th Grade changed from **83.6** to **nan** because there is no longer any data for the 9th grade students.

**Average Math Score Thomas High School by Grade First Analysis:**

![image](https://github.com/kochx384/School_District_Analysis/blob/main/images/THS_math_score_old.PNG)

**Average Math Score Thomas High School by Grade Second Analysis:**

![image](https://github.com/kochx384/School_District_Analysis/blob/main/images/THS_math_score_new.PNG)

- The Average Reading Score for the 9th Grade changed from **83.7** to **nan** because there is no longer any data for the 9th grade students.

**Average Reading Score Thomas High School by Grade First Analysis:**

![image](https://github.com/kochx384/School_District_Analysis/blob/main/images/THS_reading_score_old.PNG)

**Average Reading Score Thomas High School by Grade Second Analysis:**

![image](https://github.com/kochx384/School_District_Analysis/blob/main/images/THS_reading_score_new.PNG)
### Scores By School Spending
After conducting the second analysis, in the Scores By School Spending, the numbers for the range $630-644 from two categories had changed:
- The % Passing Reading changed from **84.4** to **84.3**.
- The % Overall Passing changed from **62.9** to **62.8**.

**Scores By School Spending from the first analysis:**
![image](https://github.com/kochx384/School_District_Analysis/blob/main/images/scores_spending_old.PNG)

**Scores By School Spending from the second analysis:**
![image](https://github.com/kochx384/School_District_Analysis/blob/main/images/scores_spending_new.PNG)

### Scores By School Size
After conducting the second analysis, in the Scores by School Size, the numbers for the Medium size from one category had changed:
- The % Passing Reading changed from **96.8** to **96.7**.

**Scores By School Size First Analysis:**
![image](https://github.com/kochx384/School_District_Analysis/blob/main/images/scores_school_size_old.PNG)

**Scores By School Size Second Analysis:**
![image](https://github.com/kochx384/School_District_Analysis/blob/main/images/scores_school_size_new.PNG)

### Scores By School Type
After conducting the second analysis, in the Scores by School Type, there were no changes:

**Scores By School Type First Analysis:**
![image](https://github.com/kochx384/School_District_Analysis/blob/main/images/scores_school_type_old.PNG)

**Scores By School Type from the second analysis:**
![image](https://github.com/kochx384/School_District_Analysis/blob/main/images/scores_school_type_new.PNG)

## Summary
There have been several changes in the updated school district analysis after the reading and math scores for the ninth grade students at Thomas High School had been replaced with NaNs. One of the changes was in the School Summary, which grouped the data for each school. Since the ninth grade scores were taken out of the data, it is no surprise that the average math and reading scores along with the passing percentages were all changed. Another change occurred in the District Summary, which totals the average scores and percentages for all the schools combined. We see this change in the overall total of the district. We can also see a change in the Math and Reading Scores by Grade, which shows the average math and reading scores by grade for each school. There are no longer any scores for the Thomas High School ninth grade students, so all we can now see is "nan" in the spot where the average ninth grade score used to be. Finally, we can also see changes in the Scores By School Spending and the Scores By School Size. The changes occurred in the groups that Thomas High School belonged to. 
