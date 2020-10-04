# Module 1 Challenge
### Project Overview
The purpose of this project is to build a detailed analysis of Kickstarter campaigns. 
In order to make data driven decisions when helping Lousie with her own Kickstarter campaign. A kickstarter is a funding platform for creative projects such as, films, games, plays, technology, and art. A kickstarter is an innovative, imaginative, and ambitious way to bring ideas to life through the direct support of others.
To better understand Kickstarter campaigns, 4,114 kickstarter campaigns will be analyzed. Data points included are name, goal, pledge, outcome, country, category, etc... 
Having this data is very valuable when starting a kickstarter campaign, because it will help Lousie better understand what is an attainable goal and help her choose a launch date that will yield a successful outcome for her campaign.

### Analysis and Challenges

#### Analysis
This analysis will focus on outcome of the campaign based on the goal and outcome relative to launch date.
There are four different outcomes for kickstarter campaigns. The possible outcomes are 'successful', 'failed', 'live', and 'canceled'. 
These outcomes define if the campaign reached its set goal. For example, Lousie set a goal of $4,000 for her play 'Fever' . 
The outcome will be defined by the pledge reaching the goal. The pledge is dollar amount raised for a specific campaign.
If we continue with the example that Louise has a goal of $4,000 for her kickstarter campaign. 
Lousie's goal is between $1,000 - $4,999 giving her a 72.66 percent chance that she will be successful reaching her goal. Its important to note that Louise's campaign was compared to similar campaigns filtered by Category 'theatre'. 

![Outcomes vs Goals](Outcomes_vs_Goals2.png)

Furthermore, an analysis of outcomes based on launch date was conducted and the results can be seen below. The graph was filtered to only include outcome of plays. The graph shows that plays were most likely to be succesful during the month on May. Louise can use this information to make a data driven decision as to when it is best for her to release her campaign. If Louise launches her campaign during the month of May she is more likely to reach her goal.

![Theater Outcomes Vs Launch](Theater_Outcomes_vs_Launch2.png)

#### Note:
The graphs above were created in excel using the Kickstarter_Challenge excel document. Calculations were done within the excel document and pivoting tables were used to manipulate the data to only show similar campaings to Louise's. To validate calculations for the Outcomes Based on Goals graph open the Kickstarter_Challenge.xlsx document and look at the Outcome Based on Goals sheet. In addition, to certify calculations for the Theatre Outcomes based on Launch Date graph open the Outcome Based on Launch Date sheet.


#### Challenges
For this particular analysis there was not many challenges or difficulties encountered. Due to the majority of the data already being formatted for this analysis. That being said, if the data was not handed over in this manner some of the challenges and difficulties would be aggregating and formatting the data. Combining data is a very difficult task, due to lack of documentation. For example, its possible that Louise does not record the backers that helped her reach her goal. Backers is a person or institution that supports someone or something financially. In addition, the format of data can also be an issue. For example, Louise writes down her goal in a written format (one thousand) while other campaigns use integers (1000). This would make it difficult for the analyst to combine the data and would require the analyst to transform the written format into an integer. 

### Results
Two conclusions can be drawn from the Theatre Outcomes based on launch date graph. May is the best month to launch kickstarter campaign, because out of 166 campaigns that were launched in May 111 were successful. That gives May about 67 percent success rate. In addition, December is the worst month to launch kickstarter campaign due to 37 out 75 campaigns being successful. That would give December a 49 percent success rate. Moreover, the main conclusion that can be drawn from the Outcomes Based on Goal graph is that by having a smaller goal the probabilty of acheiving it is higher. However, there is a few outliers around the range 35,000 - 44,999 that give 67 percent success rate. With the analysis above Lousie can be better prepared to launch her campaign and define a reachable goal. That being said, there is no guarantee that Lousie's campaign will be succesful. The data has limitations such range of data and manipulation of data. The data from the given data set only ranges from 2009 through 2015 which is very limited. The more data there is the more accurate the analysis. Moreover, the possiblity of inacurate data being recorded has to be taken into account. For example, its possible that initially a kickstarter had an aggresive goal to meet. However, as the deadline approaches the kickstarter lowers their goal to match the pledge and by doing so it shows that the kickstart was succesful. In order to improve the kickstarter campaign data set more data should be collected and accept only reliable data. 
