# Kickstarter Challenge

## Overview of Project
Louise looked to plan the next fundraiser for T Education Fund in collaboration with ZZ Theather Company and hired XYZ freelancer to gather insights from historical fundraising campaign data to inform such plan. 

### Purpose
Specifically, Louise needed XYZ freelancer to identify the optimal month and donation goal for the next fundraiser.  

## Analysis and Challenges
XYZ freelancer thus looked for trends from historical fundraising campaign data to detect the optimal month and donation goal for the next fundraiser.  

### Analysis of Outcomes Based on Launch Date
To detect the optimal month, XYZ freelancer performed the following: 
- Gathered all successful, failed, and canceled theater foundraising campaigns ran by T Education Fund from 2009 to 2017
- Grouped all successful campaigns by campaign launch month
- Grouped all failed campaigns by campaign launch month
- Grouped all canceled campaigns by campaign launch month 

Here's the graph to visualize the analysis: 
![](images/Theater_Outcomes_vs_Launch.png)

From this graph, you will see the following: 
- May is the month with most successful campaings.
- Successful campaigns surpass failed campaigns in every month, and the range between successful and failed campaign is greatest in May. Thus, success rate is greatest in May. 

These findings position May as the optimal month to launch the next campaign. 

### Analysis of Outcomes Based on Goals
To detect the optimal donation goal, XYZ freelancer performed the following: 
- Grouped successful, failed, and canceled play fundraising campaigns to buckets of dollar donation price ranges 
- Calculated the percentage of successful, percentage of failed, and percentage of canceled on each dollar donation price range bucket

Here's the graph to visualize the analysis: 
![](images/Outcomes_vs_Goals.png)

From this graph, you will see that less than $1,000 donation has the highest success rate and lowest failure rate. Based on this criteria alone, less than $1,000 donation is the optimal donation goal range. 

### Challenges and Difficulties Encountered
Attention to detail of the raw data was the biggest challenge faced in this analysis. This raw data contained donation goals in 13 different currencies. These had to be converted to USD to perform the analysis of outcomes based on goals. Failure to convert currency would have resulted in flawed results.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    - May is the month with most successful campaings.
    - Successful campaigns surpass failed campaigns in every month, and the range between successful and failed campaign is greatest in May. Thus, success rate is greatest in May. 

- What can you conclude about the Outcomes based on Goals?
    - Less than $1,000 donation has the highest success rate and lowest failure rate. 

- What are some limitations of this dataset?
    - Currency conversion rates used in this analysis are present day rates (as of 7/18/20). Yet, the dataset spans 8 years; currency conversion rates have fluctuated during these years. Thus, currency conversion rates used in this analysis are estimates but not precise. 

- What are some other possible tables and/or graphs that we could create?
    - A bar graph could be created in addition to Theater Outcomes Based on Launch Date graph to showcase the successful campaign with most quantity. This graph would be useful to take away the noise of failed and canceled campaign data present with the line graph. At the end of the day, what we want to showcase is the month with highest quantity of successful campaings. 
