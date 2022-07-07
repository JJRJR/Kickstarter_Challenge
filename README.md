# Kickstarter_Challenge
Submission of the Weekly Assessment for the Kickstarter campaign. Module 1

## Overview of Project

### Purpose
The purpose of this project is to discover how different kickstarter campaigns perfomed compared to their launch dates and funding goals.This should provide a clearer picture for Rose on when to lanuch her kickstarter play and what goal will give her the best chance for success. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
For the first challenge I created a Pivot table and chart with the parent category and years as the criteria. 
https://github.com/JJRJR/Kickstarter_Challenge/blob/main/Theater_Outcomes_vs_Launch.png. After review I would recommend that Rose launch her campaign sometime between May and June. Those two months seem to have the highest level of success. You could make the argument that summer in general would be a good time to launch however earlier in summer would give you the best chance.

### Analysis of Outcomes Based on Goals
The second challenge required that I create a range table so we can determine successful, failed, and canceled plays based on the funding goal amount. I pulled the corresponding data from the kickstarter campaigns that were plays in the US by filtering outcomes, country, and sub category. I used the COUNTIFS function =COUNTIFS('Successful Plays'!$D:$D, "<1000") to fill in the ranges on the Outcomes based on Goal table. Once I was able to fill out the ranges completely I created a pivot table using successful, canceled, and live percentages as the columns and goals for the rows. I used this data to create the following chart to easily identify which goals had the most and the least amount of successful campaigns.
https://github.com/JJRJR/Kickstarter_Challenge/blob/main/Outcomes_vs_Goals.png The most successful goal range by percentage is the $35000 to $39999 range, however there were only 5 total projects launched with that goal. The optimal goal would be the $1000 to $4999. This range also gives you a high percentage of success but with a higher amount of successful campaigns.

### Challenges and Difficulties Encountered
One of the challenges I ran into was making sure the functions were typed accurately with zero errors. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    - The best month to launch a kickstarter theater campaign is in May.
    - The worst month to launch a kickstarter theater campaign is in October.
- What can you conclude about the Outcomes based on Goals?
    - The easiest range to set for and attain a campaign goal is the $1000 to $4999 range.
    - The $35000 to $39999 range has the highest success rate based on percentage.
- What are some limitations of this dataset?
    - We aren't able to see when the successful goal amounts were launched. 
- What are some other possible tables and/or graphs that we could create?
    - Successful theater/plays goals vs date created conversion.
