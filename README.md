# School District Analysis

## Overview

After conducting a school district analysis, it was reported that academic dishonesty was discovered in the math and reading test scores of Thomas High School. 
Specifically, the scores for ninth graders were altered. As a result, the previous analysis must be adjusted by replacing the math and reading scores for the 
ninth grade students need to be replaced with "NaN" values and the analysis for the district rerun.

## Analysis Results
After replacing all of the ninth graders' scores with "NaN" (as shown below):

![Code for score replacement](https://github.com/MattK1454/School_District_Analysis/blob/main/Resources/Grade_replacement_code.png)

![Replacement output](https://github.com/MattK1454/School_District_Analysis/blob/main/Resources/Grade_replacement_output.png)

the analysis was rerun. Since all of the ninth graders from Thomas High School had their scores replaced the particular focus of the analysis re-run was the
focus on how this adjustment affected the school district analysis was altered. Primary areas of focus were:

* Average math and reading scores at Thomas High School
* Percentage of students passing according to math scores
* Percentage of students passing according to reading scores
* Overall percentage of students who passed both math and reading
* Percentage passing math, reading, and overall by budget per student
* Percentage passing math, reading, and overall by school size
* Placement of schools overall by score values relative to each other

### Reference metrics

These are the screenshot images of the metrics before and after the Thomas High School alterations.

![Original Analysis Output](https://github.com/MattK1454/School_District_Analysis/blob/main/Resources/THS_original_ouput.png)

![Adjusted Analysis Output](https://github.com/MattK1454/School_District_Analysis/blob/main/Resources/THS_modified_ouput.png)

-**Total Students**

-**Total Budget**

- **Average math and reading scores**

By effectively removing the ninth graders' scores, in should be noted that the average math exam score for the district dropped by one-tenth of a percentage point.
The average score for the district on the reading exam was not altered.

 - **Percentage of students passing according to math scores**

Following the data adjustment, it can be noted that the percentage of students passing the math exam was lowered by two-tenths of a percentage point following the adjustment.

- **Percentage of students passing according to reading scores**

Following the data adjustment, the resulting percentage of students in the district who passed the reading exam was dropped by three-tenths of a percentage point.

- **Overall percentage of students who passed both math and reading**

Due to the data adjustment of replacing the ninth graders' scores from Thomas High School with "NaN" values, the overall percentage of students who passed both the reading
and math exam in the district dropped by one-tenth of a percentage point.

## Summary
