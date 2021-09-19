# Kickstarting with Excel

## Overview of Project
Review outcomes of plays based on launch date and goals. 

### Purpose
Determine and visualize the successful, failed, and canceled play projects to show coutcomes based on launch dates and funding goals.

## Analysis and Challenges
Below you will find a list of analysis and some challenges faced when retrieiving the data.

### Analysis of Outcomes Based on Launch Date
Initial analysis of outcomes based on launch date shows the there is a higher success rate between the months of April and July. 
The failed plays seem to mimic the pattern of the successful but there were more successful plays than failed.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/90691846/133946663-266680ae-883e-45ea-964e-689d94c62e4b.png)

### Analysis of Outcomes Based on Goals
Initial analysis of outcomes based on goals shows the larger the goal the more apt for the play to fail.
There is a higher percentage of failed plays than successful in the range between 15000 to 35000 and greater than 45000.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/90691846/133946667-1ca25c84-b4c9-4d91-b168-01d3ee9575e4.png)

### Challenges and Difficulties Encountered
One challenge was using the COUNTIFS statement on the canceled plays. The result continued to bring back a 0 value. 
After verifying that there were no canceled plays, it was determined the calculations were correct.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. May is the most successful month with over 100 successful plays.
2. December has a proportionate number of failed and successful plays and is the lease successful month.

- What can you conclude about the Outcomes based on Goals?
The larger the goal the higher percentage of fail rate.

- What are some limitations of this dataset?
Could get a better look at the numbers if we look at the duration of each play.
There is a breakdown by month but a deeper analysis to a particular year can provide insight especially in the current timeframe where there are unaccounted to influences, like COVID, that could skew the numbers.

- What are some other possible tables and/or graphs that we could create?
1. Outcomes for a specific year based on goal.
2. Outcomes based on tenure of play.
3. Outcomes of based on the amount of backers and the amount pledged.
