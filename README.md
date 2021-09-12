# Additional Analysis of Kickstarter Crowdfunding Campaigns

## Overview of Project
A client came to us with a desire to initiate a crowdfunding campaign with a $10K budget for a play called "Fever".  The client provided a dataset containing crowdfunding projects for analysis to show trends on similar campaigns to help set the structure for a successful campaign.  Based on the analysis of similar campaigns a recommendation was provided.  The client initiated a crowdfunding campaign for the play "Fever”, and it came close to its fundraising goal in a short amount of time. Now, the client wants to understand how different campaigns fared in relation to their launch dates and their funding goals. 

### Purpose
Generate visualizations for campaign outcomes (successful, failed, canceled) based on their launch dates and their funding goals.  Present the conclusions drawn and any recommendations for further analysis. 

## Analysis and Challenges
A pivot table filtered based on the theater category and year was created to capture the theater outcomes (successful, failed, canceled) based on launch dates.  Another pivot table was created to capture the relationship of outcomes based on the campaign goals set for the crowdfunding campaigns. Charts were generated to visually show the theater outcomes based on launch date and the outcomes based on goals in order to present the conclusions from the analysis.  

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/89653470/132988273-7dfc2fc9-3fab-47a2-ac8f-344ab2dd0d04.png)

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/89653470/132988279-85ea01ca-9658-40a1-9523-b3e0aba3d98b.png)

### Challenges and Difficulties Encountered
Some minor difficulty was encountered with the initial generation of pivot tables and charts.  A quick review of readily available examples and material found vis Google was adequate to quickly overcome the initial challenge.  

## Results
- The summer months are the most popular months to launch new theater campaigns projects based on these months having the highest total of successful and failed campaigns. Theater campaigns launched in May and June have the highest number of successful campaigns with each month having twice as many successful campaigns as failed campaigns compared to other months.  January has twice the number of cancelations than any other month of the year.

- Campaigns with a goal greater than $45,000 fail at the very high rate of more %87 of the time.  On the other hand, campaigns with goals less than $4999 have the highest percentage of successful campaigns. 
 
- Additional data that would be valuable would be to plot the percentage of successful theater outcomes versus launch data to better visualize the success rate.  Additional data on the number of campaigns present in the data for each dollar range would be useful to identify any ranges that have limited data.  This could be plotted on the same chart give more context around the data to weed out any dollar ranges that may be based on very small sample sizes.    

- Some other possible plots to create would be the percentage of successful outcomes versus launch date, outcomes based on the number of backers, and donation amount of per backer.  The addition of filtering options to observe the impact of success rate based on country and other factors would provide additional insight on other influences on success rate.  
