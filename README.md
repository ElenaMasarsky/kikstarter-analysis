# Kickstarting with Excel

## Overview of Project
This project shows how different kickstarting campaigns fared in relation to their launch dates and their funding goals.

### Purpose
We are helping an up-and-coming playwright, Louise, who wants to start a crowdfunding campaign to help fund her play, Fever. She's estimating a budget of over $ 10,000 and is hesitant about jumping into her first fundraising campaign. We are using Excel to organize, sort, and analyze crowdfunding data to determine whether there are specific factors that make a project's campaign successful. We use these insights to help Louise plan her own and set it up for success. Using Excel to analyze current site data, we help her gain a greater understanding of campaigns from start to finish, and we set her campaign to mirror other successful ones in the same category.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
1. First a new column was added with a use of YEAR() function in the Kickstarter_Challange.xlsx workbook.
2. Then pivot table was created in a new sheet using criterias we needed for the count outcomes and filtered by Category and Years.
3. The column "live" was filtered off from the pivot table because outcomes of these campaigns are unknown yet and they will have impact on reliability of our analysis.
4. The campaign outcomes were sorted in descending order so "successful" goes first.
5. The line chart was created to visualize the relationship between outcomes and launch month.

Our analysis shows that pic of campaign comes on May and June.

<img width="316" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/107229639/174415158-a4a6361f-f850-4126-95da-c29c4c193470.png">

### Analysis of Outcomes Based on Goals
1. A new table was created in a new sheet to count outcomes and percentage of outcomes for successful, failed and cenceled campaigns by dollar-amount ranges. COUNIFS() formula was in use.
2. The line chart was built to visualize the relationship between the goal-amount ranges and the percentage of successful, failed, or canceled projects.

These analysis show us how success of campaigns depends on it's goals.

<img width="508" alt="Outcomes_vs_Goals png" src="https://user-images.githubusercontent.com/107229639/174415171-409acf39-a5aa-46be-b628-67999fb4d6b3.png">

### Challenges and Difficulties Encountered
When I was working with COUNTIFS formula I wanted to ease my work by pasting my first formula to all cells I needed and then just change arguments. For most of the cells it worked but for some celles it gave me an error. So I had to delete them and start from the beginning applying formulas for that particular cells manually.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? 
1. The value of canceled projects in theater/plays category tends to zero.
2. The most successful months to launch the campaign are May and June.


- What can you conclude about the Outcomes based on Goals?

According to analysis of the pivot table and the graph the most successful outcomes show campains with goals less than $5,000. The projects with goals
between $35,000 and $50,000 also showed high percentage of success. But they are only few. So it's hard to predict outcome based on this numbers.
Louise estimated her budget of over $10,000. Probably she might consider if it's possible to reduce her budget. 

- What are some limitations of this dataset?

In Theater Outcomes by Launch Data analysis the difference between successful and failed campaigns is not obvios. I would add the columns showing results
in percentage to emphasize relatons between these outcomes.
This data set doesn't show us for failed campains how much in average pledged ammount did not reach the goal and how much in average pledged ammount
for successfull campaigns overreached the goal. Obviosly some campaigns were close to the goal. 

- What are some other possible tables and/or graphs that we could create?

I whould add columns showing percentage of successful, failed and canceled campaigns into the Outcomes by Launch Date pivot table.

