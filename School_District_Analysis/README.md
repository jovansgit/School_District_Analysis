# School_District_Analysis
A high-level snapshot of the district's key metrics, presented in a table format
An overview of the key metrics for each school, presented in a table format
Tables presenting each of the following metrics:
Top 5 and bottom 5 performing schools, based on the overall passing rate
The average math score received by students in each grade level at each school
The average reading score received by students in each grade level at each school
School performance based on the budget per student
School performance based on the school size 
School performance based on the type of school


## Overview of the school district analysis: 
Explain the purpose of this analysis.

We are helping analyze data on student funding and student standardized test scores to assit the school on making decisions regarding buget and priorities.

The school board has notified us that we can see evidence of academic dishonesty specifically, reading and math grades for Thomas High School ninth graders, appears to have been altered.

Our goal is to replace the math and reading scores for Thomas High School with NaNs and then perform analysis on our the school district dataset 

## Results: 
- How is the district summary affected?
When analysing the district summary we see the the average math score dropped 0.1, the average reading score remainedd the same, the percentage passing math dropped .2%, the percentage passing reading dropped .3%, and the overall passing percent dropped .1%.

![Distric_Summary_Before](resources/District_Summary_Before.png)

![Distric_Summary_After](resources/District_Summary_After.png)


- How is the school summary affected?

![School_Summary_Before](resources/School_Summary_Before.png)

After updating the school summary using only the 10th-12th graders from Thomas High School we see the % Passing Math increased from 66.911315 to 93.185690, % Passing Reading increased from 69.663609 to 97.018739, and % Overall Passing increased from 65.076453 to 90.630324 for Thomas High School.
![School_Summary_After](resources/School_Summary_After.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

After replacing the 9th graders math and reading scores we see that Thomas High Schools performance went from the school with the 8th best % Overall Passing to the 2nd.

When only looking at the % Passing Reading, we see the school went from last (15th place) to the 3rd best school

When only looking at the % Passing math, we see the school went from the 9th best school to the to the 7th best school
 

- How does replacing the ninth-grade scores affect the following:
-- Math and reading scores by grade
![Reading_Scores_Before](resources/Reading_Scores_Before.png)
![Reading_Scores_Before](resources/Reading_Scores_After.png)

![Math_Scores_Before](resources/Reading_Scores_Before.png)
![Math_Scores_Before](resources/Reading_Scores_After.png)

-- Scores by school spending

![Spending_Summary_Before](resources/Spending_Summary_Before.png)
![Spending_Summary_After](resources/Spending_Summary_After.png)

-- Scores by school size

![Score_By_Size_Before](resources/Score_By_Size_Before.png)
![Score_By_Size_After](resources/Score_By_Size_After.png)

-- Scores by school type

![Score_By_Type_Before](resources/Score_By_Type_Before.png)
![Score_By_Type_After](resources/Score_By_Type_After.png)

## Summary: 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
-
-
-
-

