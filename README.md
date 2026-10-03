# Customer-Churn-Analysis
## Project Workflow
![ข้อความอธิบายรูปภาพ](images/Project_workflow.png)
## Project Overview
This project aims to predict customer default risk and identify the key drivers behind loan defaults.
## Dataset 
* credit_score (num)(independent variable)
* country (nominal catagorical)(independent variable)
* gender (nominal catagorical)(independent variable)
* age (num)(independent variable)
* tenure (ordinal catagorical)(independent variable)
* balance (num)(independent variable)
* products_number (num)(independent variable)
* credit_card (nominal catagorical)(independent variable)
* active_member (nominal catagorical)(independent variable)
* estimated_salary (num)(independent variable)
* churn (target variable)
## Exploratory Data Analysis
### Distribution Analysis
#### Credit Score
![Distribution of credit score](images/credit_score_dist.png)
#### Age
![Distribution of age](images/age_dist.png)
#### Tenure
![Distribution of tenure](images/tenure_dist.png)
#### Balance
![Distribution of balance](images/balance_dist.png)
#### Estimated Salary
![Distribution of estimated salary](images/estimated_salary_dist.png)
#### Finding from distribution analysis
* Credit score histogram is like a bell curve that has concentrated point ~680-690 and has a tall rightest tail which represent a group of person who got full score.
* Hightest age range of customer is 36-38 years old and age histrogram is right screw with mean we need to take a log before performing on logistic regression model.
* Two lowest tenure age are 0 and 10 yaers(each of them is 4-5% of all) and each of the remaining tenure age is around 10%.
* After plot a net worth balance histogram, seperating between two group. First group is a zero networth account estimated 36% and second group is a account that has more than zero networth balance look like a bell curve which has highest point around 120k.
* Estimated salary histogram indicates that at all range of salary contain a similar number of account inside it.
### Default Rate Analysis
#### Credit Score
![Default Rate of credit score](images/credit_score_def.png)
#### Age
![Default Rate of age](images/age_def.png)
#### Tenure
![Default Rate of tenure](images/tenure_def.png)
#### Balance
![Default Rate of balance](images/balance_def.png)
#### Products Number
![Default Rate of products_number](images/products_number_def.png)
#### Active Member
![Default Rate of active member](images/active_member_def.png)
