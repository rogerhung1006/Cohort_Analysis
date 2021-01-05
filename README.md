# Cohort Analysis

## Introduction
Cohort Analysis is a powerful tool that enables businesses to analyze user behavior pattern and uncover actionable insights and thus customized their products and marketing strategy toward different user segments. I find the technique so useful and powerful, and one can learn the complete code on DataCamp. In this project, I performed a cohort analysis with Python on 20% of the UCI Online Retail Dataset

#### What is a cohort?
A cohort is a group of people who have a common characteristic during a period of time. For example, you can group the users based on demographics, first purchase month, or even acquisition channel.

#### Why is it valuable? 
The importance of cohort analysis cannot be overemphasized. Among all the fascinating things that this analysis can achieve, one thing I find most important is that cohort analysis can be helpful when it comes to understanding the loyalty of your customers. This is critical since it’s far cheaper and easier to keep a current customer than to acquire a new one. For startups, it’s also a key indicator of [product-market fit](https://en.wikipedia.org/wiki/Product/market_fit).

## Results
### Example 1. Retention Rates
Both heatmap and line chart are good ways to spot behavioral differences in cohort analysis. I personally prefer to use the heatmap for behavior pattern analysis in specific cohort, and use the other for better comparison between cohorts.
<p align="center">	
	<img align="middle" width=700 src="images/Figure 1. Retention Heatmap.png">
</p>
<p align="center">
  <i>Figure 1. Retention Heatmap</i> 
</p>

<p align="center">	
	<img align="middle" width=700 src="images/Figure 2. Retention Line Chart.png">
</p>
<p align="center">
  <i>Figure 2. Retention Line Chart</i> 
</p>

### Example 2. Average Spending by Monthly Cohorts
Note that in June 2011, the average spending appears to be negative, which may be caused by potential outlier data or other outer factors. A closer examination reveals that nearly all transaction order in that months were canceled. To get a better understanding of what was the driving factor behind this, we would need to dig deeper into the dataset and conduct further research.

As I just mentioned above and according to my experience in running a e-commerce platform, it is always important to call back or retain the active or say, old user on your platform, especially in the beginning stage of a starup. Once you have gained the trust of a group of advocates or core users, they would not only assist in the business metrics you try to accomplish but also bring their friends or relatives to your platform, which is often regarded as the effect of Word-of-Mouth. Here, I demonstrate both the retention rates and average spending on a monthly basis; however, in real case, we tend to perform the analysis on a shorter time intervals, for instance, 7-Day retention rate. Additionally, for a startup, your MVP(Most Viable Product) evolves over time. New features are added and removed. Observing individual groups over time is a starting point to understanding how these changes affect user behavior.

<p align="center">	
	<img align="middle" width=700 src="images/Figure 3. Average Spending Table.png">
</p>
<p align="center">
  <i>Figure 3. Average Spending Table</i> 
</p>

