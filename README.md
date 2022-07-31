# PycitySchools Analysis
## Overview of the school district analysis:
The purpose of this analysis is to clean academic dishonesty data, and present a new school district analysis with updated grades. We have replaced the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. We will also look at the overall math and reading scores for all grades, see if there are any changes after we replaced the 9th grade data.

## Results:

- How is the district summary affected?

In the district summary, the average math score dropped 0.1, average reading score stayed the same. 

- How is the school summary affected?

The overall math passing percentage with cleaned data shows 74.8%, where as the old data shows 75.9%. The overall reading passing percentage with cleaned data also dropped to 85.7%, the original precentage was 86.8%. The overall passing percentage also decreased by 1%.
![test](../Resource/Summary.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

After dropping the data, Thomas High School's average math and reading score was still similar, but the math passing percentage decreased from 93.8% to 66.9%, thier reading passing percentage dropped from 97.3% to 69.6%, the overall passing percentage is now only 65%, which was 90.9% before.

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade: 

Grade 9: Thomas High School's Grade 9 scores are now null, all other schools' data stay the same.
Grade 10-12: No change.

  - Scores by school spending: the numbers are identical, since Grade 9 score of Thomas High School is a small portion of all data.
  - Scores by school size: no change
  - Scores by school type: no change

## Summary:
We found 4 major areas in the new analysis where data has changed:
- Significant decrease in the Math and Reading passing percentages, because the 9th Grade scores are now 0, it affected the mean.
- The overall passing percentages of Thomas High school has been affected, it had the highest passing grade with uncleaned data, but now the passing percentage is only 65%.
- Average Math and Reading scores have decreased, but not by alot since there are many other school's data included in the total summary.
- Thomas High School's 9th grade scores are now null.
