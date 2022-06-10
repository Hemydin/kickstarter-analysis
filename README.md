# Kickstarting with Excel

## Overview of Project

The purpose of this analysis is to understand how different theater campaigns performed in relationship to their launch dates and their fundraising goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Data 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/100629325/172766605-3ca4c988-f672-4ef4-9708-1a081100ef04.png)
### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/100629325/172967096-c8d02caf-e777-4c51-a64b-0b858bc19d84.png)

### Challenges and Difficulties Encountered
For the assignments, the Theater Outcomes by Launch Date and the Outcomes based on Goals, I pulled the needed information following the provided instructions and used the visuals for the conclusions. My challenge was to think of new ways to reveal insights about what factors potentially contribute to success.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? 

While looking at the theater data as a whole, I have found that the theater campaigns were overall successful. There were 839 successful campaigns which weight about 61% of the total number of theater campaigns.
The theater campaigns tend to follow the overall trend: there is a spike of successful campaigns that began in May, but it keeps dropping down by the end of the year. May and June seem to be good months to launch a campaign. December tends to be the least successful month for the theater campaigns. Also, we can see that May, June, July, August and October had roughly the same number of failed campaigns launched.

- What can you conclude about the Outcomes based on Goals?

It appears that play campaigns had been the most successful when the fundraising goal amounts were set to the amounts of less than $5,000, and had the highest failed rates when the goals were set high, $45,000 to More.

- What are some limitations of this dataset?

- What are some other possible tables and/or graphhs that we could create?

![Descriptive Statistics](https://user-images.githubusercontent.com/100629325/172769783-92c3f828-1dde-498d-b7e5-dd22a8eb8792.png)

We can add statistical calculations to our analysis to deepen our understanding about the goals and pledges in successful or failed campaigns. I've filtered the Kickstarter data for Successful US Theater campaigns and Failed US Theater campaigns. I've calculated the mean and medium for each data set's goal and pledged columns. 
Conclusions: we can see that failed campaigns have much higher fundraising goals than successful campaigns. Louise estimates that her play will cost $12,000, which is twice than average successful Kickstarter goal, thus her goal is set very high. Also, the pledged mean and the pledged medium of failed projects are much lower than the successful pledges, which indicates there must be other reasons for failures than asking for too much.

![Outcomes Based on Time Elapsed](https://user-images.githubusercontent.com/100629325/172771280-22c30bad-7313-4b1a-ac9b-b39e454c771f.png)

![Distribution of time for successful campaigns to reach goal](https://user-images.githubusercontent.com/100629325/172769987-bb1ed343-2218-4b22-b523-a45c825acfd1.png)

Does the length of the campaign make a difference in determining its success? To answer this question, I calculated the time elapsed using the launched and deadline dates and categorized the entire subset of successful campaigns based on the number of days each project lasted. Out of the total 2,185 projects, 47.6% of successful campaigns had a time elapsed value of 30 to 35 days. The mean number of days for a project to become successful is 33 days, while the median is 30 days. This shows that the distribution is right-skewered, meaning that there are more data points on the left side of the distribution than on the right. In other words, campaigns tend to reach their goals sooner rather than later.
