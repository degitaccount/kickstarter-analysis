# Module 1: Kickstarter Challenge
## Overview of Project

In Module 1 we used Excel to organize, sort and analyze crowdfunding data to assist Loise, a playwright, plan a funding campaign for her play *Fever*.

Louise has requested addition information regarding past campaigns to help inform her funding strategy.

### Purpose
The analysis in this challenge is intended to answer two questions:
1.	How have past theater campaigns fared in relation to their launch dates?
2.	How have past plays campaigns fared in relation to their funding goals?

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
For this first analysis I leveraged the pivot tables and graphing functionality in excel to organize and analyze the data.  While the pivot and graph provide the same information, the graph is a more visually appealing representation and tends to be more useful for quickly spotting trends.

![Outcomes_vs_Launch_Pivot](https://user-images.githubusercontent.com/80796467/114803943-6320f600-9d6e-11eb-8bda-0bfb08d7ecc3.png)

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/80796467/114804049-9bc0cf80-9d6e-11eb-8d09-7ca7ce7ad483.png)


### Analysis of Outcomes Based on Goals

In order to graph the Outcomes Based on Goals for the plays subcategory, I created a dataset with eight columns and twelve rows.  I started by setting goal ranges in each row, then used COUNTIFS( ), SUM( )and percentage formulas to populate the correct values in each cell.  I then created a line graph to visually represent the data.

![Outcomes_vs_Goals_Table](https://user-images.githubusercontent.com/80796467/114804097-b7c47100-9d6e-11eb-9267-a54c6a0e0f5e.png)

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/80796467/114804109-bdba5200-9d6e-11eb-8190-49c75753f5ff.png)


### Challenges and Difficulties Encountered
In working through the Outcomes Based on Goal, I noticed the goal ranges we were asked to enter did not include “50000” in any ranges.  In other words, none of the ranges would have captured any of the campaigns with a goal of exactly 50000.  

I checked the kickstarter worksheet and noticed that there were 4 failed campaigns in the plays sub-category so I knew that my results will be incorrect if I simply followed the instructions.  To ensure that all in-scope campaigns were captured I modified the last range *from Greater than 50000 to Great than **or Equal** to 50000*.

I did not experience any other challenges or difficulties.  
## Results
**What are two conclusions you can draw about the Outcomes based on Launch Date?**

* The overall success rate of theater campaigns is favorable at approximate 62%

* May and June are the months with the highest number of total theater campaigns, and the success rate during these months is better than average at 65%-67%.

**What can you conclude about the Outcomes based on Goals?**

* Goal amounts do not appear to be correlated to campaign cancelations.

* There is an inverse relationship between the _percentage successful_ and _percentage failed_ for any given goal amount, except for the points where the two lines intersect.

**What are some limitations of this dataset?**

* The data does not include any demographic information about the backers.  For example, information about age, gender and ethnicity could lead to a more targeted campaign to improve the probability of success.

* Another limitation is that we don’t know if there was a minimum donation for any of the campaigns.  Knowing that information could help in determining whether a minimum can help or hurt a campaign’s success rate.

**What are some other possible tables and/or graphs that we could create?**

* Other analysis may include lines graphs representing how the campaigns fared by country as well as how campaigns have fared by year.

