# Case Study 2 - Employee Attrition

This project is a case study of the employee data provided, contained in 3 files:
1) CaseStudy2Data.xlsx - 870 rows of full data, including both attrition and salary (MonthlyRate).
2) CaseStudy2CompSet No Salary.xlsx - 300 rows of full data, except the MonthlyRate is missing, and to be predicted.
3) CaseStudy2CompSet No Attrition.csv - 300 rows of full data, except the Attrition is missing, and to be predicted.
Other than the missing fields that are noted, all columns were present for all data. All three files contain the same columns.

I believe this data orignally came from here:
https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset/

The following are the columns of data provided. I did not receive a description of the columns. 

 1  ID                          : int. unique.
 2  Age                         : int  
 3  Attrition                   : Factor w/ 2 levels "No","Yes"
 4  BusinessTravel              : Factor w/ 3 levels "Non-Travel","Travel_Frequently", "Travel Frequently"
 5  DailyRate                   : int  
 6  Department                  : Factor w/ 3 levels "Human Resources","Research and Development", "Sales"
 7  DistanceFromHome            : int  
 8  Education                   : Factor w/ 5 levels "1","2","3","4","5"
 9  EducationField              : Factor w/ 6 levels "Human Resources", "Life Sciences", "Marketing", "Medical", "Other", "Technical Degree"
 10 EmployeeCount               : int 
 11 EmployeeNumber              : int  
 12 EnvironmentSatisfaction     : Factor w/ 4 levels "1","2","3","4"
 13 Gender                      : Factor w/ 2 levels "Female","Male"
 14 HourlyRate                  : int  
 15 JobInvolvement              : Factor w/ 4 levels "1","2","3","4"
 16 JobLevel                    : Factor w/ 4 levels "1","2","3","4"
 17 JobRole                     : Factor w/ 9 levels "Healthcare Representative","Human Resources","Laboratory Technician", "Manager", "Manufactoring Directory", "Research Director", "Research Scientist", "Sales Executive", "Sales Representative"
 18 JobSatisfaction             : Factor w/ 4 levels "1","2","3","4"
 19 MaritalStatus               : Factor w/ 3 levels "Divorced","Married","Sinle"
 20 MonthlyIncome               : int  
 21 MonthlyRate                 : int  
 22 NumCompaniesWorked          : int  
 23 Over18                      : Factor w/ 1 level "Y"
 24 OverTime                    : Factor w/ 2 levels "No","Yes"
 25 PercentSalaryHike           : int  
 26 PerformanceRating           : Factor w/ 2 levels "3","4"
 27 RelationshipSatisfaction    : Factor w/ 4 levels "1","2","3","4"
 28 StandardHours               : int  
 29 StockOptionLevel            : Factor w/ 4 levels "0","1","2","3"
 30 TotalWorkingYears           : int  
 31 TrainingTimesLastYear       : int  
 32 WorkLifeBalance             : Factor w/ 4 levels "1","2","3","4"
 33 YearsAtCompany              : int  
 33 YearsInCurrentRole          : int  
 34 YearsSinceLastPromotion     : int  
 35 YearsWithCurrManager        : int  