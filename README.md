# Module 1 Challenge
### Project Overview
The purpose of this project is to build a detailed analysis of Kickstarter campaigns. 
To make data-driven decisions when helping Lousie with her Kickstarter campaign. A Kickstarter is a funding platform for creative projects such as films, games, plays, technology, and art. A Kickstarter is an innovative, imaginative, and ambitious way to bring ideas to life through the direct support of others.
To better understand Kickstarter campaigns, 4,114 Kickstarter campaigns will be analyzed. Data points included are name, goal, pledge, outcome, country, category, etc... 
Having this data is very valuable when starting a Kickstarter campaign because it will help Lousie better understand what is an attainable goal and help her choose a launch date that will yield a successful outcome for her campaign.

### Analysis and Challenges

#### Analysis
This analysis will focus on the outcome of the campaign based on the goal and outcome relative to the launch date.
There are four different outcomes for Kickstarter campaigns. The possible outcomes are 'successful', 'failed', 'live', and 'canceled'. 
These outcomes define if the campaign reached its set goal. For example, Lousie set a goal of $4,000 for her play 'Fever'. 
The outcome will be defined by the pledge reaching the goal. The pledge is the dollar amount raised for a specific campaign.
If we continue with the example that Louise has a goal of $4,000 for her Kickstarter campaign. 
Lousie's goal is between $1,000 - $4,999 giving her a 72.66 percent chance that she will be successful reaching her goal. It is important to note that Louise's campaign was compared to similar campaigns filtered by Category 'theatre'. 

![Outcomes vs Goals](Outcomes_vs_Goals.png)

Furthermore, an analysis of outcomes based on the launch date was conducted and the results can be seen below. The graph was filtered to only include the outcome of plays. The graph shows that plays were most likely to be successful during the month of May. Louise can use this information to make a data-driven decision as to when she should release her campaign. If Louise launches her campaign during the month of May she is more likely to reach her goal.

![Theater Outcomes Vs Launch](Theater_Outcomes_vs_Launch.png)

#### Note
The graphs above were created in excel using the Kickstarter_Challenge excel document. Calculations were done within the excel document and pivoting tables were used to manipulate the data to only show similar campaigns to Louise's. To validate calculations for the Outcomes Based on Goals graph open the Kickstarter_Challenge.xlsx document and look at the Outcome Based on Goals sheet. Also, to certify calculations for the Theatre Outcomes based on the Launch Date graph open the Outcome Based on the Launch Date sheet.


#### Challenges
For this particular analysis, there were not many challenges or difficulties encountered. Due to the majority of the data already being formatted for this analysis. That being said, if the data was not handed over in this manner some of the challenges and difficulties would be aggregating and formatting the data. Combining data is a very difficult task, due to a lack of documentation. For example, Louise does not record the backers that helped her reach her goal. Backers is a person or institution that supports someone or something financially. The format of data can also be an issue. For example, Louise writes down her goal in a written format (one thousand) while other campaigns use integers (1000). This would make it difficult for the analyst to combine the data and would require the analyst to transform the written format into an integer. 

### Results
Two conclusions can be drawn from the Theatre Outcomes based on the launch date graph. May is the best month to launch a Kickstarter campaign, because out of 166 campaigns that were launched in May 111 were successful. That gives May about a 67 percent success rate. Also, December is the worst month to launch a Kickstarter campaign due to 37 out of 75 campaigns being successful. That would give December a 49 percent success rate. Moreover, the main conclusion that can be drawn from the Outcomes Based on Goal graph is that by having a smaller goal the probability of achieving it is higher. However, there are a few outliers around the range of 35,000 - 44,999 that give a 67 percent success rate. With the analysis above Lousie can be better prepared to launch her campaign and define a reachable goal. That being said, there is no guarantee that Lousie's campaign will be successful. The data has limitations such as the range of data and manipulation of data. The data from the given data set only ranges from 2009 through 2015 which is very limited. The more data there is the more accurate the analysis. Moreover, the possibility of inaccurate data being recorded has to be taken into account. For example, it is possible that initially, a Kickstarter had an aggressive goal to meet. However, as the deadline approaches the Kickstarter lowers their goal to match the pledge and by doing so it shows that the kickstart was successful. To improve this analysis more data should be collected and only reliable data should be accepted. 

#### Recomendations
A column that can be added to the existing data set is viewers. Viewers can be leveraged to show that people are interested in a subcategory. For example, let's say that there is less interest in plays in the United States, however, in Great Britain there is greater interest. This can help Louise better market her Kickstarter campaign. Viewers based on the subcategory and filtered by country would give Louise a better understanding of whom to market her Kickstarter campaign. 

