# Kickstarting with Excel

## Overview of Project
### General Background
This project analyzes Kickstarter campaign data to help provide insights for future campaigns.

### Purpose
The purpose of this project is to assist Louise in determining if there are certain factors in achieving a successful Kickstarter fundraising campaign for her play *Fever*, which has a budget of over USD 10,000.

## Analysis and Challenges
The following section describes how I performed my analysis and some of the challenges I faced during the analysis.

### Analysis of Outcomes Based on Launch Date
One important aspect of my analysis was to review outcomes based on a campaign's launch date. Analyzing outcomes based on a campaign's launch date provides insight to see if there are more opportune times throughout the year to launch a campaign. 

Specifically, I looked at successful, failed, and canceled outcomes of theater campaigns across all countries and timeframes. I removed campaigns that were still live since we cannot yet know the outcome of these campaigns.

The results of this analysis are as follows:

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/99286327/155813197-52e51ff6-9221-44cb-89e3-9f752985833e.png)

### Analysis of Outcomes Based on Goals
Another important aspect to analyze was the outcome of the play campaigns based on the goal amount. This insight would help inform whether Louise's budget of $10,000+ is realistic in getting funded based on historical data. Again, I included all countries and timeframes.

The results of this analysis are below:

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/99286327/155813256-81014b9f-16a6-43de-b52a-98704ab64e2d.png)

### Challenges and Difficulties Encountered
1. Since I operate on a MacOS instead of a Windows PC, certain functionality within Excel was slightly limited. For example, I was unable to easily filter specific data or data points when looking at a visualization. On a PC, I would have been able to easily drill down using filtering when looking for insight into particular data points, however, on my Mac I was unable to do so.

2. When creating the PivotTable for Theater Outcomes by Launch Date, I had an unusual error that included blank rows in my PivotTable. Although I tried to manipulate the data source (i.e. Select Data) within the PivotTable design, in the end I had to delete the sheet tab and start fresh. Selecting the specific table range instead of the complete Kickstarter tab seemed to solve the mishap.

## Results

### Theater Outcomes by Launch Date Conclusions
1. One important finding for Louise is that there are almost always more successful theater campaigns than failed campaigns throughout the year and very few theater campaigns get canceled. With the exception of December, more than half of all theater campaigns are successful, regardless of the time of year (see screenshot below). This is a hopeful sign for Louise, assuming her campaign aligns with other factors that make campaigns successful.

![Theater_Outcomes_vs_Launch_percentage](https://user-images.githubusercontent.com/99286327/155814224-7a4a702d-6f6f-4abe-88b6-b98345cd0336.png)

2. Louise is most likely to have the biggest chance for success if she launches her campaign in May. If her campaign is not ready to launch in May, June would be the next best month to launch. 

### Outcomes Based on Goals Conclusion
Based on historical trends, the play campaigns with the _highest_ likelihood of success were those with funding goals less than $5,000. Specifically, from the data we see over 70% of campaigns were successful when the goal was less than $5,000 (see screenshot below). 

![Outcomes_vs_Goals_table](https://user-images.githubusercontent.com/99286327/155814678-058d01e2-2276-4d24-843b-7c4110e4b794.png)

Although we see that 67% of campaigns were successful when their goals were $35,000-$44,999, the total number of projects is so few (9) that it would be unwise to draw conclusions from such a small sample. 

Louise's budget falls in the $10,000 to $14,999 range and of all the campaigns in that group, 54% were successful. This is a smaller percentage than I would have liked but it still shows more than half were successful. 

### Limitations of the Dataset
I found the dataset to be highly robust. Many different types of analysis are able to be performed on the data and much of the data could be manipulated to provide additional data points. That said, there were a few limitations to the dataset:
- The data was captured from 2009 to 2017 and it would be helpful to have a more up-to-date dataset, especially since the COVID pandemic drastically changed our economy and spending patterns. In fact, if Louise had launched her fundraiser in May 2020, it would likely to have gone un-funded.
- The other limitation of the dataset was the minimal data provided on pledges. While it was easy enough to write a formula for average donations, it would be helpful to have the highest (or maximum) donation. For example, if some of the campaigns had a wealthy benefactor or a corporate sponsorship that donated a significantly higher amount than most pledges and was skewing our average, our current data does not show this. It would be helpful to know the highest donation and have the option to remove anomalies and outliers from our analysis. 

### Future Data Visualizations
Below are a few ideas for future data visualizations:
- Since I included all countries and timeframes in my analysis, I believe future insights could be gleaned by knowing definitively where Louise plans to produce her play and when. If she plans to produce her play in the US, then it would be good to focus on country-specific data and revise some of the graphs included here. Similarly, depending on when Louise wants to launch her campaign, it might be wise to limit the scope to the 5 most recent years instead of including all data going back to 2009 since spending patterns might have changed.

- For the Theater Outcomes by Launch Date graph, it might be helpful to include a line graph for the Percentage of Successful. Overlaying the total number of successful campaigns with the number of failed ones forces the reader to "_eyeball_" certain numbers. For example, 67% of theater campaigns were successful when launched in May and 65% were successful when launched in June. Based on the graph included above, one might think that July would be the next best month just based on the high number of successful campaigns, but in fact 63% of successful campaigns were launched in July, February, **AND** April. However, that's not entirely obvious from our current graph. 
> Note: I included screenshots of my tables to be sure the audience knew how I was drawing my conclusions.

- Lastly, it might be helpful to conduct some additional correlation analysis as it pertains to length of campaign, number of backers, and campaign success.
