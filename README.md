# Excel_HW


Instructions

Using the Excel table provided, modify and analyze the data of 4,000 past Kickstarter projects as you attempt to uncover some market trends.
•	Use conditional formatting to fill each cell in the state column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.

o	Create a new column O called Percent Funded that uses a formula to uncover how much money a campaign made to reach its initial goal.

•	Use conditional formatting to fill each cell in the Percent Funded column using a three-color scale. The scale should start at 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.

o	Create a new column P called Average Donation that uses a formula to uncover how much each backer for the project paid on average.

o	Create two new columns, one called Category at Q and another called Sub-Category at R, which use formulas to split the Category and Sub-Category column into two parts.


![alt text](https://github.com/iyesogie/Kickstart-My-Chart/blob/main/images/Screen%20Shot%202021-08-03%20at%208.17.44%20PM.png?raw=true)

o	Create a new sheet with a pivot table that will analyze your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

o	Create a stacked column pivot chart that can be filtered by country based on the table you have created.

![alt text](https://github.com/iyesogie/Kickstart-My-Chart/blob/main/images/Screen%20Shot%202021-08-03%20at%208.18.04%20PM.png?raw=true)

o	Create a new sheet with a pivot table that will analyze your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.

o	Create a stacked column pivot chart that can be filtered by country and parent-category based on the table you have created.

![alt text](https://github.com/iyesogie/Kickstart-My-Chart/blob/main/images/Screen%20Shot%202021-08-03%20at%208.18.20%20PM.png?raw=true)

•	The dates stored within the deadline and launched_at columns use Unix timestamps. Fortunately for us, there is a formula that can be used to convert these timestamps to a normal date.

o	Create a new column named Date Created Conversion that will use this formula to convert the data contained within launched_at into Excel's date format.

o	Create a new column named Date Ended Conversion that will use this formula to convert the data contained within deadline into Excel's date format.

o	Create a new sheet with a pivot table with a column of state, rows of Date Created Conversion, values based on the count of state, and filters based on parent category and Years.

o	Now create a pivot chart line graph that visualizes this new table.

![alt text](https://github.com/iyesogie/Kickstart-My-Chart/blob/main/images/Screen%20Shot%202021-08-03%20at%209.03.55%20PM.png?raw=true)


•	Create a report in Microsoft Word and answer the following questions.
1.	Given the provided data, what are three conclusions we can draw about Kickstarter campaigns?
2.	What are some limitations of this dataset?
3.	What are some other possible tables and/or graphs that we could create?

Bonus

•	Create a new sheet with 8 columns:

o	Goal

o	Number Successful

o	Number Failed

o	Number Canceled

o	Total Projects

o	Percentage Successful

o	Percentage Failed

o	Percentage Canceled


•	In the Goal column, create 12 rows with the following headers:

o	Less than 1000

o	1000 to 4999

o	5000 to 9999

o	10000 to 14999

o	15000 to 19999

o	20000 to 24999

o	25000 to 29999

o	30000 to 34999

o	35000 to 39999

o	40000 to 44999

o	45000 to 49999

o	Greater than or equal to 50000


![alt text](https://github.com/iyesogie/Kickstart-My-Chart/blob/main/images/Screen%20Shot%202021-08-03%20at%208.18.33%20PM.png?raw=true)


•	Using the COUNTIFS() formula, count how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populate the Number Successful, Number Failed, and Number Canceled columns with this data.

•	Add up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Then, using a mathematical formula, find the percentage of projects that were successful, failed, or canceled per goal range.

•	Create a line chart that graphs the relationship between a goal's amount and its chances at success, failure, or cancellation.


![alt text](https://github.com/iyesogie/Kickstart-My-Chart/blob/main/images/Screen%20Shot%202021-08-03%20at%208.19.09%20PM.png?raw=true)

Bonus Statistical Analysis

If one were to describe a successful crowdfunding campaign, most people would use the number of campaign backers as a metric of success. One of the most efficient ways that data scientists characterize a quantitative metric, such as the number of campaign backers, is by creating a summary statistics table.

For those looking for an additional challenge, you will evaluate the number of backers of successful and unsuccessful campaigns by creating your own summary statistics table.

•	Create a new worksheet in your workbook, and create a column each for the number of backers of successful campaigns and unsuccessful campaigns. 

•	Use Excel to evaluate the following for successful campaigns, and then for unsuccessful campaigns:

o	The mean number of backers.

o	The median number of backers.

o	The minimum number of backers.

o	The maximum number of backers.

o	The variance of the number of backers.

o	The standard deviation of the number of backers.

•	Use your data to determine whether the mean or the median summarizes the data more meaningfully.

•	Use your data to determine if there is more variability with successful or unsuccessful campaigns. Does this make sense? Why or why not?


![alt text](https://github.com/iyesogie/Kickstart-My-Chart/blob/main/images/Screen%20Shot%202021-08-03%20at%208.19.25%20PM.png?raw=true)

