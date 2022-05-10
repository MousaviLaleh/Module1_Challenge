# Kickstarter Challenge: Louise’s play fundraising goal
## Overview of Project
Louise, a playwright, wants to start a crowdfunding campaign fund her play, Fever, with estimating a budget of over $10,000. With using Excel to organize and analyze crowdfunding data, we will determine whether there are specific factors that make a project’s campaign successful. The purpose is to help Louise to gain a greater understanding of campaigns from start to finish, and we'll be able to set her campaign to mirror other successful ones in the same category.<br/>
- The funding goal is the amount of money that a creator needs to complete their project. <br/>
- Funding on Kickstarter is all-or-nothing. No one will be charged for a pledge towards a project unless it reaches its funding goal. This way, creators always have the budget they scoped out before moving forward.<br/>
- A creator is the person or team behind the project idea, working to bring it to life.<br/>
- Backers are folks who pledge money to join creators in bringing projects to life. Kickstarter is not a store, backers support a creative process.<br/>
- 

### Purpose
Louise wants to know how different campaigns fared in relation to their launch dates and their funding goals.

## Analysis and Challenges
After retrieving the data from previous campaigns, and performing it into a readable format in excel, we can help Louise set up her incentives by first determining how much money people have pledged to campaigns historically.<br/>

### Analysis of Outcomes Based on Launch Date
To help the Louise plan her campaign timeline, we need to take a closer look at how campaign length might be tied to its outcome. We should consider time, or more specifically, whether the length of a campaign makes a difference in determining its success. For example, is a shorter or longer campaign more effective? Is there a certain time of year when campaigns tend to be more successful?<br/>
![outcomes_vs_launch.png](/resources/outcomes_vs_launch.png)<br/>
Line charts are helpful when trying to determine trends. The chart shows the months that launched the most successful campaigns was May, June and July. Although Feb, Apr, and Aug have the same range of oucomes, but in compare with others, they can provide quiet well outcome. However, May to October, all had roughly the same number of failed campaigns launched. Overal May, Jun and July is the best time to run her campaigns.<br/>

### Analysis of Outcomes Based on Goals
To continue to help Louise plan her campaign, we need to be more specific with our searches. In this way we'll be able to pinpoint the ones most similar to Louise's vision. Now, we need to collect the outcome and goal data for the “plays” and visualize the percentage of successful, failed, and canceled plays based on the funding goal amount.<br/>
![outcomes_vs_goals.png](/resources/outcomes_vs_goals.png)<br/>
The graph is based on the goals and the percentage(suucess, failed, cancelled). Goals are in the range of 5000.
Each percentage is coming from the subcategory data filterd by "plays", meaning that only those specific subcategories are considered in this outcome, because it had the most successfull occurances.<br/>


### Challenges and Difficulties Encountered


## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. Between May and June are the best time to run a campaign.
    2. July has the least canceled theater project, and so is the best time to run the campaign.

- What can you conclude about the Outcomes based on Goals?
    1. The most successful capaigns are the ones have goal less than 5000 or goal between 35000 and 50000.
    
- What are some limitations of this dataset?
    1. There is no current data. The latest one is 2017.

- What are some other possible tables and/or graphs that we could create?
    1. We might need a graph to show the relation between the sucessfull projects and the number of backers.
