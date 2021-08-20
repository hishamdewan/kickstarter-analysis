# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this analysis is to use Kickstarter data we need to help Louise, hopeful playwright, with her project campaign. Louise is looking to launch a Kickstarter campaign to fund her play "Fever". This analysis is looking to draw conclusions about past campaigns to help guide Louise's decisions. Specifically, Louise would like to know how different campaigns fared in relation to their launch dates and their funding goals. 
 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Purpose is to visualize campaign outcomes ("successful," "failed," and "canceled") based on launch date. I took the following steps:

- Cleaned up the Kickstarter data to create Parent category and subcategory columns, created date created and date ended columns. 
- Created a pivot table that looked at outcomes of campaigns ("successful," "failed," and "canceled") over month in which projects were launched. 
- Create a line chart from the pivot table to visualize the relationship between outcomes and month in which projects were launched. See 

![Theater Outcome vs Launch](/Resource/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
Purpose is to visualize the percentage of successful, failed, and canceled plays based on the funding goal amount.I took the following steps:

- Created a table using COUNTIFS() function to count the number of plays based on outcome of the projects for various range of pledged amount. 
- Created a table and a line chart that showed percentage of projects that were successful, failed, and canceled . 

![Theater Outcome vs Launch](/Resource/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
The main challenge was cleaning up the Kickstarter data to suit the need of the client. 
If one is not familiar with COUNTIFS() function, please refer to [Microsoft Office tutorial](https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842)

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	- The month that launched the most successful Kickstarter campaigns in the theater category was May.
	- May through August all had roughly the same number of failed campaign launches.
- What can you conclude about the Outcomes based on Goals?
	- Campaigns looking to raise less than $5000 were the most successful in reaching their goals. 
	- Campaigns looking to raise more than $45000 had the highest failure rates in reaching their goals. 
- What are some limitations of this dataset?
	- The dataset lacks qualitative drivers of what makes campaigns successful such as its quality of the project.
	- The dataset lacked information on marketing prowess of the campaigners and ability to go viral.
- What are some other possible tables and/or graphs that we could create?
	- Outcome of projects based on category and country to gauge if pursuing theatrical Kickstarter campaigns is a good idea in the US vs other countries. 
	- How does gap between deadline and launch date impact the success rate of theatrical Kickstarter campaigns. 
