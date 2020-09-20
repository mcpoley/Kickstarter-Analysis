# Analyzing Kickstarter Campaigns For Strategy #
*Uncovering trends in crowd funding campaigns with Kickstarter data*

## Overview of Project
First, I color-coded the outcomes, “successful”, “failed”, “canceled”, and “live”, with corresponding colors green, red, yellow, and blue. Such a visual cue made it faster and easier to view and locate the outcomes. It was important to separate out the successful from the failed campaigns in the U.S. for comparison sake. This is helpful to Louise as her campaign will occur in the states.I looked through the data for similar plays to Fever, and looked at the goal amount, the amount pledged, the average donation, and the number of backers for these plays. In the final phase of my analysis, I looked at the outcomes of different theater campaigns based on their corresponding launch dates. Finally, I looked at these same outcomes in light of their corresponding campaign goals. 

### Purpose
The main purpose of this project was to determine what effect (if any) campaign goals, and time frames had on their outcomes. 

## Analysis and Challenges
A view of the data from a categorical perspective showed that the theater campaigns did better than campaigns in other industries. This should be encouraging for Louise. I divided up the mean, median, standard deviation, upper and lower quartile, and IQR of the goals shown in the table below.  A careful analysis seemed to demonstrate that the lower campaign goals correlated with a higher level of successful campaign outcomes. This is proven when one looks at the mean goal of the successful outcomes ($5,049) with mean goal of the failed outcomes ($60,556). The median yields a similar comparison ($3,000 vs. $8,000 consecutively).  The greatest number of successful outcomes occurred with goals of less than $1000. A study of launch dates and outcomes yields the highest success rate around the months of May and June.

![Variance_Measurements] (path/to/Variance_Measurements.png)

### Analysis of Outcomes Based on Launch Date
Looking at the annual success of outcomes, 2009, for the most part was a bad year for campaigns. The years 2014 and 2016 were fairly successful campaign years. When looking at the monthly outcomes, there was an initial boom in campaign success from January to February, followed by a steady decline from February to March. From then, campaigns began to pick up again until June and began to steadily decline after that. The greatest amount of failing campaigns occurred in October. There was no notable trend in monthly cancelations, other than that there were no cancelations in the month of October. 

### Analysis of Outcomes Based on Goals
There was an overall negative correlation between the number of successful campaigns to goals. This also proved true for the number of cancelations to goals. When comparing the percentage successful to goal amount in U.S. dollars, there seemed to be an initial plummet in success as the goal amount increased. This continued until the goal amount reached the range of $35,000-40,000. At this point the campaigns increased in success with higher goals. As one would expect, there was an inverse relationship between percentage successful and failed. The percentage failed was overall positively correlated with goal value. 

### Challenges and Difficulties Encountered
One challenge with this project is that canceled and live campaigns leave an unknown result. There is no way of knowing what these campaigns could have yielded if they had continued unhindered (in the case of the canceled), or concluded (in the case of the live). 

Another challenge was that the pivot chart that I created for the Outcomes Based On Goals section arranged the goals out of order. When I tried to correct this by setting the rows to be in ascending order, the goals still remained somewhat out of order. This could also be the result of user-error.   

## Results

The first conclusion that I would draw from this section is that it seems to be better to launch a theater campaign either early in the year or during the early summer. The late fall and winter seem to be very poor times to launch a campaign. May appears to be a productive period for campaigns as it yielded the highest number (a total of 166). This was also the most successful month. In most other industries, the amount of success seemed to decline during the summer months, and May did not seem to be an exceptional campaign month. 
The second conclusion one could make is that the previous year ended with a long stretch of failing campaigns. The current year (2017) seems to have started off better possibly indicating a recovery from the failing campaign phase.  


The main conclusion I would make from this section is that it is better to set moderate campaign goals ($5,000 or less) rather than set large goals and not be able to meet them. 

One limitation is annual range. There is only data for the years 2009 and onward. The amount of time required to achieve the goal is another variable. Some of the campaigns had shorter deadlines, and so there was less time to meet the required goal. This adds difficulty in determining outcomes based solely on goals or launch dates.  

There could be another column that indicates the theme or cause of the fundraiser. People oftentimes take into consideration the cause they are supporting when donating money. There could be a general subject category of the theme such as, “social justice” or “the arts” or “humanitarian.” It might be interesting to compare the outcome of success to this parameter. 
