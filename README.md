# R365_Assessment
Max Krueger's assessment for R365 RevOps Position

Questions:

1/ What is our win rate % for each job title?

The Franchisee Win Rate (%) is 81.25%.
The VP of Operations Win Rate (%) is 76.19%.
The COO Win Rate (%) is 75.00%.
The Owner Win Rate (%) is 72.73%.
The CFO Win Rate (%) is 71.43%.


2/ You’re meeting with the head of Marketing. Which job title and business type would you recommend they prioritize in their outreach, and why?

Burger Joints are the only type of restaurant that we've lost opportunities with, so we'll focus our attention on winning them over first.

With Burger Joints, CFOs and COOs are the titles with the most opportunities and the only two titles that we've had some win traction with. As far as potential amount goes, losing opportunities with CFOs results in the largest amount missed ($11,666.67 on average), followed by Owners ($8,500 on average) and COOs ($7,540 on average), respectively. If we factor in the amount gained from the CFO/COO wins, losing opportunities with Owners is the most costly loss, around $1,000 above CFO losses. Therefore, I would recommend Marketing prioritize Burger Joint CFOs, as there appear to be more lucrative opportunaties with CFOs, and we have had some previous success with them as well. After CFOs, I would recommend they target Burger Joint Owners because there are quite a few lucrative opportunities that we have yet to have success with.


3/ If a lead converts the same day, what is the probability that the deal will be won?

There are 43 total observations with 38 wins. The sample mean is 0.88 and the sample standard deviation is 0.32. If a lead converts on the same day it is created, the probability that the deal will be won is between 74.92% and 96.11%, with 95% confidence, and is estimated to be 88.37%.

4/ What other insight(s) would you bring to our attention from this data?

For the following observations, I partioned the dataset according to the quartiles of conversion time and time between conversion and closing. I then grouped the dataset by the respective variables and took the aggregate mean of wins and dollar amount. Here's what I found:

It appears we are most likely to win an opportunity if the lead converts between 0 and 2 days after creation, with 1 to 2 days conversion time being slightly more likely to result in a win than same-day conversion. After 2 days without conversion, the probability that the lead will result in a win drops significantly, and past 7 days even further. Furthermore, these leads that take longer to convert appear to have greater amounts on average than leads that convert in 0-2 days. Given these findings, more focus should be placed on a potential lead in the first 2 days after creation.

It also appears that we are significantly more likely to have a win when the closing date is between 26-45 days after conversion, with these leads having the second-highest dollar amounts. Leads that have 76+ days between conversion and closing have the highest dollar amounts and are also the least likely to result in a win. However, the difference is not as large as the results above. Leads that take longer than 75 days to close after conversion still result in a win more than half of the time. Given these findings, it may be beneficial to focus more energy on leads as they approach 45 days after conversion.

Thanks for reading! Please don't hesitate to contact me with any questions or if you're having trouble accessing the jupyter notebook. If needed, I can transfer my work to an excel worksheet. This was fun!