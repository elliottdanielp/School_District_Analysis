# School_District_Analysis

## Overview
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Results:

### How is the district summary affected?

#### Original Analysis:
![original_analysis](https://user-images.githubusercontent.com/106495422/177372970-83e798f6-bd89-485c-9fd1-8119ef943c93.png)

#### Updated Analysis:
![updated_analysis](https://user-images.githubusercontent.com/106495422/177373040-16cb6798-3660-42e6-89d5-0ef6eda8066b.png)

When comparing the Orginal and Updated, removing the test scores of the 9th graders from Thomas High School had very little impact on the almost 40,000 total students.

### How is the school summary affected?

In the original analysis, Thomas High School started with a 91% overall passing rate. After calculating the total number of 10th - 12th grade students the rest of the testing data was adjusted accordingly.

#### Orginal Analysis Including 9th grade:
![ths_including_9th](https://user-images.githubusercontent.com/106495422/177381803-c173f7d5-c523-4c71-bef9-55502de67fce.png)

#### Adjusted Analysis without 9th grade:
![ths_minus_9th_overall](https://user-images.githubusercontent.com/106495422/177381937-f625312d-6a46-47e6-84ce-60fd6c042bf0.png)

By droping 9th grade from the DataFrame the overall passing rate took a big hit by going from 91% to 65% overall passing as seen in the screen shots.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Overall it does not affect the perfromance relative to the other schools. Thomas High School was one of the best performing schools in the district. Both with and without the 9th grade scores, Thomas High School is the 2nd highest performing school in the district based upon percentage of students overall passing, so again there isn't really impact resulting from dropping the 9th grade scores.

### How does replacing the ninth-grade scores affect the following: 
#### Math and Reading scores by grade.
#### Scores by school spending.
#### Scores by school type.

#### Math and Reading scores by grade:
There is no impact on any scores for reading or math, other than the scores that were removed. This is because the 9th grade reading and math scores from Thomas High School are independent data points relative to the entire data frame, meaning that changing them will have no impact on the other data in the data frame. As seen in screen shots below.

#### Reading Scores by grade:
![reading_scores_by_grade](https://user-images.githubusercontent.com/106495422/177392816-734a5b7d-45ff-4d2b-b472-317a891c90de.png)

#### Math Scores by grade:
![math_scores_by_grade](https://user-images.githubusercontent.com/106495422/177392881-caed1218-aa92-4011-a3fa-94b2e9fd81eb.png)

#### Scores by school spending:
Again there is no impact on the scores based off of school spending because we only droped 461 students from the almost 40,000 orginial students.

### Scores by school type:
Just like we saw with the school spending, dropping 9th graders from Thomas High School had no impact for the same reasoning

## Summary

Ultimately, dropping the 9th grade scores from Thomas High School that were impacted by academic integrity had very little (in most cases no) impact on the analyses Maria needed us to complete to help her team at the district office.
