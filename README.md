# An Analysis of Kickstarter Campaigns
##Analyzing fundraising goals using outcomes based on the launch date and fundraising goals.
###Analysis and Challenges:
  In order to find the theater outcomes by launch date, I created a pivot table and filtered the parent category to theater.  Additionally, I created a line chart to view the changes in the outcomes from Jan to Dec.  There were no challenges completing this particular task.  However, an example of a difficulty would be with choosing the wrong fields for the pivot table or adding the fields to the wrong area.
![image](https://user-images.githubusercontent.com/33010018/147375178-fb7cd324-e5b4-4324-a126-8126afbcc00b.png)

  In order to find the outcomes based on goals, I used a table and formulas to find the percentages, total number of projects, and the total count of each outcome based on the goal amount. I also created a line chart to give a visual of the percentages vs the goals of each outcome.  The only difficulty I had was using countifs() when the range had more than one condition.  I search online and none of the examples or explanations seemed to work.  Finally, I was able to play around with the formula and figured it out on my own.  Example(=COUNTIFS(Kickstarter!D:D, ">=1000",Kickstarter!D:D, "<=4999",Kickstarter!F:F,"successful",Kickstarter!R:R,"plays")
![image](https://user-images.githubusercontent.com/33010018/147375324-630845c5-44bf-4b59-9e18-4c2f9cc8ff42.png)

###Results
  Viewing the Theater Outcomes by Launch Date chart, I can see the most successful outcome took place in May and there are very few canceled outcomes overall.  The Outcome based on goals is showing there are no canceled projects in the play category.  However, the project with high goal amounts had a very high failed percentaage.
  I believe both datasets can be better analyzed by finding the mean or average for each outcome and maybe a box plot could better show how the outcomes are distributed vs the project's goals.
