# Kickstarter-Analysis

## Overview of Project
Helping Louise with her project campaign by analyzing fundraiser data.

### Purpose

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Successful outcomes remained above above 50 percent until December.
Success outcomes trend higher between March and May (peak). Then declining through December.
Trends for failed and canceled outcomes appear to be somewhat flat throughout the observed period.
There appears to be  missing data for cancelled campaigns in October.

### Analysis of Outcomes Based on Goals
Outcomes appear to be at their highest percentage of success when goals are below $4,999. 
However there also appears to be an increase in successful campaigns when goals are between the $25,000 to $44,999 mark.
There were no cancelled campaigns.

### Challenges and Difficulties Encountered
I didn't encounter much difficulty in  this project. There were challenges in clarity regarding the requested outcomes.
Some of the outcomes weren't clear enough. The second outcome of this challenge for example. It asked to create a table using COUNTIFS().
In the pro tip video, the narrator uses "pledged" instead of "goals" as the metric. And filters the data by "US".
This was somewhat confusing in that filtering by country wasn't requested outside of the video.
Also, using "successful", "failed", and "cancelled" as criteria in the COUNTIFS() formula wasn't specified explicitly.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1)May is the best month to launch a successful campaign.
  2)December is the worst month to launch a successful campaign.

- What can you conclude about the Outcomes based on Goals?
1)There's an inverse relationship in outcomes and campaign goals.
2)The highest percentage of successful outcomes are below $4,999.

- What are some limitations of this dataset?
I just noticed that id# 3529 is an actual play by a theatre company in my home town of Kalamazoo. 
So I assume this is real data and that all of this campaign data was procured by some somewhere or online platform.
Some limitations may be whether or not all fundraising campaigns were reported in this platform.
The "Theatre Outcomes Based on Launch Data" chat has missing "cancelled" data for October.
Which means there may have been some error. Otherwise, the data would report zero if there were no cancelled campaigns.

- What are some other possible tables and/or graphs that we could create?
Seeing any trend between the number of backers and successful outcomes.
Seeing any trend between the "staff pick" metric and successful outcomes.
