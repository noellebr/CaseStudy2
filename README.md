# Employee Attrition  
A project analyzing factors that lead to employee attrition as well as further analysis of existing employee data for DDSAnalytics, an analytics company that specializes in talent management solutions for Fortune 1000 companies. This project was created for MSDS 6306 by Noelle Brown, William Gonzalez, and Ann Nelson.

## Executive Summary

### Introduction
This project was created for DDSAnalytics, an analytics company that specializes in talent management solutions for Fortune 1000 companies. According to DDSAnalytics, "Talent management is defined as the iterative process of developing and retaining employees. It may include workforce planning, employee training programs, identifying high-potential employees and reducing/preventing voluntary employee turnover (attrition)." DDSAnalytics has hired our team of data scientists to predict employee turnover by analyzing existing employee data. The company can utilize this analysis to predict factors that lead to employee attrition and potentially prevent voluntary employee attrition.  
### Project Goals
The main goal of this project is to analyze factors that lead to employee attrition to discover the top most influential factors that lead to attrition.  We are also interested in specifics about the company to help DDSAnalytics better understand its employees. We will analyze interesting trends in job roles at the current company as well as job satisfaction. This knowledge can ultimately help DDSAnalytics remain competitive when hiring employees and creating a positive company culture with satisfied employees.  
### Findings
#### Attrition Analysis:
Overall, we found that the number one cause of employee attrition is being a Sales Representative. Sales Representatives are 8 times more likely to have attrition than any other category. The second highest cause of attrition is working overtime; employees who work overtime are 5 times more likely to quit. Additionally, people who travel frequently are 4 times more likely to voluntarily leave the company. After these top three factors, the next most influential factors that lead to attrition are: being a Laboratory Technician, being in Human Resources, being a Sales Executive, travelling rarely, being a Research Scientist, being a manager, having a high number of companies worked, and living a far distance from the company.  
#### Job Roles:
Since we are also interested in analyzing the current company, we ran the rest of our analysis only with current employees.  We found that the manager is the only job role that overlaps departments and that managers and directors tend to be older and have a higher monthly income than other roles (as expected). The only job role where males do not outnumber females in this company is the Manufacturing Director. The most interesting analysis conducted was on Sales Representatives, since this is the position that is most likely to quit. Sales Representatives have the lowest job levels, the lowest average duration at the company, and change managers the most frequently. All of these factors could contribute to their high turnover rates.  
#### Company Specifics:  
Again, we analyzed the company by only including current employees in our analysis. We found that 67% of the company works in Research and Development and that there are 46% more male employees than female employees. We also noticed that job level is strongly correlated to monthly income, which is based on work experience rather than performance. Since everyone in the company receives a performance rating of excellent or outstanding, this holds no weight on income or job satisfaction. Another interesting finding is that the longer employees work for the same manager, there tended to be a longer time there in between promotions. There is a relatively new group of employees at company with 50% of the company working there for less than or equal to 5 years.  
#### Satisfaction:  
Oddly, job satisfaction increases as hourly rate decreases, this is an artifact of erroreous compensation data in the data set (see the Interesting Facts tab for more information). Employees with PhD’s, Sales Representatives, and the HR Manager are the most satisfied, which is intriguing given Sales Representatives are the most likely to voluntarily quit. The most dissatisfied employees are the R&D Directors.  
#### Interesting Findings:  
There seems to be some discrepancies or errors in the data – we would expect a multiplicative relationship between daily rate and hourly rate or daily rate and monthly rate, but we do not see consistency in this data.  
#### Experimentation:
For our attrition analysis, we ran a logistic regression and fit our model using the STEP procedure as our selection procedure. We ran our model against our test data and came out with 91.8% accuracy in our model, so we sorted the factors that lead to attrition by p-values in descending order of influence. For the remaining analysis on the company, we used linear regression modeling.  
### Conclusion
This analysis can help DDSAnalytics gain a competitive edge in this industry by creating a positive climate and culture and decreasing the attrition rate. With only 16% attrition, DDSAnalytics does not have a very high attrition rate to begin with. Our recommendations to lower this percentage even further are as follows:  
1.	Focus time and energy on your Sales Representatives. As this job role was the leading cause of attrition, it would be beneficial to ensure these employees remain satisfied. Things to consider altering about this job role could be the job level the frequent manager changes.  
2.	Do not grant as many overtime hours – employees are more likely to leave if they work overtime, so limit the number of employees that are working overtime hours.  
3.	Check in with R&D Directors – this is the most dissatisfied job role in your company.  
  
Please see our report for more detailed findings and experimentation. Please contact Noelle Brown, William Gonzalez, or Ann Nelson with any additional questions.  

