# School District Analysis

## Project Overview
A school board shows evidence of academic dishonesty in a high school where the math and reading grades for a certain grade have been altered.

1. Replace ninth-grade math and reading scores.
2. Redo analysis with new data changes.
3. Describe how the overall analysis has been changed.

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Jupyter Notebook

## Summary
The analysis of the district show that:
- The district summary was affected by showing the following:
  - A decrease of 0.1 points in Average Math Score
  - A decrease of 0.2 points in % Passing Math
  - A decrease of 0.3 points in % Passing Reading
  - A decrease of 0.1 points in % Overall Passing
- The school summary was affected by showing the following:
  - A decrease of 0.67412 points in Average Math Score
  - An increase of 0.47152 points in Average Reading Score
  - A decrease of 0.86481 points in % Passing Math
  - A decrease of 0.290130 points in % Passing Reading
  - A decrease of 0.317688 points in % Overall Passing

Replacing the 9th graders scores didn't affect Thomas High School's performance relative to the others schools. It stills sits in second place for top five schools.
It did change however the input score for Thomas High School's ninth grade with a "nan" replacing the previous value of 83.6 and 83.7 for math and reading, respectively.
There no changes to the scores by school spending, school size, and to school type.
  
## Challenge Overview
This analysis was interesting to do for the simple reason that it helped me understand that how to further use .loc and .groupby. It was quite the learning experience to find out why either function was not working correctly due to either a punctuation mistake or misplaced entry.

## Challenge Summary
The changes to the analysis are the decrease in points for % Passing Math, % Passing Reading, and % Overall Passing for bothe the district and school summary.
