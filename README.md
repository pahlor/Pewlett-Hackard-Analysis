# **Overview of Pewlett-Hackard Employee Analysis**

The purpose of this analysis of Pewlett-Hackard employee data was two-fold. The first part of the analysis was to determine the extent of how many employees will be retiring soon based on their position and title so the company can better prepare for the impact on the company as current employees reach retirement age. The second part of this analysis was to determine which employees are eligible to participate in a mentorship program based on age (born between January 1, 1965 and December 31, 1965). 

# **Results**
* There are a total of 72,458 employees retiring. 
* The majority of the open positions will be Senior Engineer and Senior Staff. See complete breakdown of retiring titles below.
    *  Senior Engineer: 25,916
    *  Senior Staff: 24,926
    *  Engineer: 9285
    *  Staff: 7636
    *  Technique Leader: 3603
    *  Assistant Engineer: 1090
    *  Manager: 2
* There are a total of 1549 employees who are eligible to participate in a mentorship program.
* The breakdown of current positions of employees eligible to participate in a mentorship program do not necessarily align with the position titles and volume retiring from each position.

![](Pewlett-Hackard-Analysis%20Folder/Data/mentorship_eligible_top_titles.png)
###### *SQL Table Output of Mentorship Eligible Employees based on Title*

# **Summary**
Pewlett-Hackard will need to fill a very large number of positions as a result of the "silver tsunami", over 70,000 positions with the majority of those positions being Senior Engineer and Senior Staff positions. Assuming the current employees who are eligible to participate in a mentorship program assumes the vacant roles that are left by those retiring, there will still be a need of almost 71,000 positions to be filled.

Based on our limited queries and data analysis, at a high level, if we just compare the total number of employees retiring against those that are eligible to participate in a mentorship program, there will be more than enough retirement-ready employees to mentor the next generation of Pewlett-Hackard employees. The total number of retirement-ready employees is 72,458 individuals, compared to 1,549 individuals who are eligible for a mentorship program.

Additional queries that will help us to better understand the impact of the "silver tsunami" and prepare is to run a query specific to the upcoming years and the breakdown of positions that will be retiring each year. This will give us more detailed information on if there are specific positions within the company that should be prioritized in the mentorship program and/or that we need to strategically plan for how we will market and attract talent for those positions.

Another query that will helpful in this analysis and our preparation is to analyze the average number of positions (in addition to what those positions are) as employees build history and tenure with the company. This knowledge will help us to understand on movement of employees in the company and what positions and career trajectories are appealing to the existing employee base. From this query, we can assess then what eligibility requirements should be for participation in a mentorship program. Currently our list of eligible employees for participation is based on age (born between January 1, 1965 and December 31, 1965). Rather than generate a list of eligible employees based on age, perhaps setting eligibility based on length of employment history with the company may be more appropriate. This will allow us to start mentoring, preparing and recruiting existing employees for advanced positions earlier on in their career with the company.
