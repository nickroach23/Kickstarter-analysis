# Kickstarter-analysis
## Overview of Project 
Overview is performing analysis on Kickstarter data to uncover some trends given.

### Purpose 
The Outcome Based on Launch Date shows the relationship between the number of (failed, live and successful) plays and the month of the launch dates. The Outcomes Based on Goals shows the relationship between the percentage of (successful,failed and canceled) plays and funding goals. 


## Analysis and Challenges 

### Analysis of Outcomes Based on Launch Goals 
Outcomes Based on Launch Date: I created a pivot table based on the data from the kickstarter worksheet. The pivot table shows the number of (canceled,failed, live and successful) plays based on the months on the launch date. Then I created a line graph with the months for launch date and the number of outcomes. The line graph gives a better visualization of the data and shows how the outcome fluctuates. 

### Analysis of Outcomes Based on Goals 
Outcomes Based on Goals: I created a table that shows the number and percentage of (successful, failed and canceled) plays based on the funding goals. I obtained the number of (sucessful, failed and canceled) plays based on the funding goals by using the =countifs() function, which pulled data from the kickstarter worksheet. I was then able to get the percentage of each outcome by dividing the number of (successful,failed and canceled) to the total number. I created a line graph that shows the trends of how the percentage and funding goals flows through different ranges. 

### Challenges and Difficulties Encountered 
Challenges that I was faced with was the =Countifs() function for the (successful,failed and canceled) section. There was a lot of back in forth with this section because of minor typos in my equation. One mistake would throw my data off. To make sure my numbers were correct. I went through each column on kickstarter that related to my charts and graphs and filtered each one, scrolled down to the bottom of the data sheet to make sure my numbers matched with the numbers I calculated. 

## Results 

Outcomes Based on Launch Date: The first trend shows the lower the goal funded  the higher the success percentage is.There is a decline in success percentage from "20000 to 24999" to "25000 to 29999" of around 25%. There's an increase from "30000 to 34999" to "35000 to 39999" of around 40%. But there was a dramatic decline from "40000 to 44999" to "45000 to 49999" of around 67%. With the failed percentage you see the similar trends in  goal funded. With the higher goal funded the the higher the failed success rate increases. There is a increase in failed percentage from "20000 to 24999" to "25000 to 29999" of around 25%. There's an decrease from "30000 to 34999" to "35000 to 39999" of around 40%. But there was a dramatic increase from "40000 to 44999" to "45000 to 49999" of around 67%. With Percentage caceled there was nothing impacted, it stayed the same. 
