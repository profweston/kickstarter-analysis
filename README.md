# An Analysis of Kickstarter Campaigns
## Overview of Project
Famous playwright, Louise, is ready to release her latest creation, *Fever*, with an estimated budget of $10,000. After using Kickstarter as a funding platform, she ultimately fell short of her fundraising goal. To improve her future funding efforts, Louise requested an examination of data provided by Kickstarter for other fundraising campaigns, specifically for theater and play projects. This analysis examines theater projects in relation to the launch date of the campaign and a narrower examination of plays in relation to their funding goals.  Preliminary results indicate that theater projects launched during May are most successful and those launched in October fared the worst. Projects with funding goals of less than $15,000 or more than $45,000 also indicate greater success. 

## Analysis and Challenges

Data used for this analysis was provided by Kickstarter and contained data on numerous variables for 4113 various projects during 2009-2017. The outcome variable was defined as successful if the total pledged contributions met or exceeded the desired goal and as failed if the pledged contributions did not meet the desired goal. Canceled campaigns were those canceled by the creator of the project. 

### Analysis 1
For the first analysis, the data was filtered to the category of theater projects to examine the variables of outcome of the campaign in relation with their launch date during the year. The data set included 1369 total projects with 839 successful projects, 493 failed projects, and 37 canceled projects. This data is presented in the following line graph.


![Theater Outcomes vs Launch](/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis 2

For the second analysis, the data was further filtered using the subcategory of plays. The outcomes were then examined in relation to the desired goal of funding. This resulted in 1047 total projects with 694 successful projects, 353 failed projects, and 0 canceled projects. This data is presented in the following line graph.

![Outcomes vs Goals](/Resources/Outcomes_vs_Goals.png)

### Challenges

The only challenge I encountered during this assignment came with the editing of the README.md file in GitHub. Although making the headers and the text came without difficulty after reading the module, the challenge arose when trying to insert the graph into the file. After failing to get a graph when trying to follow the instructions in the module, I turned to my best friend Google for assistance. I found a video on YouTube that approached the task by using the issue tab. I was successful in this method and cited my source. Ultimately, I wanted to know where I was initially going wrong so I inquired during office hours for assistance with the method presented in the module and learned I was missing a backslash. This method was used in the final product.

## Results

### Theater Outcomes Based on Launch Date

The first graph provides data about three trends in relation to launch date: successful outcomes, failed outcomes, and canceled outcomes. The graph illustrates that the success of the campaign varies according to the month it is launched. Leading up to month of April, the rate of success is up and down. In April, the success starts to steadily increase until it peaks in May. After May, the data shows a somewhat steady decline for the remainder of the year with a slight bump upward in October. Interestingly, the graph of the failed outcomes generally follows the same pattern as the success albeit with fewer outcomes. Both success and failure peak in May and dip in September with a slight uptick in October. The success rate and the failure rate approach each other in December. Overall, approximately 35% of successful campaigns launch in the months of May, June and July while approximately 30% of failed campaigns launch in the same three months. Although these results are somewhat similar, the graph indicates the failure rate is less impacted than the success rate by the time of year.  This is also true of the canceled campaigns as it remains somewhat consistent across the year.

### Outcomes for Plays Based on Goal

The second graph provides data about three trends in relation to funding goals: successful outcomes, failed outcomes, and canceled outcomes. Since no projects were canceled in the play subcategory, the trend for canceled outcomes on the graph is meaningless. On the other hand, since no plays were canceled, each play has a 50% chance of being successful and 50 % chance of failure. Thus, the graph shows a reflective pattern around 50%. In general the pattern of success, and accordingly the pattern of failure, fluctuates according to funding goals. For the projects in this data set, there are three pivot points. The plays with funding goals had more successes than failures when the goal was less than $15,000. This disposition reverses at $15,000 and then pivots one more time to return to the initial propensity for success at slightly less than $45,000 goal. This suggests that low end budget projects and high-end projects are more attractive to backers and more likely to get enough pledges to be successful.

## Limitations

While this study can provide insight into factors that affect successful campaigns, in practice, other variables beyond the ones examined in this analysis could be impacting success or failure. A project may take longer than expected or other circumstances may prevent a project from meeting the campaign deadline resulting in pledges being withdrawn. Moreover, there may be some pledges that are not collected upon resulting in the backer being dropped from the platform. In this case, if the backer is contributing to more than one project, other success rates might be impacted. Also, this analysis is limited to one crowdfunding platform. Other platforms should be examined to validate the results. Lastly, it is difficult to draw comparisons between the two analyses since one is focused on a broader category than the other. To make further comparisons, future analyses might include examining outcomes and launch date on the subcategory of plays or examining outcomes and funding goals on the broader category of theater. 

