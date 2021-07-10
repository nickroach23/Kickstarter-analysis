# Kickstarter-analysis
## Overview of Project 
Overview is performing analysis on Kickstarter data to uncover some trends given.

### Purpose 
The Outcome Based on Launch Date shows the relationship between the number of (failed, live and successful) plays and the month of the launch dates. The Outcomes Based on Goals shows the relationship between the percentage of (successful,failed and canceled) plays and funding goals. 


## Analysis and Challenges 

### Analysis of Outcomes Based on Launch Goals 
Outcomes Based on Launch Date: I created a pivot table based on the data from the kickstarter worksheet. The pivot table shows the number of (canceled,failed, live and successful) plays based on the months of the launch date. Then I created a line graph with the months of launch date and the number of outcomes. The line graph gives a better visualization of the data and shows how the outcome fluctuates. 

### Analysis of Outcomes Based on Goals 
Outcomes Based on Goals: I created a table that shows the number and percentage of (successful, failed and canceled) plays based on the funding goals. I obtained the number of (sucessful, failed and canceled) plays based on the funding goals by using the =countifs() function, which pulled data from the kickstarter worksheet. I was then able to get the percentage of each outcome by dividing the number of (successful,failed and canceled) by the total number of plays. I created a line graph that shows the trends of how the outcome percentage fluctuates based on funding goal ranges. 

### Challenges and Difficulties Encountered 
Challenges that I was faced with was using the =Countifs() function for the (successful,failed and canceled) section. There was a lot of back in forth with this section because of minor typos in my equation. One mistake would throw my data off. To make sure my numbers were correct. I went through each column on kickstarter that related to my charts and graphs and filtered each one, scrolled down to the bottom of the data sheet to make sure my counts matched with the numbers I calculated. 

## Results 
Outcomes Based on Launch Date: The data shows that through the months of (March-May) there's a significant increase of successful plays shown which would be considered the peak season. The months after that you notice a trend of successful plays decreasing each month with the exception of October. With failed outcomes the trend shows small increases throughout the months and a increase towards (october). With live you see an increase through the first 3 months (Jan-March) but after there's no data recorded after March. With the canceled outcomes you see a steady trend with no data recorded in October.

Outcomes Based on Goals: Based on the successful percentage there's a few trends that fluctuate in the graph. From funded goals less than 1000 to 29999, the higher the goal the lower the success percentage.
