# **Kickstarting with Excel**

## **Overview of Project**
Louis is an upcoming play writer and wants to launch the crowdsourced fund raising campaign for her Play **Fever** but first she wants to have an idea about outcomes of such campaigns. In order to help her, 
we used a dataset of about 4000 crowdfunding campaigns and analysed the trends to come up with a better answer for Louise.

### **Purpose**
Louis wants to know how the other crownfunded projects performed on the basis of their ***Launch Date*** and ***Funding Goals***. By using the kickstarter dataset, the outcomes based on these 
two aspects were analysed and visualized.

## Analysis and Challenges

Below is the description of Analysis on both the aspects.

### Analysis of Outcomes Based on Launch Date
The data was filtered on the basis of *parent category* of **Theater** and *year* of launching date and analysed on the basis of **successful**, **failed** and **canceled** outcomes. The data was further analysed
to see the outcomes on the basis of months. To visualize the relationship of date of launching and the outcome , a line graph was created and shown below:
<img src="Theater_outcomes_vs_launch"></img>

### Analysis of Outcomes Based on Goals
For this analysis, the ranges of dollar figures of goals were created (like less than $1000, $1000 to $4999 and so on) and number of *successful*, *failed* and *canceled* outcomes were computed.
Then percentages of these outcomes were analysed against the ranges of dollar figures of goals. The visual representation of this relationship is shown in the below line graph:
<img src="Outcomes_vs_Goals"></img>

### Challenges and Difficulties Encountered
While analysing the outcomes based on Launch date, initially I had a little bit of challenge while selecting the correct rows, filters and values in the pivot chart. But then resolved this issue after having the conceptual clarification of the pivot chart from the instructor.

In case of outcomes based on goals, I spent some time to find a dynamic formula to make the ranges in the *Goal* column since I wanted to avoid the manual entries of these ranges but couldnt find
any such formula so had to input the manual entries which increases the chances of error and consume so much of time.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1-Highest number of successful campaigns were launched in May so May seems the best month to launch the campaign.

2-The period from Apr-Jul has the highest number of successful campaigns (ratio of successful campaigns is around 65%) so it seems summer is a good time to launch such campaigns.

- What can you conclude about the Outcomes based on Goals?

The highest percentage of successful campaigns is when the goal is under $1000 (The next best result is when goal is between $35000 to $45000) however this inference might not be helpful for Louise since having
such a modest goal will not be practical for her fundraising campaign. She needs to consider other parameters to plan her campaign.

- What are some limitations of this dataset?

There are many limitations of this dataset for example, the dataset is heavily skewed towards goals of upto $10,000. we dont have great information for camapigns over $10,000.
Then this dataset is heavy on **US** data since its a crowdsourcing camapign, we need to have more information about other countries. Additionally even if **US** data is split into further geographic locations, it
can provide useful insights.

- What are some other possible tables and/or graphs that we could create?

I have further analysed the data on the basis of **Duration of Campaigns** for **plays** subcategory. The analysis shows that the duration of most successful campaigns was ranging from 20 to 39 days.
The line chart showing this analysis is shown below:
<img src="Outcomes Based on Campaign Duration"></img>