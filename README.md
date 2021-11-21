# **An Analysis of Kickstarter Campaign**
kickstarter campaign analysis 


## **Overview of Project**

This project is designed to identify the best and worst months to commence a money-fund campaign for a theater. It also identifies the probability of running a successful campaign based on the fund goal for a play.

### Purpose
This project is designed to identify the best campaign strategy for writers seeking to begin a fund-raising campaign to fund their projects. 


## **Analysis and Challenges**

### Analysis of Outcomes Based on Launch Date
The objective in this portion of the analysis was to identify the best and worst months of the year to start a crowd-funding campaign for a theater project. The analysis was administered by using data on campaigns for the theater category, date each campaign commenced, and outcome of the campaign. Utilizing pivot tables, the data was manipulated to focus on the exact month the campaign commenced, and whether the campaign was successful, failed, or cancelled. Finally, the results of this analysis were depicted in a line chart (Theater Outcomes vs Launch Date) that depicts the relationship between the month the campaign commenced (x-axis) and the outcome of the campaign on the y-axis.

![image]("C:\Users\omarr\Dropbox\My PC (LAPTOP-U0EFHS68)\Desktop\Boot Camp\W1 Excel\Module1\Kickstarter-Analysis\Resources\Theater_Outcomes_vs_Launch.png")


### Analysis of Outcomes Based on Goals
The objective of this portion of the analysis was to identify the probability of running a successful campaign meant to fund a play based on the desired fund goal. The analysis commences using data on the requested campaign goal and the outcome of the campaign. The data was manipulated and categorized based on the dollar amount range that each play falls under and whether the campaign was successful, failed, or cancelled. After the categories were assembled the total number of successes, failures, and cancellations for each range were identified and used to identify the probability of running a successful, failed, or cancelled campaign based on the funding goal set. Finally, the results were depicted in a line chart with the goal-amount ranges depicted on the x-axis and the percentage of successful, failed, and cancelled projects on the y-axis.

![image]("C:\Users\omarr\Dropbox\My PC (LAPTOP-U0EFHS68)\Desktop\Boot Camp\W1 Excel\Module1\Kickstarter-Analysis\Resources\Outcomes_vs_Goals.png")


### Challenges and Difficulties Encountered
The primary challenges faced with administering analysis were related to the quality of the data. The data on the dates the campaigns were created are provided in Unix time stamp format which needed to be transformed into a readable format. Furthermore, the data on the category of the campaign required manipulation to further stratify the data into subcategories.


## **Results**

By examining (Figure 1) it is evident that May is the best month to start a money-fund campaign for a theater project. However, Jan, March, September, and November are the worst months to commence a campaign. It is also important to state that theater campaigns are a very popular and successful category as they account for roughly a third of the total campaigns and successful campaigns. The analysis on the outcomes of money-fund campaigns for plays based on the monetary goal of the campaign concludes that the most successful campaigns are the ones that set a modest monetary goal. Campaigns with a monetary goal less than $1000 were successful 75.81% of the time and those with a goal between $1000 and $4999 has a success rate of 72.66%. Once the campaign goal exceeds $15,000 most campaigns fail. Campaigns with goals in the 35,000 to 39,999 and 40,000 to 44,999 categories have a success rate of 66.67%; however, there are very few campaigns that fall into these categories which is not very assuring. Despite these valuable insights the dataset does suffer from limitations particularly the lack of data on the genre of the work, which would provide a unique perspective at identifying successful campaigns. The dataset could be used to complete analyses that would incorporates the length of the campaign, country the campaign took place in, and the number of backers to develop a superior campaign strategy. 