# School_District_Analysis

## Project Overview
Learning how to use Anaconda and Jupyter and applying those skills in order to better understand how to use effectively.

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.10.2, Jupyter Notebook 4.10.3

## Challenge Overview
Learning how to use Anaconda and Jupyter and applying those skills to:
1) Selecting and altering scores for the 9th grade of Thomas High School.
2) Calculate the change in students, '% Passing Math', '% Passing Reading', and '% Overall Passing' through the use of data frames.
3) Creating new data frames.
4) Sort rows of a data frame by highest to lowest from a specific column.
5) Find average math scores, average reading scores, scores by school spending per student, scores by school size, and scores by school type

## Challenge Results
- The District summary changed slightly from the module(Figure 1) to the challenge (Figure 2) due to the abscensce of the 9th graders from Thomas High School. 

![DistrictSummaryModule](https://user-images.githubusercontent.com/98374315/159191977-3e6044ac-1dda-4d31-b379-ba75049f19a0.PNG)
Figure 1. 

![DistrictSummaryChallenge](https://user-images.githubusercontent.com/98374315/159191990-c917e7b8-660d-40a6-8d6c-b63fdfff1e9f.PNG)
Figure 2. 

- The school summary is affected by the large increase in '% Passing Math', '% Passing Reading', and '% Overall Passing'. This is due to the fact, that the data orginally starts with a total of 1635 students attending Thomas High School, and the data ends up with only 1174 students after the 9th Graders are removed. 

![perSchoolSummaryChallengeb4](https://user-images.githubusercontent.com/98374315/159192002-0373848a-218e-476b-a3fb-e4e800516f9e.PNG)
Figure 3. With 9th Grader's scores of Thomas High School

![perSchoolSummaryChallengeAfter](https://user-images.githubusercontent.com/98374315/159192007-e8ffbb0b-1c8b-4a67-a0e0-7b5a622b59b1.PNG)
Figure 4. Without 9th Grader's scores of Thomas High School

- As stated above, Thomas High School's percentage performance was drastically affected by the 'new_student_count'! Allowing it to be ranked 2nd for '% Overall Passing' among all the high schools. However, the average math and reading scores are unaffected. 

    - There was a slight decline in average math and reading scores among all the 9th Graders from the Module(Figure 5) to the Challenge (Figure 6).
    
    ![AverageMathReadingScoresModule](https://user-images.githubusercontent.com/98374315/159192070-56663a78-f031-4242-b694-781f400bd94b.PNG)
    Figure 5. Module

   ![AverageMathReadingScoresChallenge](https://user-images.githubusercontent.com/98374315/159192805-e8c46800-fbb6-4322-aa01-59a18ddbab26.png)
    Figure 6. Challenge

- Scores by school spending remains unaffected, they both remain within the $631-645 range.
- Scores by school size remains unaffected.
- Scores by school type remains unaffected. 



## Challenge Summary
Seems that a majority of the data remains unchanged or slightly changed. The only drastic changes were the '% Passing Math', '% Passing Reading', and '% Overall Passing' when comparing before and after the Thomas High School 9th Graders were removed. We can conclude that a decent sized group of the 9th Graders from Thomas High School passed either a Math or Reading Exam with a larger portion of them not passing both. Four changes that were made after the ninth graders reading and math scores were replaced with NaNs:
  1) Calculated '% Passing Math' and replaced it within the 'per_school_summary_df'
  2) Calculated '% Passing Reading' and replaced it within the 'per_school_summary_df'
  3) Calculated '% Overall Passing' and replaced it within the 'per_school_summary_df'
  4) Sorted the rows of 'per_school_summary_df' in order to rank them from highest to lowest based on '% Overall Passing'.
