# School_District_Analysis
Module 4 Analysis with Pandas, Python


## Overview of the school district analysis: Explain the purpose of this analysis.

The PyCity school board has reviewed the standardized test scores for the district but believes that evidence of academic dishoonesty exists, specifically in the reading and math grades for the Thomas High School 9th graders. In order to uphold state-testing standards, the board has asked to repeat the school district analysis that was already provided and advised how these changes affected the original overall analysis. 

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

### District Summary Impact 

- After removing the 9th graders from Thomas High School, the data shows that the average scores for the district decreases. Thus, the presence of their grades infers that their grades were greater than the district average. 

  - District Summary New (without Thomas High School 9th Graders)

![Alt text](https://github.com/Austin-Cyr/School_District_Analysis/blob/main/District%20Summary%2010-11-12th.PNG?raw=true)

  - District Summary (All Students)

![Alt_Text](https://github.com/Austin-Cyr/School_District_Analysis/blob/main/District%20Summary%209-12.PNG?raw=true)

### School Summary Impact
 
- After removing the 9th graders from Thomas High School, the data shows that the average scores did not change, but the Percent passing the Reading and Math decreased. Thus, the presence of the 9th grader grades infers that a greater percentage of them passed then the rest of the school.

  - School Summary New (without Thomas High School 9th Graders)

![Alt_Text](https://github.com/Austin-Cyr/School_District_Analysis/blob/main/Per_School_Summary_10-12.PNG)

  - School Summary (All Students)

![Alt_Text](https://github.com/Austin-Cyr/School_District_Analysis/blob/main/Per_School_Summary_9-12.PNG)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

  - Replacing the 9th graders' scores reduces Thomas High School's performance relative to other schools. Previously, they were in the top 5 and now they are not when you remove the 9th graders' scores because their percentage of overall passing has dropped to the 60 percentile.

  - Without the 9th Grader Scores
![Alt_Text](https://github.com/Austin-Cyr/School_District_Analysis/blob/main/Per_School_Summary_10-12_Perf_Comp_Title.PNG)

![Alt_Text](https://github.com/Austin-Cyr/School_District_Analysis/blob/main/Per_School_Summary_10-12_Perf_Comp.PNG)

  - With the 9th Grader Scores
![Alt_Text](https://github.com/Austin-Cyr/School_District_Analysis/blob/main/Per_School_Summary_9-12_Perf_Comp.PNG)


### Replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
      - Replacing the 9th graders' scores for Thomas High School with null values, would not have any impact on the other schools 9th graders or Thomas High School's other students because they are independent variables and thus not impacted by each other. Below is an image of the Reading scores, which only has an impact of Null values for the Thomas High School 9th Graders.

![Alt_Text](https://github.com/Austin-Cyr/School_District_Analysis/commit/241d62a34af05a328c3fc0fcab186bb7a3063da5)

  - Scores by school spending
      - Scores by school spending were impacted because an entire class at a school was removed from consideration. Particularly because this school was spending more per student.

![Alt_Text](https://github.com/Austin-Cyr/School_District_Analysis/blob/main/Avg_Spending_wo_9th_graders.PNG)

  - Scores by school size
      - Scores by school size was impacted as the score for mid-size schools decreased due to the removal of the higher averages for the 9th graders at Thomas High school. 

![Alt_Text](https://github.com/Austin-Cyr/School_District_Analysis/blob/main/school_by_size.PNG)

- Scores by school type
      - Scores by type was impacted as well since Thomas High School is a charter school. 

![Alt_Text](https://github.com/Austin-Cyr/School_District_Analysis/blob/main/scores_by_type.PNG)

## Summary: 

As a result of removing higher scoring students from the data set, all of the metric saw a reduced scoring for the respective category. The average Math and Reading scores decrease across the district. We saw scores by school spending decrease, particularly in its school size range and the school type range. In essence, the data does suggest that the scoring of the 9th graders at Thomas High School were abnormally high and should be reviewed more closely. 
