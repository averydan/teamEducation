# teamEducation
#Create a write-up summarizing your major findings. This should include a heading for each "question" you asked of your data, and under each heading, a short description of what you found and any relevant plots.

This project's goal was to analysize the Indiana high school graduation rate verse the waiver graduation rate. Students who attended 4 years of high school, but graduated with a waiver for meeting the state graduation requirements. We'll examine the relationships between graduation and non-waiver graduation rates; school grades; poverty rates; and school spending.

Data used in this project was gathered from https://www.census.gov/ and https://www.doe.in.gov/.

What is the differnece between the reported graduation rate and the non-waiver graduation rate?






What is the relationship between waiver graduates and school grade?
To beging, let's visualize the school grade data. See the multiline graph below. It showes the number of schools in each letter grade by year. Insights gleened from this visualization of the letter grades is that there may have been a change in grading schools from 2015 to 2016. We speculated that was a result of a new state administration elected to lead the education department. If I had another two weeks, I would look into this further. Another insight is that D and F schools do not add up to many schools.

School Grade Count MultiLine Graph: (https://github.com/averydan/teamEducation/blob/main/Output_Data/schoolgradecount.png)


The anova analysis below compares average percent change in graduation rates per school letter grade in 2015. I expected there it be a statistical difference between how high performing schools and lower performing schools use graduation waivers. There was a satistical difference. Also, not all outliers are to be discarted from the data. In the case of schools, the outliers show us problem schools. If I was a state leader in eduation, I would use outliers to pinpoint schools that need help. I would road trip to talk to school administration, teachers, staff, and students in schools that graduating more students who don't meet state requriments for graduation. Was there an natural disaster that year? Did the drug addiction rate skyrocket in these locations? This analysis of the graduation waiver program left us with plenty of question for futher exploration.

anova analysis: (https://github.com/averydan/teamEducation/blob/main/Output_Data/schoolgradeanova.png)

Finally, the average percent change from the reported graduation rate to the non-waiver graduation rate were calculated to isolate the waiver graduates for analysis. In bar graphs below, each letter grade's average percent change in grad rate is represented for each year. From 2015 to 2019 the use of graduation waivers went up significantly. That means more students are attending 4 years of high school in Indiana and leaving without meeting the graduation requirments. In a world that requires more and more understanding of S.T.E.M subjects and jobs for unskilled labor are dwindling, this is concerning.I did this analysis on 2015. Out of all of the years obsurved in the data, 2015 data showed the least use of graduation waivers and the least difference between higher performing schools and lower performing schools in that use of waivers. If I did run an anova analysis on the other years we would see even more statistical difference beween the letter grades. For example, the outliers in 2015 showed up to 25% use of graduation waivers. In 2019, the average percent percent change in graudation to non-waiver graduation was over 50%. There is definatly a trend upwards from 2015 tp 2019.

2015 Average Change in Graduation Rates per School Letter Grade: (https://github.com/averydan/teamEducation/blob/main/Output_Data/AveragChange15.png)
2016 Average Change in Graduation Rates per School Letter Grade: (https://github.com/averydan/teamEducation/blob/main/Output_Data/AveragChange16.png)
2017 Average Change in Graduation Rates per School Letter Grade: (https://github.com/averydan/teamEducation/blob/main/Output_Data/AveragChange17.png)
2018 Average Change in Graduation Rates per School Letter Grade: (https://github.com/averydan/teamEducation/blob/main/Output_Data/AveragChange18.png)
2019 Average Change in Graduation Rates per School Letter Grade: (https://github.com/averydan/teamEducation/blob/main/Output_Data/AveragChange19.png)



What is the relationship between waiver graduatation rates and poverty?




What is the relationship between waiver graduation rates and school budget?




