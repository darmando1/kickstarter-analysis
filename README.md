# An Analysis of Kickstarter Campaigns
##**Summary**
Identifying kickstarter outcomes based on launch date (specifically within theater) and identifying kickstarter outcomes based on goals (specifically for theater plays).
##Kickstarter Sheet
The kickstarter sheet provides important raw and calculated data to help with the analysis. Some of the more important columns we will use include a unique identifier for each name, a name column, a quick description of what the name is, a goal/pledged amount, the country of origin/currency code, a derived deadline/launched at date, and a derived parent category and subcategory. Our analysis is designed to help Louise make the most informed decision as to how different campaigns fare in relation to their launch dates and their funding goals. First, we will analyze theater outcomes as a whole based on launch date.
##Theater Outcomes by Launch Date Sheet
![Theater Outcomes Based on Launch Date](https://github.com/darmando1/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.jpg)
The purpose of this pivot table is designed to show different outcomes based on month without the specific year being a factor. For example, in January (regardless of year), there were 56 successful campaigns, 33 failed campaigns, and 7 canceled campaigns. We can clearly see that May, June and July appear to be the months where campaigns are more successfully funded. As this is an analysis to help Louise try to understand why her **play** * *Fever* * came close to its fundraising goal in a short amount of time, we can also add a "Subcategory" filter to only view "plays." Here we still see the trend of May, June and July providing the highest number of successful campaigns.
##Outcomes Based on Goals
![Outcomes Based on Goals](https://github.com/darmando1/kickstarter-analysis/blob/main/Outcomes_vs_Goals.jpg)
The purpose of this table is to identify whether or not smaller goals (specifically within plays) are successfully more funded than larger goals. First we see that goals less than $4,999 have more than a 70% chance of being funded. We also see that goals less than $4,999 account for 69% of total play kickstarters. The numbers then begin to dwindle from $10,000 to $34,999 accounting for only 12.61% of the total plays. The success rate for goals between $10,000 and $34,999 is less than 55% with goals between $25,000 and $34,999 dropping down to less than 28%. Finally we see a large spike to 66.67% successful with goals between $35,000 and $44,999. However, these two ranges count for only .86% of the total population. 
#Challenges
The data provided is heavily skewed between certain years (2015 with 1225 events, 2016 with 950, and 2014 with 976.) These represent a significant amount of the population with very little representation from years 2009, 2010, 2011, 2012, 2013 and 2017. Thus for the Theater Outcomes by Launch Date Sheet we cannot fully determine whether or not the months of May, June and July provide the highest number of successful campaigns regardless of year. 
##Conclusions
Theater Outcome by Launch Date - Most successful fundings occur in the months of May, June and July. This finding is based on data primarily from the years 2014, 2015 and 2016.
Outcomes Based on Goals - **Most** goals are set between $0 and $19,999 and there's more than a 50% chance they are successful with an inverse correlation between success and goal amount. Thus, as the goal amount decreases from $19,999 the success amount increases up to 75%.
##Recommendations
Include a subcategory filter in the "Theater Outcomes by Launch Date."
Include a Percentage of Total Projects calculation in the "Outcomes Based on Goals" sheet.
Include a count of the years along with a percentage of total.
