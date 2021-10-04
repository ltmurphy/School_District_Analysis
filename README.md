# School District Analysis

## Overview of School District Analysis:
### The purpose of this analysis was to examine multiple school districts on different key points using Pandas and Jupyter Notebook while compensating for academic dishonesty. Various DataFrames will be used to isolate the specific data deemed fraudulent, in this case the math and reading scores from Thomas High School's 9th grade. This data is then removed from the DataFrame to allow for a more accurate depiction of the district levels. The remaing scores for the 9th and those for the other grades are then evaluated against school spending, size, and type.

## Results:
   * How is the district summary affected?
   * This is the district summary before removing the fraudulent grades: 
   * ![image](http://localhost:8888/notebooks/PyCitySchools_Challenge_testing.ipynb#:~:text=Out%5B196%5D%3A-,Total%20Schools,65.9,-School%20Summary)
   * This is the district summary after removing the fraudulent grades:
   * ![image]
   * As you can see, the district summary was not affected at all by the removal.
   * How is the school summary affected?
   * This is the school summary before removing the fraudulent grades:
   * ![image]
   * This is the school summary after removing the fradulent grades:
   * ![image]
   * Here the percent passing math, percent passing reading, and percent overall passing at Thomas High School are affected by the removal, decreasing slightly.
   * How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
   * As you can see below, the performance of Thomas High School compared to the others was changed, if only slightly.
   * Before: ![image]
   * After: ![image]
   * How does replacing the ninth-grade scores affect the following:
   * Math and reading scores by grade
   * Both math and reading scores are unaffected:
   * Math before: ![image]
   * Math after: ![image]
   * Reading before: ![image]
   * Reading after: ![image]
   ** the longer decimal in the before images equals the shortened one in the after images
   * Scores by school spending
   * unchanged with supporting pictures
   * Scores by school size
   * unchanged with supporting pictures
   * Scores by school type
   * Changes were observed in the percent passing for math and reading in the charter type as well as percent overall passing. The numbers again decreased slightly
   * supporting pictures.

## Summary:
### Four changes in the updated school district analysis after the reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs:
* I only observed 2 noticable changes. verify and compare
