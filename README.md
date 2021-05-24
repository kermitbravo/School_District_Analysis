# School District Analysis

## Overview of the school district analysis

The purpose of the analysis performed was to account for the academic dishonesty incident reported in the Thomas High School. After correcting the scores for both math and reading we will perform another school district analysis using ~Pandas~ to analyze how these changes affected the overall analysis.

## Results

After correcting the analysis by removing the number of students in the Thomas High School along with their grades we can see that there is a small change in the following calculations: 

### School District Analysis Summary Impacts

Below is an analysis of the changes caused by adjusting the scores on the 9th Grade at THS where applicable. 

### District Summary 

We can observe some small percentage changes like the ones below: 

- The % Passing Math decreased from 74.9 to 74.8%
- The % Passing Reading decreased from 85.8 to 85.7%
- The overall passing % decreased from 65.17 to 64.9 %
- The total number of total students used in the analysis decreased by 416 students hence affecting the percentage calculations but no significantly given that the population is of 39,170	students which represents ~ 1.06% of the students.

### Top & bottom lists

This ranking didn't get affected really since the list of high performing schools still remained the same although the numbers for THS did suffer a small % reduction on the overall passing percentage of ~.31%: 

Top
1. Cabrera High School
2. Thomas High School
3. Griffin High School
4. Wilson High School
5. Pena High School

Bottom
1. Rodriguez High School	
2. Figueroa High School	
3. Huang High School	
4. Hernandez High School	
5. Johnson High School

The change in the score percentage wise wasn't enough to change the rankings. 

### The Math & Reading Scores by Grade

This is the one metric where the biggest impact of removing the 9th grade scores. Given that we didn't add back grades for the 9th grade the Math & Reading score average is still showing NaN which makes it impossible to compare to its previous value.

### Scores by School Spending

No real impact on this metric due to the grades as they're not relevant for this analysis. This is more a function of budget and number of students. 

### Scores by School Size

No real impact on this metric due to the grades as they're not relevant for this analysis. This is more a function of number of students. 


### Scores by School Type 

No real impact on this metric due to the grades as they're not relevant for this analysis. This is more a function of the type of schools. 

## Summary

After performing the adjustments an analyzing the impacts of the changes performed we can conclude that although we made our dataset incomplete and we did affect the Math & Reading scores analysis, the change in the data was small given that it only affected ~1% of the student population that it's not significant enough to reduce the trust in the numbers published. 

We did observe some small percentage changes on the % of Pass grades but it was a very small change as noted in the section above. The rankings remained unchanged as noted in the previous section of the analysis. It is important to note that given that we decided to use "NaN" as a value some mathematical calculations specific to the 9th grade were not populated which as I mentioned above might not be the best approach. We could've replaced the numbers with "Zeros" instead of NaN and then published the 9th grade analysis with a footnote to explain that the statistic didn't include THS in it.
