# Kickstarting with Excel

## Overview of Project
The purpose of this project to assist a client in determining the best conditions for a favorable fundraising campaign. 

### Purpose
Our client, Louise, wants to fund kickstarter event for her play, Fever with an estimated budget of $10,000. She is seeking advice in order to run a successful campaign. We have determined that a review of previous kickstarter events may provide insight.  Data of a variety of campaigns can be reviewed and analyzed to suggest the best way to run a successful campaign. Then, Louise may be able to use that information to set up her campaign. 


## Analysis and Challenges
A dataset of 4,115 campaigns were analyzed to look for trends that may have impacted performance.  The campaigns were classified based on multiple parameters, including: amount of goal, amount pledged, outcome, date started, date completed, category of event, country located, and the number of backers. 

Analysis was performed using Excel. 
For a visual inspection of the large dataset, the column for Outcomes was conditional formatted to show different colors for "successful", "failed", "canceled" and "live".  The color output provides an ability to quickly scan large datasets to see if any trends are obvious. 

A column was added to calculate **percentage funded**, using the formula: '=ROUND(E2/D2*100,0)', where E was the amount pledged and D was the amount of the goal.  The percentage funded is a way to measure the success of a campaign rather than just the pass/fail criteria of successful or failed.  Our client wants the best scenario for a successful campaign so understanding relative success is important. 

 

### Analysis of Outcomes Based on Launch Date

Starting and ending dates of each campaign was provided.  The dates for the theater campaigns were graphed based on the starting month of the campaign to look for trends.  The graph shows distinctive trends in the success of the campaigns.  Those campaigns started in April through July had a much higher success rate than those campaigns started in September through December. 

![Outcome_vs_Launch](https://user-images.githubusercontent.com/98054953/156898860-ca4f18f2-32be-4753-aa89-0c23aedd6552.png)



      
    

### Analysis of Outcomes Based on Goals

To determine if the amount of support requested in the campagin affected the outcome, the succes was evaluated against the stated goal.  For campaigns with a goal of less than $15,000, more campaigns were successfull than unsucessful.  The lower valued campaigns were more successfull and the success rate decreased as the value of the goal increased. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/98054953/156898832-7083c62b-ec42-4024-9feb-e10444bb1fac.png)

It is important to keep in mind the number of campaigns in each category when evaluating the success.  There are many more campaigns with goals of less than $15,000 (661 of the 688 campaigns evaluated).  At the higher campaign values, one or two campaigns that fail can skew the data. The table below shows the goal for each campaign and the number that were successful, failed or canceled.  

![SuccessofTheaterData](https://user-images.githubusercontent.com/98054953/156897426-efe06816-32c9-43e6-8ec4-bac575ed5612.png)


### Challenges and Difficulties Encountered

The dataset of Kickstarter campaigns provided a lot of useful information for the question Louise is trying to answer. Challenges that were encountered with the dataset include: 

1. Checking the dataset for errors in calculating average donation per campaign. The dataset includes failed and canceled which had zero contributors and would result in an error when calcuating average donations. 
2. The dataset includes campaigns from multiple countries.  To ensure that we are comparing similar events, the data was filtered to show events in the United States. There could be multiple reasons why campaigns in different countries have different success rates. 
3. The campaigns range from film to food trucks to childrens books. It is possible that these campaigns are too varied to provide useful information on how to conduct a successful campaign for plays. Therefore, the data was filtered to show the campaigns for the parent catergory of theater and, for some analysis, the subcategory of plays.  That filtering provides the most relevant data. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?


1. The campaigns that were started in April through July seemed to have the highest success rate. 
2. The campaigns that were started between September and December appeared to have the lowest succss rate. 

For Louise to have the best chance of sucessful campaign, then a start date between April and July seems to be the best advice. 


- What can you conclude about the Outcomes based on Goals?

There appears to be a high correlation between campaigns with a goal of less than $15,000 and the chance of that campaign being successful.  For campaigns greater than $15,000 there is mixed data indicating that there are some high value campaigns that are success and an equal or greater number of campaigns that failed. It is less common for the high value goals to be successful.  For Louise to have the best chance of a successful campaign, I would recommend a goal of less than $15,000.

- What are some limitations of this dataset?

There are many factors which could make a fundraising campaign sucessful that are not captured in the dataset.  The evaluation of Outcomes based on Launch Data includes data across multiple years. There may be conditions in different years that affect whether a campaign was successful.  The dataset does not take into account the history of an organization, its network, its marketing ability.  All of those factors would weigh heavily in whether the campaign was successful. 


- What are some other possible tables and/or graphs that we could create?

Other possible graphs or table that would provide additional insights include: 
- Graph of Outcomes based on Launch data seperated by year
- Graph of the Descriptive statistics of Mean Goals vs Mean Pledged

