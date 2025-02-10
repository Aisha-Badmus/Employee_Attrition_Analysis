# Employee Attrition Analysis
## Project Background
Employee attrition is a critical challenge for organizations, affecting workforce stability, operational efficiency, and long-term business growth. High attrition rates can lead to increased recruitment and training costs, reduced productivity, and potential loss of institutional knowledge. To address these challenges, this project aims to analyze employee attrition patterns, identify key drivers, and provide actionable insights to improve employee retention strategies.

### Objective
The primary goal of this analysis is to understand the factors influencing employee attrition and develop data-driven recommendations to reduce employee turnover. Historical employee data was used to uncover trends and correlations that can help make informed decisions to enhance employee engagement, job satisfaction, and retention.

This project examines various aspects of employee attrition, including:  
**1.	Hiring Trends:** Identifying patterns in employee tenure and reasons for departure to predict and mitigate future attrition risks.  
**2.	Demographic Analysis:** Assessing attrition rates across different demographics such as age, gender, department, and job role.  
**3.	Compensation Analysis:** Analyzing the impact of salary on attrition.  
**4.	Employee Performance** Understanding how performance ratings, working pattern contribute to attrition.  
**5.	Employee Satisfaction:** Evaluating factors like job satisfaction, work-life balance, that influence employee retention.  

An interactive Power BI dashboard can be downloaded [here](https://github.com/Aisha-Badmus/Employee_Attrition_Analysis/blob/main/HR%20Analytics%20Solution.pbix)\
Targeted SQL queries regarding various business questions can be found here

## Data Structure & Initial Checks 
Database structure as seen below consists of 5 tables: **Employee, Education Level, SatisfiedLevel, RatingLevel, and PerformanceRating** with a total row count of 6,709 records.

![database structure](https://github.com/Aisha-Badmus/Employee_Attrition_Analysis/blob/main/db%20structure.png)

Prior to beginning the analysis, a variety of checks were conducted for quality control and familiarization with the datasets.\
Minimal data cleaning was required but I ensured data quality by handling missing values, standardizing formats, and eliminating inconsistencies.

## Executive Summary
### Overview of Insights	
Atlas Lab had hired a total of 1470 employees from 2012 to 2022, with a near split between male and female employees and the highest number of hires (833) in the Technology department. A total of 237 employees have left the company within this period with an attrition rate of 16.1%, with highest attrition rate at 22.1% in 2020 which is broadly attributed to the pandemic period. Significant variations in attrition have been recorded based on, ethnicity, tenure, department, overtime, and travel frequency.

Below is the overview page from the Power BI report and more examples are included throughout the report.  
![overview](https://github.com/Aisha-Badmus/Employee_Attrition_Analysis/blob/main/Overview1.png)
The interactive dashboard can be downloaded [here](https://github.com/Aisha-Badmus/Employee_Attrition_Analysis/blob/main/HR%20Analytics%20Solution.pbix)


### Key Insights
**1. Frequent Travelers & Overtime:** Employees who work overtime have the highest attrition rate (30.5%) while those who travel frequently have a 24.9% attrition rate, likely due to burnout or job dissatisfaction. Employees with no travel and no overtime have the lowest attrition at 8% and 10.4% respectively.  
**2. Tenure Impacts Attrition:** The highest attrition occurs within the first two years of employment, suggesting challenges in onboarding and retention. Attrition significantly decreases after five years.  
**3. Sales Department Attrition:** Sales experiences the highest turnover (20.6%) with sales representatives attrition at (39.8%), possibly due to job performance pressures, commission-based pay structures, or lack of career growth.  
**4. Diversity Retention:**  Higher Attrition Among Minority Groups, American Indian/Alaska Native employees have the highest attrition rate at 30% (Female) and 40% (Non-Binary), indicating potential diversity and inclusion challenges.  
**5. Impact of Performance Ratings and Job Satisfaction:** Employees with consistently low manager ratings and self-ratings tend to leave the company at higher rates. Those with improving ratings exhibit stronger retention.

 ![travelovertime](https://github.com/Aisha-Badmus/Employee_Attrition_Analysis/blob/main/travelovertime.png)  ![salesattrition](https://github.com/Aisha-Badmus/Employee_Attrition_Analysis/blob/main/Sales%20Attrition1.png)
 
## Recommendations
**1. Improve Work-Life Balance:** Offer flexible travel policies, remote work options, and better incentives to improve job satisfaction among traveling and overtime employees.\
**2. Implement a Retention Program for New Hires:** Focus on better incentives, mentorship, career development programs, and structured onboarding to reduce high turnover within the first two years.\
**3. Address Turnover in Sales Department:** 3. Re-evaluate commission structures with performance-based incentives, provide career development opportunities, and foster a positive work environment.\
**4. Enhance Diversity & Inclusion Efforts:** Introduce team-building exercises, implement mentorship programs, and refine inclusive hiring and retention policies.\
**5. Monitor and Act on Performance Trends:** Conduct employee experience surveys, foster an open communication environment, identify employees with declining satisfaction and performance ratings early and provide targeted interventions, such as coaching or leadership training.

## Conclusion
By addressing these key areas, Atlas Lab can significantly improve employee retention, enhance job satisfaction, and build a more engaged workforce. Implementing these strategies will contribute to long-term business success and a more positive workplace culture.


