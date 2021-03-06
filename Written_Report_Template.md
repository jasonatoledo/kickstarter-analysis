# Kickstarting with Excel - Louise's Plan to Kickstart

## Overview of Project
Louise is interested in starting a Kickstarter campaign to raise funds via crowdsourcing for her theater production. She wants to better understand how other similar campaigns have fared in the past by using a thorough data analysis.
### Purpose
The purpose of the analysis through excel is to provide Louise with factual data about past campaigns and their success rates. In addition, this analysis will help discover any trends and patterns in the data to help Louise plan and prepare for her campaign in the hopes to have a successful campaign herself.
## Analysis and Challenges
After doing a bit of data cleanup, I was able to create meaningful chart visualizations and pivot tables to help Louise understand when the most successful campaigns are and the success rate of campaigns by goal amount. I built a descriptive statistics supportive analysis to provide additional information to help Louise further understand how successful and failed campaigns compared.
### Analysis of Outcomes Based on Launch Date
There are two noticable conclusions that Louise can draw from the Outcomes Based on Launch Date analysis. The first conclusion we can draw is that the most successful campaigns are started in the month of May, with the best season being late Spring through Summer. The second conclusion about the data is the least successful campaigns begin in the month of December, with the preceding and following months being next worst overall. Another  data point is there have been no cancelled campaigns in the month of October, but there isn't enough data to understand the reasoning behind this.
### Analysis of Outcomes Based on Goals
The conclusion I can draw about the Outcomes Based on Goals is that the most successful campaigns quantity-wise have a goal with the range of $1000 to $4999. The highest percentage of successful campaigns are in the "less than 1000" range. 61.6% of campaigns failed once the goal was $15000 or higher.
### Challenges and Difficulties Encountered
One of the challenges I had was building the countifs calculations, where I didn't put >= or <= so it excluded some values, such as "1000" and threw off the total count when I checked the sum total against the raw data. Also, I'm not really a fan of Excel's visualization options when compared to a specialty platform like Tableau or Looker, I find that although they've made improvements in their options, the experience is still rather clunky and not a great user experience. Another issue I encounted was a bit of slowness when using the filters as I kept live formulas in the sheet, whereas I am accustomed to using "paste special/values" in the real world (but I understand for evaluation purposes to leave the formulas intact).
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  see above^
- What can you conclude about the Outcomes based on Goals?
  see above^
- What are some limitations of this dataset?
  
  Some of the limitations that I've seen in this dataset would be a small sample size of theater campaigns at a little over 1,000. More specifically, the range that Louise is interested in for her campaign only contains 534 projects to draw conclusions from. The data only contains 9 years of campaigns, this could be expanded upon to provoide more information. Since Louise is looking at just the theater data, there is a lot of irrelevant data in the file; it could be better to have a higher quality data source.
- What are some other possible tables and/or graphs that we could create?
  
  We could create a histogram chart based on the bucketed goal ranges. We could also create a table to show the number of backers against the successful and failed campaigns to see the distribution of donations. Another chart we could create would be a scatter plot to create a quick-view visualization of the successful campaigns against the goal, where a person could understand the ranges within a few seconds.
