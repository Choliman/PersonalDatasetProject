# PersonalDatasetProject
Repository for Personal Dataset Project for DATA115, Fall 2020

# Motivation 
I have been a foster parent before and have adopted my own children from foster care. By going through this process, I was shown the amount of children and especially teens in the foster care system and seen the affects it can have on their education and the difficulties they face. I started out wanting to figure out how many teens age out of foster care, but I was not able to find public information for that question. My research into the topic did however lead me to public data for foster care children and school performance. From this I began wanting to investigate the affects being in foster care and those unique challenges that arise have on school performance and ultimately graduation from high school. 

# Data Source
The data was collected by [ERDC](https://erdc.wa.gov/) (Education Research and Data Center) for Washington State [DCYF](https://www.dcyf.wa.gov/practice/oiaa/reports) (Department of Children Youth & Families) and made public in a [2019 report](https://www.dcyf.wa.gov/sites/default/files/pdf/reports/FosterHomelessEducation.pdf). The data is from Washington state schools, years 2012-2017. The four year graduation data was from year 2015.

# Processing Steps 
There wasn't much processing of the data that needed to be done, it was more of an organizational matter. From the research tables put together by ERDC I simple extracted the data I found important for my question, I used data from Appendix pages 77, 78, and 79 of the report. The data was separated by race and gave the percentage of students in foster care that tested at or above grade level and the percentage of students not in foster care that tested at or above grade level. I was only interested in the total numbers for all race and genders, and found enough data that adequately represented 3rd, 4th, 6th, 7th, and 8th grade. The data for high school students had both percentage and total number of students included in the report, but the younger grades only reported a percentage. I choose than to uniformly report with percentages for all grades.  For 9th-12th grade the data was a little confusing as the numbers were not broken up by grade. Based on my interpretation of the data, I made the decision that the data represents 9th graders as of 2012, with a four year grad year in 2015 and 5 year grad in 2016. I also made the decision to include the testing information as 12th grade data. 

# Visualization
I then decided on three simple bar graphs. Two for comparing the Math and ELA testing results between those in and out of foster care; followed by a comparison of graduation rates. 


![Graph_1](https://raw.githubusercontent.com/Choliman/PersonalDatasetProject/master/ELA_Standards_Met.jpg) ![Graph_2](https://raw.githubusercontent.com/Choliman/PersonalDatasetProject/master/Math_Standards_Met.jpg)
![Graph_3](https://raw.githubusercontent.com/Choliman/PersonalDatasetProject/master/Graduation_Rate.jpg)

# Analysis
After looking over the data, I started to wonder about the correlation between Math and ELA and if that same pattern was found for all students. This graph easily displays the significant gap between those children in foster care versus the majority of those not. Additionally it shows that, for all students, when there is a lack of skill in one area, there tends to be a lack of skills throughout. This points out the need for a revision in the way public school teaches youth and highlights an even more significant need for those in foster care. 

![CorrGraph](https://raw.githubusercontent.com/Choliman/PersonalDatasetProject/master/CorrelationGraph.png)
