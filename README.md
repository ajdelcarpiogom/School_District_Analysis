# School_District_Analysis

### Overview of the School District Analysis

The purpose of this analysis was to find passing percentages of both reading and math scores from the file of students given, considering the situation that the reading and math grades for Thomas High School 9th graders have been altered. We decided to void them in order to prevent false information from interrupting our most accurate analysis by replacing them with "NaN". We then continued our analysis we did in the PyCitySchools.ipynb in order to determine whether those grades affected the overall analysis for Thomas High School and comparing it to the other High Schools.

### Results

#### How is the district summary affected?
When looking at PyCitySchools and PiCitySchools_Challenge, we can see that removing the 9th graders did not affect the district summary.

#### How is the school summary affected?
Thomas High School decreased in overall passing percentage by ~25% after removing 9th graders from its results.

#### How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
When assessing average scores and passing percentages among the 15 high schools in the school district, the average math score dropped .1, the average reading score stayed the same, the percentage passing math dropped .1%, the percentage passing reading dropped ~.3 %, and the overall passing percent dropped ~25%. Thomas High School didn't change places in rankings and is still 2nd place.

#### How does replacing the ninth-grade scores affect the following:
  - math and reading scores by grade: 9th graders now have an NaN rather than a score.
  - scores by school pending: Score doesn't nearly change after nullification.
  - scores by school size: The overall passing percentage did not change.
  - scores by school type: No change.

### Summary

When reviewing the School Spending summary, this data change did not impact the spending ranges for either the average math scores or average reading scores but it did change when referring to the impact the spending ranges for passing percentages. According to the summary, there was a 6% decrease in % passing math, a 7% decrease in % passing reading, and a 6% decrease in % overall passing in the $630-644 spending range.
When reviewing the School Size summary, removing the ninth grade scores did not affect the average math and reading scores, but it did affect the passing percentages for medium-sized schools (1,000-2,000). In this category, % passing math, % passing reading, and % overall passing dropped 6% each. Before the data change, medium sized schools were first at an overall passing percentage of 91% and have gone down to 85% in second place.
In reviewing the last summary on School Types, this data change also affected the passing percentages that compared charter and district schools but with a decrease in reading, math, and overall, Charter schools still scored higher than District schools.
