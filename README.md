# Kickstarter-Analysis
**Performing Analysis on kickstarter data**

## Overview of Project
Analysing crowdfunding campaign data to determine possible outcomes could arise based on the deciding factors of starting up a new fundraising project of Louice.The projected budget is set to approximately $10,000
The main deciding and analysing factors would be concluded upon success rate of the particular subcategory based on the launch date and goals separately.
As the main objective of the fundraising campaign is to fund for a new play,the final analysis is based on the subcategory play and it outcomes based on the funding goals and parent category theater and it outcomes based on the launch day.   

## Purpose
The purpose of the project is to compare and get to know the outcomes of different campaign in relation with campaign launch date and the funding goals of each campaign.The final analysis and conclusion will be main deciding factor of when to and how to plan the project to be successful. The data will be analysing using the following excel workbook. 

https://github.com/Rangisal/Kickstarter-Analysis/blob/main/Kickstarter_Challenge.xlsx

## Analysis and Challenges
As described above the analysis is mainly based on,
- Analysis of outcomes based on launch date
- Analysis of outcomes based on Goals

### Analysis of Outcomes Based on Launch Date

- Added a new column to the worksheet as **years** and extracted the year from date created column in order to determine the readable format. 
- Filtered a pivot table based on **parent category and years** with all the outcomes except live to analyse the each outcomes. 
- Grouped row labels according to the months of the year to analyse the success factor of all categories in each month. 
- Filtered the **theater** from the parent category to show the success factor in each month and this will be shown in the **theater outcomes by launch date** sheet in the     work book.
- Pivot chart were created sorting the outcomes in descending order. 
- The chart shows as follows and noticing the higher successful rate in May and June.
  
  ![image](https://user-images.githubusercontent.com/93173498/140600027-5974c046-6487-4844-b0b1-284895362431.png)


### Analysis of Outcomes Based on Goals
- Used the countifs() to visualize percentage of successful, failed and canceled plays based on funding **goal** amounts.
- Collected the outcomes and goal data for the subcategory **play** 
- This can be found in the sheet **outcomes based on goals**
- In the goal column created dollar amount as ranges as the projects can be grouped based on their goal amount. 
- Calculated the total projects and percentage of each outcomes to visualize the relationship between the goal amount ranges and the percentage of each outcomes. 
- This following line chart shows the outcome perfectly for the above analysis.

 ![image](https://user-images.githubusercontent.com/93173498/140600003-5803d221-5649-43b8-b1bb-70d08cf4b202.png)


### Challenges and Difficulties Encountered
- It shows in the analysis according to the outcomes based on the goal there is a higher possibility to fail the campaign when the goal amount is higher.
- The following table clearly indicates that Louise is asking more than twice the average successful goals. Both mean and median successful goal amount is lower than the       failed goal amount.

![image](https://user-images.githubusercontent.com/93173498/140601301-8be8cd78-1c2e-4387-9813-631a0b681cdf.png)

  
- Hence there should be another way to confirm the feasibility of using outcomes vs goal before make any conclusion. 

## Results

 **What are two conclusions you can draw about the Outcomes based on Launch Date?**
- The months of May and June has higher outcomes of successful with higher rate of success.
- It will be a good deciding factor to launch a campaign in those months.

 **What can you conclude about the Outcomes based on Goals?**
- Higher failure due to higher goal amount 

 **What are some limitations of this dataset?**
- There should be more deciding factors to analyse before make any final decision on the campaign. The success rate is not solely depends on the goal or the launch date. 

 **What are some other possible tables and/or graphs that we could create?**
- Demographic analysis of the past campaigns on theater and see the other opportunities as Louis was interested in other areas in theater in different countries. 
- Box plot of selected demographic based on subcategories of theater. 
