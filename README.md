# School_District_Analysis

## Overview
Maria is a the Chief Data Scientist for a school district and is looking for insights into performance and patterns based on data from all the high schools in her district.  Maria would like to use these insights to make strategic decisions about funding and curriculums at the school district level.

##  Resources
-Software: Python3.7.6
-files: students_complete.csv, schools_complete.csv

## Results
In the results, the reader should be aware that there were concerns regarding Thomas High School 9th Graders score integrity.  As a result, all reading and math scores had to be removed from the dataset in order to provide reliable information.  The following summary will reference the Original (dataset) which includes 9th Grade scores from Thomas High School and New (dataset) which does not include 9th Grade Scores from Thomas High School

### District Summary
After removing the 9th graders scores from Thomas High School, the data shows there were little change to overall student averages for each category.  The change was less than 1% and can be concluded that the remove had little impact on the overall data.
- In the original District Summary:
  - Average Math Score = 79%
  - Average Reading Score = 81.9%
  - Percentage Passing Math = 75%
  - Percentage Passing Reading = 86%
  - Overall Percentage Passing = 65%
- In the new District Summary:
  - Average Math Score = 78.9%
  - Average Reading Score = 81.9%
  - Percentage Passing Math = 74.8%
  - Percentage Passing Reading = 85.7%
  - Overall Percentage Passing = 64.9%
 
### School Summary
After removing the 9th graders scores from Thomas High School, the data shows there were little change to overall data for Thomas High School, which is the only item that was impacted from this summary.  Differences were no greater than 1%.  It an be concluded that the removal had little impact on School_summary.  
-In The Original School Summary for Thomas High school:
  - Average Math Score = 83.41%
  - Average Reading Score = 83.84%
  - Percentage Passing Math = 93.27%
  - Percentage Passing Reading = 97.30%
  - Overall Percentage Passing = 90.94%
  
 -In the New School Summary for Thomas High School
  - Average Math Score = 83.35%
  - Average Reading Score = 83.89%
  - Percentage Passing Math = 93.18%
  - Percentage Passing Reading = 97.01%
  - Overall Percentage Passing = 90.63%


### Thomas High 9th Grade Scores vs All Other Schools
- When compared to the rankings of other schools, after removing the data for 9th graders from Thomas High School, it can be concluded there was little change to the overall ranking of Thomas High School.  Thomas High School ranked 2nd in the district both before and after the data for 9th graders was removed.

### Thomas High 9th Grade Impacts
- Because the 9th Grade scores were removed, there is a NaN(not a number) showing for both reading and math scores for 9th graders from Thomas High when grouped by school.
  - Change did not impact scores by school spending
  - Change did not impact scores by school size
  - Change did not impact scores by school type

## Summary

In conclusion, the removal of the data from the data set for 9th graders from Thomas High School had the most impact on Thomas High School itself and little impact on the school district overall.
  - Overall District Percentage passed decreased.
  - Percentage that passed Reading decreased.
  - Percentage that passed math decreased.
  - Overall percentage passed for Thomas High School decreased.
 However, all decreases overall were less than 1% and had little impact on Thomas High Schools ranking in the district.
