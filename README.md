# Kickstarting with Excel
##
## Overview of Project
### *Purpose*
#### The purpose of this analysis is to supply our client Louise with filtered and usable information to help her make informed discissions on crowd funding using the Kickstarter data. Using Excel, we supplied her with readable and searchable data, tables, and charts to help Louise with future decision making using past data for her crowd-sourcing project campaign.
##
## Analysis and Challenges 
### *Analysis of Theater Outcomes Based on Launch Date*
#### A Pivot Table (https://github.com/Chipsheffield/kickstarter-analysis/blob/main/Resources/Theater%20Outcomes%20By%20Launch%20Date%20Table%20.png) was created to look at Successful, Failed, and Canceled Outcomes by Month and then used to create the following Pivot Line Chart (https://github.com/Chipsheffield/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png) to aid in Analysis of the Kickstater Campaign Data. 
#### 
### *Analysis of Outcomes Based on Goals*
#### A new sheet was created looking at the number of Successful, Failed, and Canceled Outcomes for Plays from the Kickstarter Campaign using the Goals data column (https://github.com/Chipsheffield/kickstarter-analysis/blob/main/Resources/Outcome%20Based%20On%20Goals%20Table.png). This sheet was used to create a new Pivot Chart that shows the Outcomes by percentage for the above based on Goal (https://github.com/Chipsheffield/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png). 
#### 
### *Challenges and Difficulties Encountered*
#### The biggest challenge for this module was trying to set the criteria and ranges for all the different formulas used, and insuring they worked across multiple pages. Given the sheer size of this dataset, this was impossible to spot check and in the case of COUNTIFS had to be taken on faith. 
##
## Results 
### *What are two conclusions you can draw about the Outcomes based on Launch Date?*
#### That the best month to likely launch a Successful Theater Campaign is May or June, and the worst is in December. Also, the chance of launching a Canceled Theater Project is very low no matter the month. (https://github.com/Chipsheffield/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png) 
####
### *What can you conclude about the Outcomes based on Goals?* 
#### That the percentage of Outcomes Canceled for plays was found to be zero for all Goals, which shows that the likelihood of a Play being canceled once a goal has been set is zero, and the percentage of Failed Projects increases while Successful Projects decrease and vice-versa. Also, it was found that a Play with a Goal in the 45000-to-50000-dollar range has a 100% chance of Failure, and the next highest chance of failure being for the range of 50000 or more. So, plays with a Goal of 45000 or more should be avoided.  (https://github.com/Chipsheffield/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png) 
####
### *What are some limitations of this dataset?* 
#### The size of this dataset is a major limitation. It was hard if not impossible to spot check the analysis data for many of the tables, charts, and graphs because Kickstarter in its final form contains 86,415 data cells. 
####
### *What are some other possible tables and/or graphs that we could create?* 
#### When creating charts based on percentages of total, we could have used Pie-Charts to give a quicker and more accurate description. 
