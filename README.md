# School_District_Analysis
## Overview of the school district analysis

The purpose of the analysis was to assist Maria and the school board to reference two separate data sets to identify the average math and reading scores for 9th-12th graders in their district.  After creating the prework, we were made aware that there was academic dishonesty in the 9th grade class for Thomas High School.  With this news, we refactored the code to remove the 9th grade Thomas High School students.

## Results
### How is the district summary affected?
    - This played a factor in the district summary due to the results being incomplete as we had to remove 461 students from our data set.  This is not giving us full results of the districts student population by removing these data points.
### How is the school summary affected?
    - In the final results we did not factor in any of the Thomas High School scores.  We replaced these with NaN and you will see that in the final results that they receive no scores.  This also played a factor in the final overall scores for Thomas High School and we saw an increase in their overall scores for each of the Math, Reading, and overall totals passing.
    - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
### How does replacing the 9th graders scores affect the following:
    - math and reading scores by grade
        - did not affect any schools other than Thomas High School, which received no score do to removing their scores and replacing all with Nan.  All other school and grades were unaffected.

        
    - Scores by school spending
        - Thomas High School was classified in our $631-645 bin size.  This bin saw a decrease in % passing accross the board.  All other sizes were not affected.
    - scores by school size
        - Small and Large school sizes were not affected.  Thomas High School was categorized as a "Medium" school and they experienced a decrease in % passing in all categories.
    - scores by school type
        - the charter schools saw a decrease in % passing scores as Thomas High School was listed as this Type.  District school types were not affected.

## Summary

Overall, not a lot of our categories were affected by replacing the Thomas High School 9th grade scores with NaN's.  The class size was only 461 students, just a little over 1% of the total amount of students tested.  While it didn't affect all analysis the replacing of these scores did heavily change our data on scores by grade, our $631-645 spending bin, "Medium" school size, and the "Charter" school analysis.  Even though a small sample size, these figures did change and sway our overall total results in these featured data points.  
