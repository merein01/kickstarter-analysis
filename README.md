# Kickstarting with Excel

## Overview of Project
Kickstarter is a type of platform that is used for crowdfunding to be able to fund creative projects. This project examined Kickstarter campaigns from multiple countries to discover trends, specifically focusing on plays. 

### Purpose
The purpose of this project is to analyze how different Kickstarter campaigns managed to achieve their funding goals in relation to their launch dates, specifically focusing on plays as our subcategory. 

## Analysis and Challenges
Overall, according to the data, the Theatre category is the most successful in Kickstarter, as the chart shown below indicates.

### Analysis of Outcomes Based on Launch Date
The purpose of this analysis is to analyze which theater campaigns were successful, failed, and canceled, based on their launch dates. The first step taken was adding a new column labeled “years” in the Kickstarter dataset to extract the year from the date created conversion column in which now we have a separate column that tells us when the campaign was initially launched. Next, we created a pivot table including filters of the parent category and years. Rows contained the date created conversion and columns and values contained outcomes. We placed another filter removing live campaigns, changing the rows to display only the months of the year, and filtering for theater only. Lastly, a line chart was created as the best type of chart to visualize the data from the pivot table in showing the relationship between theater outcomes and their launch month. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/105119376/168716685-a2b82a57-cf1b-4c06-942e-3c0998f8339f.png)


### Analysis of Outcomes Based on Goals
The purpose of this analysis is to analyze the percentage of successful, failed, and canceled plays based on the amount of funding goal. The first step taken a new table was created on a new sheet in the Kickstarter Excel workbook named, Outcomes Based on Goals in order to show the amounts and percentages of the campaigns and their outcomes. This table was broken down into 12 rows with goal amounts ranging from less than $1000 to greater than $50000. To calculate the number of successful, failed, and canceled campaigns based on funding goal, we used the COUNTIFS function on Excel. Additionally, we focused the outcome and goal data on the plays subcategory. Afterwards, we calculated the total number of successful, failed, and canceled campaigns using the SUM function on Excel. Then, we calculated the percentage of these campaigns. To help visualize the data, a line chart was created focusing on the percentage of successful, failed, and canceled campaigns. 



![Outcomes_vs_Goals](https://user-images.githubusercontent.com/105119376/168716760-af1184de-c973-4348-978c-471c5505a39c.png)




### Challenges and Difficulties Encountered
The biggest challenge that I encountered with this Kickstarter project was towards the end of this project, while working on Deliverable 2. At first, I was having trouble figuring out how to use the COUNTIFS function on Excel, as I have never used it before. It took me more than an hour to figure out the correct formula to place in order to calculate number of successful, failed, and canceled campaigns. But after studying hints and using external resources, I figured out the correct formulas and the line chart created based off these calculations looked the same from the one provided in the module for the challenge!

Biggest difficulty for me was setting up the Pivot Table field on Excel. This occurred when selecting the data on where to place the correct information in the rows, columns, and value fields while creating the pivot tables. I overcame this difficulty mostly by playing around with it, through trial and error, until I saw the tables were correctly created and looked the same from the module challenge. 

## Results
-What are two conclusions you can draw about the Outcomes based on Launch Date? 
One conclusion I can draw is that after analyzing the data, the success rate was at the highest in the month of May for the Theater campaign launch and then declined starting in the month of June and onwards. At its peak in May, a total of 111 theater campaigns launched were successful. 52 theater campaigns launched failed. 3 theater campaigns launched canceled. 

Another conclusion I can draw is that the success rate slightly increased September to October but then decreased again from October to December. The failure rate had an increase from September to October, then decreased from October to November. 

- What can you conclude about the Outcomes based on Goals?
	We can conclude that the success rate is higher for campaigns who’s funding goal is less than $5,000. When analyzing the data, campaigns that had a funding goal less than $1000 had about 79% success rate. There was a slight decrease for campaigns with funding goal of $1000-$4999 with a success rate of around 75-76%. Then the success rate dropped significantly when the funding goal increased to $5000-$9999 to around 58-59%.


-	What are some limitations of this dataset?
One limitation is that we don’t really know why the campaigns were highly successfully launched in the month of May, and then a significant decrease in the following months. We can assume this is due in part to the time of year or the season, as I noticed the campaign successful launch decreases going into June, which is when the summer begins. However, there is no actual data that can prove this assumption.

-	What are some other possible tables and/or graphs that we could create?
We could create a table or graph to analyze the outcomes based on country to see how each country fared compared to the other. We also could have done a comparison to the theater campaigns and how they relate to the other parent categories. 

