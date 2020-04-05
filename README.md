# An Analysis of Kickstarter Campaigns
(Module 1.6.1 exercise)

This repository contains Kickstarter data and analysis that is used to determine the Kickstarter campaign parameters needed to have a successful campaign to fund the playwright's production of the play "Fever". The playwright's initial estimate of the cost to put on the play is $12,000.

First, looking at US Kickstarter campaigns for all categories, the data shows that plays have the most Kickstarter campaigns and that these campaigns are among most successful.

![Outcomes By Major Catigory](https://github.com/berndab/kickstarter-analysis/blob/master/Module1.3.1.Chart.Parent%20Category%20Outcomes.png)

Second, research on the plays favored by the playwright at the Edinburgh Festival Fringe:

* Be Prepared
* Checkpoint 22
* Cutting Off Kate Bush
* Jestia and Raedon
* The Hitchhiker’s Guide to the Family

shows that all of these plays had successful Kickstarter campaigns. If "Fever" is a play written in the same style of one of these plays, the data indicates that the Kickstarter campaign for "Fever" would attract enough donors to be successful. 

However, the data also shows that the campaign's goal for "Fever" of $12,000 is significantly greater than the mean campaign goal of $2,100 for these successful Edinburgh plays. In addition, the "Fever" campaign goal of $12,000 is well above the mean campaign goal of $5,049 for all successful US play Kickstarter campaigns and is also above the mean goal of $10,554 for all failed US play Kickstarter campaigns. This indicates that the playwright must set a significantly lower Kickstarter campaign goal of $3,000 - $4,000 in order for Fever’s Kickstarter campaign to have the highest chance of success.

In addition, the data from all US Kickstarter campaigns show that the time of year that the campaign is launch is significantly correlated to the highest number of successful Kickstarter campaigns. The data shows that the May to June timeframe consistently has the highest number of successful Kickstarter campaigns across all categories. 

![Outcomes By Launch Date](https://github.com/berndab/kickstarter-analysis/blob/master/Module1.3.3.Chart.Outcomes%20Based%20on%20Launch%20Date.png)

Based on this analysis of Kickstarter campaign data, the playwright should implement the following recommendations to have the greatest chance of success for the "Fever" Kickstarter campaign:
* The play’s style should be similar to one of the Edinburgh Festival plays favored by the playwright
* The play's Kickstarter campaign goal must be in the  $3,000 - $4,000 range to have the highest chance of success
* The play's Kickstarter campaign should be launched between the May to June timeframe to have the highest chance of success


### Challenge
Introduction

This additional analysis of Kickstarter data focuses only on Kickstarter data from the theater category and the play subcategory to determine the campaign parameters and the parameter values that give a play Kickstarter campaign the greatest chance of success. The playwright will use this additional analysis and its conclusions to plan future play Kickstarter campaigns.
	
Overview

Our analysis of play and theater Kickstarter campaign data focuses on three campaign parameters. These parameters are campaign goal amount, campaign launch month, and campaign duration (This was and additional dataset I choose to add to the required challenge because I thought it gave additional insight into play campaign success criteria).

% Outcomes by Campaign Goal Amount Range

![% Play Outcomes by Goal Amount Range](https://github.com/berndab/kickstarter-analysis/blob/master/Module1.Challenge.Chart.Plays.%25OutcomesByGoalAmount.png)

The initial analysis of this chart shows that there are two peaks in the success rate for play Kickstarter campaigns.  One success rate peak occurs for the goal range between $0 to $4,999 and the other peak occurs for the goal range between $35,000 to $49,999. However, there are 720 play campaigns that have a goal amount between $0 to $4,999, while there are only 9 play campaigns that have a goal amount between $35,000 to $49,999.

The chart below shows the number of play campaigns for each goal range. The number of campaigns declines rapidly as the goal range amount increases. There are too few data point at the upper goal ranges to make the calcualted success and failure rates for these  ranges statistically significant enough to be useful in predicting outcomes for the upper goal ranges.


![Kickstarter Campaign Counts by Goal Range]( https://github.com/berndab/kickstarter-analysis/blob/master/Module1.Challenge.Extra.Chart.Plays.CampaignCountsByGoalAmount.png)

However, this data set can be used to calculate statistically significant success and failure rates for campaigns with goal amounts below $15,000. This is because 92% of the play campaigns in this data set have a goal amount below $15,000 and there is enough data points in each goal amount range below $15,000 to generate statistically significant success and failure rates for the play campaigns in each goal range.

Here are the  success rate for play campaigns with goal amounts in the following ranges:

* Less than 1,000 - 75.81%
* 1,000 to 4,999 - 72.66%
* 5,000 to 9,999 - 55.03%
* 10,000 to 14,999 - 54.17%

The playwright can expect a greater that 70% average success rate for future play campaigns that have a goal amount below $5,000 and can expect an average 55% success rate for future play campaigns that have a goal amount between $5,000 to $14,999. Success and failure rates cannot be accurately be determined for play campaigns with goal amounts of $15,000 and above. The playwright should avoid launching play Kickstarter campaigns with goal amounts above $15,000. However, the playwright can accurately anticipate the chances of success of play campaigns created with goal amounts below $15,000.

Outcomes by Launch Month

![% Play Outcomes by Goal Amount Range]( https://github.com/berndab/kickstarter-analysis/blob/master/Module1.Challenge.Chart.Theater.OutcomeCountsByLaunchMonth.png)

This chart shows the count of theater Kickstarter campaigns outcome by launch month. This theater data includes not only play campaign outcome data but also outcome data for musicals and theatrical space campaigns. However this analysis focuses solely on determining the launch months that have the highest success rates for play Kickstarter campaigns. Since 75% of theater campaign outcomes consist of play campaign outcomes, this data can be used to investigate the relationship of play campaign outcomes to launch months.

The chart of outcome data by launch month shows that highest number of successful theater campaigns occur from May to July. One potential conclusion is that play campaigns launched from May to July will have the greatest chance of success. However, an alternative conclusion could be that the period from May to July has the highest counts of successful theater campaigns because these months also have the highest counts of theater campaign launches. 

A closer look at the data for May, June, and July show that these months have the three highest successful theater campaign outcome counts in order but also have the three highest theater campaign launch counts in order also.

*	May -- Success Count: 111   -- Total Launched Count: 166
*	June -- Success Count: 100  -- Total Launched Count: 153
*	July -- Success Count:    87  -- Total Launched Count: 138


![Theater Campaigns Success Countd and Total Launch Count by Launch Month](https://github.com/berndab/kickstarter-analysis/blob/master/Module1.Challenge.Extra.Chart.Theater.Success%26TotalCountsByLaunchMonth.png)

This chart is a shows a comparison of the number of successful theater campaigns by launch month with the number of theater campaign launches by month. The chart indicates that there is a correlation between the number of theater campaign launches in a month and the number of the successful theater campaigns for that same launch month. However, it does not show a 100% correlation between these counts. Therefore the peak in the number of successful theater campaign outcome that occur in May, June, and July may not solely be caused by the increase in the number of theater campaign launches during these months. I may also be caused by an increase in the success rate for theater campaigns for these months. 


![Theater Campaign Success Rate by Launch Month]( https://github.com/berndab/kickstarter-analysis/blob/master/Module1.Challenge.Extra.Chart.Theater.%25SuccessByLaunchMonth.png)

The chart of theater campaign success rates by launch month confirm that theater campaign succcess rates do peak in May and June. This would support the conclusion that launching a play Kickstarter campaign during May and June will increase its chance of success. For example, a campaign launched in May has a 17% greater chance of success then a campaign launched in December. One reason that the success rate peaks in May and June is that theater plays launched during these months open and run during the peak theater attendance months. More people pledge to theater campaigns because they want to see more plays during this time.

Because of the increase in the success rate for theater campaigns in May and June, The playwright should, when possible, plan to launch a new play Kickstarter campaign in May or June in order to have the greatest chance of success. Plays lauched during these months may attract larger audiences because of increased interested in seeing more plays. 

% Outcomes by Campaign Duration

![$ Outcomes by Campaign Duration](https://github.com/berndab/kickstarter-analysis/blob/master/Module1.Challenge.Extra.Chart.Plays.%25OutcomesByDuration.png)

The outcome rates by duration chart shows that play Kickstarter campaign with a duration of 30 days or less are more successful than play campaigns with longer durations. An explanation of this could be that, the success of play campaigns depends more on the size of the campaign creators’ network of fans then the duration of the campaign. Creating a campaign on Kickstarter does not in itself attract participants. However, a single tweet to a large fan base about a play campaign launch would motivate the large number of devoted followers to make a pledge to the campaign in a short period of time. 
The inverse correlation of play campaign duration to play campaign success indicates that the playwright should invest a considerable time and resources developing a fan base network and communicating with this network. This effort should be ongoing and should begin long before launching a major play Kickstarter campaign. The size of the fan network and communication with this network about upcoming play campaigns seems to be the major method for recruiting campaign pledgers. Increasing the campaign duration appears to have little effect on increasing campaign pledgers.

In summary the analysis of the play Kickstarter data show that the playwright can increase the probability of success of play Kickstarter campaigns by
* Setting a goal amount below $15,000
* Launching the play campaign in May or June
* Developing a fan base network and continuously communicating with it to promote new  play Kickstarter campaigns and to motivate fans to make pledges to active play Kickstarter campaigns.
