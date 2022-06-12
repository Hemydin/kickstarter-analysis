# Kickstarting with Excel

## Overview of Project

This analysis aims to understand how different theater campaigns performed in relationship to their launch dates and fundraising goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Data 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/100629325/172766605-3ca4c988-f672-4ef4-9708-1a081100ef04.png)
### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/100629325/172967096-c8d02caf-e777-4c51-a64b-0b858bc19d84.png)

### Challenges and Difficulties Encountered
In my analysis of the Theater Outcomes by Launch Date, I prepared the visual using the pivot line chart, which helped uncover the trends of campaign outcomes regarding their launch dates. For the outcomes based on the goals assignment, I pulled the needed information using the Excel COUNTIFS functions and prepared the visual for my conclusion. My challenge was to think of new ways to reveal insights about what factors potentially contribute to success.

## Results

What are two conclusions you can draw about the Outcomes based on Launch Date? 

![Theather Outcomes vs Launch Pivot](https://user-images.githubusercontent.com/100629325/173246307-45968d82-cef3-42b1-9e33-1a67eac3b553.png)

 - While looking at the theater data, I have found that the theater campaigns were overall successful. There were 839 successful campaigns which weight about 61% of the total number of theater campaigns 1,369.
 - A spike of successful campaigns began in May, but it keeps dropping by the end of the year. May and June seem good months to launch a campaign, and December tends to be the least successful month for the theater campaigns. Also, we can see that May, June, July, August, and October had roughly the same number of failed campaigns launched.


What can you conclude about the Outcomes based on Goals?

- It appears that play campaigns had been the most successful when the fundraising goal amounts were less than $5,000 and had the highest failed rates when the goals were set high, from $45,000 to More.

What are some limitations of this dataset?

- This dataset is limited to only the quantitative information about the theater campaigns, such as goals, pledges, backers, etc. We were not given other elements that contributed to the campaign outcomes, such as the popularity of performers, and performance rating, to name a few.

What are some other possible tables and/or graphs that we could create?

![Outcomes Based on Time Elapsed](https://user-images.githubusercontent.com/100629325/172771280-22c30bad-7313-4b1a-ac9b-b39e454c771f.png)

![Distribution of time for successful campaigns to reach goal](https://user-images.githubusercontent.com/100629325/172769987-bb1ed343-2218-4b22-b523-a45c825acfd1.png)

- Does the length of the campaign make a difference in determining its success? I calculated the time elapsed to answer this question using the launch and deadline dates. I categorized the entire subset of successful campaigns based on the days each project lasted. Out of the 2,185 projects, 47.6% of successful campaigns had a time elapsed value of 30 to 35 days. The mean number of days for a project to become successful is 33 days, while the median is 30 days. This shows that the distribution is right-skewered, meaning that there are more data points on the left side than on the right. In other words, campaigns tend to reach their goals sooner rather than later.
