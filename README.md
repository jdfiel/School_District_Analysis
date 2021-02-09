# School_District_Analysis
Python 3.7

## Overview of Project

### Purpose
The purpose of the analysis is to develop an unbiased assessment of the academic performance of the schools, independant of the tampering of the 9th Grade students at Thomas High School.

### Results
Replacing the ninth-grade math and reading scores produced the following results. The district summary and per school summaries have also been included for visibility.

#### Figure 1. District Summary
![District Summary](https://github.com/jdfiel/School_District_Analysis/blob/main/Resources/district_summary.png)

#### Figure 2. Adjusted District Summary
![Adjusted District Summary](https://github.com/jdfiel/School_District_Analysis/blob/main/Resources/adjusted_district_summary.png)

- Looking at the District Summaries, we can see that the overall passing percentages and the average math score decreased slightly. Considering that the ninth graders were not removed from the overall district population, this is not surprising.

- The Per School Summaries indicates that the Thomas High school averages jumped significantly once the ninth grader scores were removed, suggesting that a significant portion of the ninth graders were failing. This would explain why the District passing values were not significanlty impacted despite the ninth grade population not being removed, as most of them were failing in the first place.

- Relative to the other schools, removing the ninth grader marks places Thomas High School amongst the top performing High Schools

- The Math and Reading score data frames remain the same, with the exception of the ninth graders of Thomas High School, who show as 'nan' for both the Reading and Math Scores by Grade data frames.

- Scores by School Spending did not show any significant changes

- Scores by School Size did not show any significant changes

- Scores by School Type did not show any significant changes

### Summary

The adjusted District School Summary shows that the ninth graders were severely lowering Thomas High School's grades. The removal of the ninth graders, by replacing their values with 'nan', caused Thomas High School's overall performance to be comparable with the top schools - jumping from ~60% to ~90%.

The scores by grade data frames show that the ninth grader grades have all been replaced with 'nan'. It is interesting to note that the scores by grades are nearly ~10% lower than the consolidated score.

The lack of changes for the Scores by School Spending, Size and Type show that the removal of the ninth Graders was insignificant enough to provide an accurate representation of data while preserving data integrity.

