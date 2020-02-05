# Excel-Challenge

Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.
Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. This repository contains an analysis of a database of 4,000 past projects in order to uncover any hidden trends.

Three conclusions that can be drawn from this data is as follows:
1. December is the month with the least number of projects successful (111), and the highest rate of failure. There were 118 projects that failed, therefore the failure rate for this month is 106%. This is also the only month where the rate of failure is higher than the rate of success. 
2. Theater projects are the most popular projects to fund on Kickstarter, comprising of almost 34% (1393 theater projects out of the total 4114) of the overall projects. Within this category, plays were the most popular to fund, with a total of almost 77% of the projects in this sub-category (1066 out of 1393). 
3. Kickstarter is the most popular in the United States. There were 3038 from the States out of a total of 4114 (74%). There are more projects that were started in the States, than all other countries combined. 

Some limitations of this dataset are as follows:
There were quite a few data points (1393 in total) for the theater category, which will give a more accurate representation of the Kickstarter projects in this category. However, some other categories such as journalism had lower representation. There were only 24 projects in the journalism category and these datapoints may not be enough to provide an in-depth analysis. This dataset should not be used to extrapolate predictions about the theater in conjunction with the journalism category due to the large difference between datapoints.
Another limitation is that there is no reason given for why a project was canceled. For example, a Kickstarter project may have been canceled if it was approaching the deadline and was close to failing. In addition, the dataset does not answer why a project might have failed or succeeded. Thus, we cannot predict how the live projects in the dataset will perform. 
Lastly, the dataset has quite a few projects from the United States. Using this dataset to extrapolate data from other countries may not be as accurate. For example, there are only 2 projects from Belgium. 

Other table and graphs that could have been used are:
-	A pie chart to show the percentage of each category in each state. This will give a better visualization of what types of projects are most likely to be successful. 
-	A stacked bar graph showing the number of projects in each country by state. To show what other countries Kickstarter is popular in. This will be faster than going through the country filter.
-	A pivot table with the category and subcategory as a filter. The row will the dollar value of the goal, and the column will be the state. This will show the sweet spot for the goal per category. 
