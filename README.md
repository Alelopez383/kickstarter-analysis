# kickstarter-analysis
Challenge Module 1_ PlayFever
# Crowdfunding campaign for the play Fever
## Overview of Project: 
Louise is an up-and-coming playwright who wants to start a crowdfunding campaign to help fund her play, Fever. She estimates a budget of over $10,000 and wants to determine what makes a project campaign successful, so she can kickstart her production. In the beginning, she made a campaign with a goal of $2,885 but only got the 86% of it ($2,485), although the fundraising lasted almost a month, from 13/06/2016 to the 11/07/2016.
## Purpose: 
Louise’s play Fever came close to its fundraising goal in a short amount of time, although it wasn’t completely, now, she wants to know if the launch date or the funding goals have a relation with the outcome of the project.
### Analysis and Challenges: 
-The requested analysis only includes three variables for it, launch date, goal, and outcome of the campaign, when the database contains multiple variables such as country, other types of projects, date of creation and ending, goals, pledged, average donation, percentage fundraising, outcomes, etc. Limiting the analysis to only three variables could be not so enriching.
### Analysis of Outcomes Based on Launch Date: 
-After analyzing the launch date of the campaign with the outcome, we can see that in general, campaigns for funding theater projects have good outcomes. In fact, they have a greater number of successful campaigns than canceled or failed ones.  
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/43974872/177688037-12aede5e-b54f-48cf-aa7c-20b9369ca9a0.png)
- On the other hand, we can determine that there are better months to start a successful campaign, so the months of May, June and July would be the best ones to start a campaign that would be successful. On the contrary, January and December would it be the worst months to start a fundraising campaign.
-However, if we look at the month of May in particular, we can observe that the percentage of successful campaigns due the launch date has 67% of success.
![Theater_Outcomes_vs_Launch %](https://user-images.githubusercontent.com/43974872/177688212-2f4a88f0-168e-447b-a9f1-145aa5f91619.png)
### Analysis of Outcomes Based on Goals. 
-Now, if we observe the successful campaigns through the goal to be raised, we have that, if the goal is less than $4,999 dollars, there will be a higher percentage that the campaign be achieved. However, when the fundraising goal increases, the percentage of failed campaigns also increases.
![Outcomes based on Goals](https://user-images.githubusercontent.com/43974872/177688266-72810357-ee1d-48ab-ba5a-e98326709318.png)
-The above is true, except when the goal is in a range of $35,000 to $39,999 dollars.
![Outcomes based on Goals2](https://user-images.githubusercontent.com/43974872/177688334-73023e0a-642e-4113-a56f-d49aefa0f98d.png)
### Challenges and Difficulties Encountered: 
-Creating new variables using other active sheets of the worksheet was something that initially confused me because of the way is written in the formula. 
-Example:=CONTAR.SI.CONJUNTO(Sheet1!$D:$D,"<1000",Sheet1!$R:$R,"Plays", Sheet1!$F:$F,"Successful")
-So, I needed to understand each part of the formula so I could determine what was wrongly written, when trying to run the formula and didn’t work. That took me the longest. 
### Results: 
- What are two conclusions you can draw about the Outcomes based on Launch Date? The analysis carried out shows us that, first, starting a fundraising campaign in May is a good idea. The second, the worst month to start a campaign is December.  
- What can you conclude about the Outcomes based on Goals? It is just as appropriate to have a fundraising goal between $35-39K as a goal of less to $5K, the percentage of having a successful outcome is about the same.
- What are some limitations of this dataset? I needed to create different variables and pivot tables to understand the information and what was happening with the outcomes of the campaigns.
- What are some other possible tables and/or graphs that we could create? In the first place, I would make a general graph of the outcomes of the different categories. So, you could see that the campaigns to raise funds for theater projects, after music, are the most successful. In addition, with a general graph, within the theater category, the most successful campaigns are plays. So, Louise is doing the right thing with her crowdfunding to fund her play, Fever. Also, I would make a graph with the year, outcomes and theater, because 2017 was not a good year to started one. 
