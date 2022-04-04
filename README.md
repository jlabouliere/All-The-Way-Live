# All-The-Way-Live

## Overview
A dataset of 583 Funding Campaigns from 2009 to 2017 were analyzed by category and sub-category to discover trends in success rates for Live Performance projects.  The data was analyzed and charted for Outcomes based on Launch Date and Funding Goal for Theater categorized campaigns and Play sub-categories, respectively.

![image](https://user-images.githubusercontent.com/98665941/161452279-aa8fab60-4253-4244-810d-1319dacb0345.png)

![image](https://user-images.githubusercontent.com/98665941/161452328-1a578f49-e78d-49a3-81aa-be37dc13c189.png)

### Purpose: To determine the viability of future Funding Campaings for Live Performances analyzed on the basis of Theater Events by Launch Date and Plays by Funding Goal.  Outcomes of successful, failed and canceled were included.

## Analysis and Challenges

### Theater Event Outcomes by Launch Date
1,369 total Theater Events

Campaign Outcomes by Calendar month

Submissions and successful outcomes peak in May

36% of Successful Campaigns in May - July

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/98665941/161453073-ab8c9c1b-ae6f-43ab-88bd-18e9eac1bd6b.png)


### Plays Outcomes by Funding Goal
Goals assessed at below $1,000 and then increments of $5,000 up to $50,000 with a final grouping of $50,000 and over

1,047 total Plays Campaigns

85% of Goals under $10,000

Average 68% success rate for Campaigns with Goals under $10,000

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/98665941/161453425-54b859d4-e3bb-49a8-9370-0b4a07d444b4.png)

### Challenges
Nesting the COUNTIFS() syntax properly and including "" for numeric values required some additional research.  For the Plays Campaigns, properly incorporating the "</>=value" was missed and the total campaigns were not matching up to the data at first.

## Results
Based on the analysis, Theater campaigns tend to have more succes when started between May and July.  These months do have the highest rate of Campaign submissions, but the overall success rate is higher than the rest of the year.

Goals based analysis shows a distinct preference for Plays Campaigns with funding goals under $10,000 in terms of successful funding and submission.  Campaigns under $10,000 average a 68% successful funding rate that increases to 74% when under $5,000.  85% of all Plays Campaigns in the data set fell under the $10,000 goal threshold.

The data set analysis was somewhat limited by the requested parameters.  Defining outcomes separately for the Theater category and the Plays subcategory may not accurately represent the trends.  Expanding the parameters to have the analyses performed on both the Parent and Sub category may yield a better view and an intersection between Launch Dates and Funding Goals.  It was not necessarily clear if the intended focus was Theater in general or Plays specifically.

Additional visualizations:

![Percentage_of_Outcomes_by_Goal](https://user-images.githubusercontent.com/98665941/161455982-9bb78235-eccd-46b0-a6ee-cbd15e68d27f.png)

![Goal_Outcomes_by_Amount](https://user-images.githubusercontent.com/98665941/161455990-d136350a-68bc-41de-806b-4ccfb9adfacf.png)



