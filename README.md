# Kickstarting with Excel

## Overview of Project
Louise is interested in fundraising money for a future play she would like to create. She is interested in Kickstarter data so she can understand the outcomes of different campaigns based on their launch dates and their funding goals. 
 
### Purpose
The scope of this project is to analyze Kickstarter data for Louise, and provide her with an evaluation of the data so she can understand the most optimal time to launch a campaign and funding goal.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Using a pivot table and chart used the Parent Category "Theater" and Years as filters I was able to determine the number of successful, failed, and canceled campaigns based on the month they were launched. A total of 1,369 campaigns fall under the specified filters. The majority of the campaigns were successful with 839 (61.3%) successful campaigns, 493 (36%) failed campaigns, and 37 (2.7%) canceled campaigns. 

May is the month with the most total launched campaigns with 166 campaigns launched. It is also the month with the most succcessful campaigns with 111 being successful. Month over month, from May to September there is a negative trend of successful campaigns. The number of successful campaigns decreases at an average of 13 campaigns from May to September. However the number of failed and canceled campaigns remains consistent averaging 46 and 5 respectfully. July actually sees a decrease in canceled campaigns compared to the average of this timeframe with only 1 campaign being canceled. Overall the total of launched campaigns decreases from May to September which appears to be the main driver of the reduction of successful campaigns. Rather than the reduction being driven by an increase in failed or canceled campaigns. 


![](/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

I created a table using the CountIfs function to sort out the number of campaigns that succeeded, failed, and were canceled. I used the Subcategory "Plays" and twelve unique funding goal ranges as filters I was able to determine the number of successful, failed, and canceled campaigns. Along with the respective percentages. In total, 1,043 Plays were examined. The majority of plays (51.1%) had a goal between $1,000 and $4,999. Overall, Plays averaged a percent successful rate of 46% and a percent failure rate of 54%. There were no canceled campaigns across any of the goal ranges. 

Plays had the highest rate of success (76%) when they had a goal less than $1,000. Plays with a goal range $1,000 to $4,999 had a similar rate of success at 73%. 

Plays with a goal range $45,000 to $49,000 had the highest rate of failure (100%). Followed by Plays with a goal greater than $50,000 (83%) and goal range $25,000 to $29,000 (80%). 

Plays with a goal in the rage of $15,000 to $19,000 had a success rate of 50% and a failure rate of 50%. Plays with goals between the ranges of $35,000 - $39,000 and $40,000 - $44,999 had the same success rate (67%) and failure rate (33%).

![](/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

One challenge that arose while creating the table for Outcomes Based on Goals was the CountIfs formula. As I copied the formula to all the cells, I initially updated the wrong part of the formula so some cells were no longer filtered for "plays" but rather the outcome. This returned the wrong value, however it was fixed after I double checked my formulas. Potential difficulties that could have been encountered would have been:
* Being unable to add the correct filters to the pivot table for Theater Outcomes based on Launch Date
* Being not able to sort the Launch Date table columns in descending order
* Not being able to extract the Year from the Date Created Conversion column

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

One conclusion that can be drawn is that May is the most optimal month to launch a campaign and December is the least optimal month to launch a campaign. Also while successful campaigns seem to be impacted by time of the year, the rate of failure is not seasonly affected. Since the number of failed campaigns remains consistent it is not affected by time of year. 

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
