# School_District_Analysis
Analysis of school district data using Python and Jupyter notebook

## Overview of the Analysis:
### Purpose
After I had completed a full analysis on the data for schools within the district, the school board came to me with a special request. According to some of the data I had cleaned, there was evidence of academic dishonesty in test scores for Thomas High Schools ninth grade class. The school board asked for my help in replacing the math and reading scores with NaN’s (not a number). After I sorted those scores out, they wanted me to run another analysis on the data again and describe what I found!

## Results
Once the cleaning, nulling, and recalculating was complete, I noticed how this process affected 7 key metrics within the school district data. 

The results of the analysis came by process of turning the data from the 9th grade class at THS and making them NaN (not a number). From there I was able to determine exact percentages and averages for math, reading, and overall passing based off the data that was still viable. However, the overall number of students remained the same even though I still went in and changed over 400 9th grades test scores.

### 1. District Summary:

#### Before Recalculating:

<img width="469" alt="image" src="https://user-images.githubusercontent.com/96212660/153080211-ac3c7420-b891-44fa-8fca-8960b8caf765.png">

#### After Calculating:

<img width="468" alt="image" src="https://user-images.githubusercontent.com/96212660/153080247-c16042a7-3cc4-42a5-b79b-6a211b93fc09.png">

Looking at the 2 data frames, by removing the THS students, there was a little bit of an effect on some of the scores, but nothing more drastic than even 1%. That is because there are 39,170 students overall and not even 500 scores were recalculated as NaN.

### 2. School Summary:

#### Before:

<img width="468" alt="image" src="https://user-images.githubusercontent.com/96212660/153080485-a7065a71-f22a-415d-8028-506e187508a2.png">

#### After:

<img width="469" alt="image" src="https://user-images.githubusercontent.com/96212660/153080519-6f0bba84-1250-4940-a559-46fc025c1f4a.png">

THS originally was responsible for holding a 90.6% passing rate. However, once I cleaned and adjusted the scores (removing the 9th graders) were see the overall passing rate drop 26% to a 65% passing rate.

### 3. Thomas High School vs. Other Schools:

#### Before:

<img width="468" alt="image" src="https://user-images.githubusercontent.com/96212660/153080667-7cd26516-c23a-4a6a-b0d6-cccb7729c8f0.png">

#### After:

<img width="468" alt="image" src="https://user-images.githubusercontent.com/96212660/153080694-c4a3497b-1e58-438c-9514-da2f5dbf6454.png">

THS originally was ranked 2nd overall in the district! But once the changes were made THS dropped to the middle: 8th out of 15 schools.

### 4. Math and Reading Scores by Grade:

In the initial analysis, the data show that THS had test scores around 83% for reading and math, once I went in in NaN the 9th graders scores, this is what we get for my new data frame:

<img width="311" alt="image" src="https://user-images.githubusercontent.com/96212660/153080815-d225cc0f-3038-4fbb-8757-f975de48fb85.png">

### 5. Scores by School Spending:

THS stayed in the $630-$644 spending per student. The differences were minimal and had little to no effect on categorization.

### 6. Scores by School Size:

THS stayed classified as a medium sized school before and after the changes were made. Although the score were NaN, the overall student count did not change.

### 7. Scores by School Type:

THS is classified as a charter school, although the changes were made to the scores, as we saw in i.e. spending and District Summary, the changes were almost to nothing!

## Summary:

While my analysis for the recalculating of the data for the school board proved to be successful, I would like to highlight 4 changes to the overall school district analysis that were evident once the reading and math scores were replaced with NaN’s in my new data frames.


- The overall passing in THS dropped 26% (originally was 91%, after the changes were made it went down to 65%)
- The overall status of THS went from being the 2nd highest ranking school (in terms of test scores and overall passing) to the middle 8 of 15 schools.
- In the district summary, the average math scores increased .1%
- In the district summary, the % passing reading increased about .3%







