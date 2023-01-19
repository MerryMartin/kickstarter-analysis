# Kickstarting with Excel

## **Overview of Project**
## Louise is a playwright who just completed her first kickstarter campaign.  She would like to optimize her future kickstarter campaigns by mimicing the attributes of other successful campaigns in her field.  

### The purpose of this analysis is to help Louise understand how different launch dates and funding goals affect fundraising outcomes for plays

## Analysis and Challenges 
## I evaluated how different campaigns fared in relation to their launch dates and funding goals by utilizing formulas, pivot tables, and charts.

### Analysis of Outcomes Based on Launch Date
#### A pivot table was used to summarize theater outcomes, based on launch dates.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/115426070/197050261-9d896a7f-bdd9-4d4a-be1a-ead6902e160d.png)

### Analysis of Outcomes Based on Goals
#### CountIfs were used to determine the percentages of kickstarter outcomes, based on their fundraising goal amounts.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/115426070/197050194-638f7e37-c4da-4733-a42a-76aab5842858.png)

### Challenges and Difficulties Encountered
#### One potential challenge was when the formulas returned zeros and I was concerned they were not calculating the data that I wanted.  I manually filtered the dataset to verify that the calculations were accurate.

## Results
    Based on the data analysis, I can conclude that the most successful month to launch a kickstarter campaign is May and the least succesful month to launch a kickstarter campaign is December.  I can also conclude that campaigns with goals less than $4,999 have a pretty good chance of success - over 70%.  Since the highest percent of successful outcomes was for campaigns with fundraising goals of less than $1000, I would recommend that Louise keep her budget as close to that dollar amount as possible.  
---
## Limitations to Dataset
    There are some limitations of this dataset.  For example, the dataset for campaigns with goals between $40,000 and $44,999 is too small (only one campaign) to draw any conclusions.  Also, there are some datapoints that could be considered unrealistic and be possible outliers, like the $100,000,000 campaign goal for The Time Jumper.   Lastly, there could be campaigns identified in the dataset as FAILED that had pledged dollars that totaled 70% or more of the goal and were at least a partial success.  When the data is segmented based on clear dollar limits, it is hard to completely evaluate projects such as the Pants On Fire audio book.  
---
    In order to fully explore the dataset and provide the recommendations, I would suggest we filter the outcomes by the most recent launch dates (2016 and 2017) and create a bar chart to better understand the current market for kickstarter campiagns. 

