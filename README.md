# An Analysis of Kickstarter Campaigns.

### BACKGROUND

Louise's play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset, visualize campaign outcomes based on their launch dates and their funding goals.



### OBJECTIVE

- DELIVERABLE 1: Outcomes Based on Launch Date Chart and Summary.
- DELIVERABLE 2: Outcomes Based on Goals Chart and Summary.
- DELIVERABLE 3: Written analysis of any D1 vs D2 relations. Also, recommend optimal launch quarter.

---
---
---
## DELIVERABLE 1

### Theater Outcomes Based on Launch Date Chart and Summary.
![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/theater_outcome_chart_res/Theater_Outcomes_vs_Launch6.png)

#### Chart Definitions:

- ![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/theater_outcome_chart_res/mrkr_successful.png) Launch date vs number of successful fundraiser outcomes.
- ![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/theater_outcome_chart_res/mrkr_failed.png) Launch date vs number of failed fundraiser outcomes .
- ![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/theater_outcome_chart_res/mrkr_canceled.png) Launch date vs number of canceled fundraiser outcomes.
- ![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/theater_outcome_chart_res/optimal_launch.png)    Optimal fundraiser launch date.
- ![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/theater_outcome_chart_res/optimal_fundraiser_season.png)    Optimal "LIVE" fundraiser season.

#### In Summary 1.0:

The data shows optimal fundraiser launch dates to fall in the month of April. While the optimal "LIVE" fundraiser runtime appears to fall between the months of May and August, which also shows the highest probability of successfully meeting/exceeding a campaign goal.

Louise's fundraiser was launched late into the "LIVE" fundraiser season. Therefore the Fever fundraiser campaign did not benifit from the full exposer time of the entire "LIVE" runtime season. Moving forward, when launching any new fundraisers, please take into consideration of the 2 stage fundraiser success plan. Launching in April (stage 1) will greatly benifit your fundraiser campaigns exposer time during the "LIVE" (stage 2) runtime.

### Total Backers per Month.
![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/sum_backers_per_month_res/outcomes_vs_backers1.png)

#### Chart Definitions:

- ![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/theater_outcome_chart_res/mrkr_successful.png) Launch date vs number of successful fundraiser outcomes.
- ![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/theater_outcome_chart_res/mrkr_failed.png) Launch date vs number of failed fundraiser outcomes .
- ![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/theater_outcome_chart_res/mrkr_canceled.png) Launch date vs number of canceled fundraiser outcomes.
- ![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/theater_outcome_chart_res/optimal_launch.png)    Optimal fundraiser launch date.
- ![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/theater_outcome_chart_res/optimal_fundraiser_season.png)    Optimal "LIVE" fundraiser season.

#### In Summary 1.1:

We can also peer into total number of backers per month. Taking a closer look at the "Total Backers per Month" chart, the data for May and October reviels "peak backer traffic". We notice that this correlates very well vs the May and October months from the "Theater Outcomes Based on Launch Date" chart. Indicating that you could launch a very conservative and successful campain in late August in order to catch the "LIVE" exposer time for the months of September & October.

## DELIVERABLE 2

### Fundraiser Data Density Distribution
![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/nd_goal_density_res/ND_Goal_Density.png)

#### Chart Definitions:

- ![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/theater_outcome_chart_res/optimal_fundraiser_season.png)    Optimal fundraiser goal amount.
- ![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/nd_goal_density_res/suboptimal1.png)    Suboptimal fundraiser goal amount.

#### In Summary 2.0:

Looking closer at the overall distribution of our data set, we find by plotting the data density shows us that most of the fundraising goals hover anywhere between $1,000 and $10,000. We also can determine that there are a few outliers in the dataset that should be removed for an improved apples to apples comparison.

##### Records Removed
- The Time Jumper / Goal = $100mil / outcome = canceled
- Lynnewood Hall Restoration / Goal = $30mil / outcome = canceled
- KJV2015 / Goal = $25mil / outcome = canceled
- Project: eXelcius - Next Generation Movie / Goal = $10mil / outcome = failed

After removing the data points, we find that the optimal fundraising goal ranges between $1000 and $10,000. The Fever fundraiser falls inside the $1,000 to $4,999 bin, in-which 33.4% of the total fundraiser campaigns are allocated to (Blue). This bin/range has a 66% Successful Goal Distribution rate (Green). If Louise takes advantage of the 2 stage fundraising recommendation, that was mention in "DELIVERABLE 1", then funding this campaign will be no problem.

### Outcomes Based on Goals Chart and Summary.
![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/outcomes_based_on_goal_res/Outcome_vs_Goals.png)

#### Chart Definitions:

- ![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/theater_outcome_chart_res/optimal_fundraiser_season.png)    Optimal fundraiser goal amount.

### Outcomes Based on Goals Table and Summary.
![This is an image](https://github.com/jcaraway-na/kickstarter-analysis/blob/main/resources/outcomes_based_on_goal_res/outcome_table1.png)

#### In Summary 2.1:

As illustrated in the chart and table above, we can see a clear data convergence around $10,000. With a goal of $10,000 or less, Louise should be able to successfully fund the campaign. The more conservative the campaign goal is, then the more likly the goal will be met. 

## DELIVERABLE 3

### Written analysis of any D1 vs D2 relations. Also, recommend optimal launch quarter.

#### Final Summary:

After completing the analysis of theater outcomes based on launch date and outcomes based on goals; We can determain the optimal campain start date would be mid to late April. Giving the fundraiser the full "LIVE" exposer time during Q3 (May, June, July, and August). Also, based on the  the "outcomes based on goals" data, setting a more conservative fundraiser goal of less than $10,000 would be recommended. 




