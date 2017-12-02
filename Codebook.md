# Codebook
## CaseStudy2-Data.csv
**Description:** This is a dataset that contains a list of 1470 employees with 35 attributes  
**Data Set Characteristics:** This is a comma-separated file  
**Number of Rows, Columns:** 1470 rows, 35 columns
**Column Characteristics:** Character, Integer  
### Attribute Information:
***Attribute Name*** | *Brief Description*  
**Attrition** | A 'yes' or 'no' answer to whether the employee left the company  
**BusinessTravel** | How often the employee traveled from non-travel to rarely to frequently  
**Department** | The department that the employee works in  
**EducationField** | The field studied in the employee's formal education  
**Gender** | Male or female  
**JobRole** | Identifies the job role of the employee  
**Over18** | A 'yes' or 'no' answer to whether the employee is over 18 years old  
**OverTime** | A 'yes' or 'no'answer to whether the employee works overtime  
**MaritalStatus** | Single, married, or divorced  
**Age** | Employee age  
**DailyRate** | Rate that the employee makes per day in USD  
**DistanceFromHome** | Distance that the employee lives from work in miles  
**Education** | A 1-5 indicator of highest educational degree with 1=Below College, 2=College, 3=Bachelor, 4=Master, and 5=Doctor  
**EmployeeCount** | Number of employees the observation is referring to  
**EmployeeNumber** | Number assigned to the employee by the company  
**EnvironmentSatisfaction** | A 1-4 indicator of how satisfied the employee is of the work environment with 1 being low and 4 being very high  
**HourlyRate** | Rate that the employee makes per hour in USD  
**JobInvolvement** | A 1-4 indicator of how involved the employee is at work with 1 being low and 4 being very high  
**JobLevel** | Level of employee's job from 1-5  
**JobSatisfaction** | A 1-4 indicator of the employee's satisfaction with their job with 1 being low and 4 being very high  
**MonthlyIncome** | Income the employee makes per month in USD  
**MonthlyRate** | Rate the employee makes per month in USD  
**NumCompaniesWorked** | Number of companies the employee has worked at in their career  
**PercentSalaryHike** | Percent of employee's salary hike  
**PerformanceRating** | A 1-4 level of performance with 1 being low and and 4 being outstanding  
**RelationshipSatisfaction** | A 1-4 indicator of how satisfied the employee is with relationships at work with 1 being low and 4 being very high  
**StandardHours** | Number of regular hours worked during the two-week pay period  
**StockOptionLevel** | Level of stock options offered to the employee  
**TotalWorkingYears** | Total number of years the employee has worked  
**TrainingTimesLastYear** | Number of trainings the employee attended last year  
**WorkLifeBalance** | A 1-4 indicator of work-life balance in the employee's life with 1 being bad and 4 being best  
**YearsAtCompany** | Number of years the employee has worked at the company  
**YearsInCurrentRole** | Number of years the employee has been in the current role at the company  
**YearsSinceLastPromotion** | Number of years it has been since the employee's last promotion  
**YearsWithCurrManager** | Number of years the employee has worked for their current manager  

## CaseStudy2reorder.csv
**Description:** This is a dataset that contains a list of 1470 employees with 33 attributes (variables that had no variation,that is, are constants and will not aid in the analysis were removed (Over18,EMployeeCount,StandardHours) & columns were reordered to aid analysis)  
**Data Set Characteristics:** This is a comma-separated file.  We then used this to create a data frame titled 'attrit' for our analysis  
**Number of Rows, Columns:** 1470 rows, 33 columns
**Column Characteristics:** Character, Integer  
**Attribute Information:** Same as above

## noattrit
**Description:** This is a data frame with attrition participants removed in order to analyze current company trends.  We are left with 1233 employees when attrition employees are removed  
**Data Set Characteristics:** This is a data frame with 1233 observations and 33 attributes  
**Number of Rows, Columns:** 1233 rows, 33 columns
**Column Characteristics:** Character, Integer  
**Attribute Information:** Same as above  
