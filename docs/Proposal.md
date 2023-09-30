## Title and Author

* Project Title: Loan approval prediction analysis 

* Prepared for UMBC Data Science Master Degree Capstone by: Dr. Chaojie (Jay) Wang

* Author: Siva Sri Vasthsasa Mutukuri

* Link to the author's GitHub profile: https://github.com/DATA-606-2023-FALL-THURSDAY/Mutukuri_siva

* Link to the author's LinkedIn profile: https://www.linkedin.com/in/siva-mutukuri/

* Link to PowerPoint presentation file: 

* Link to Youtube Video:


## Background 

In India, the surge in loan applications in recent years has posed a challenge for banks. Determining whether a customer is likely to repay a loan at a given interest rate differentiating between a "good" and a "bad" customer has become increasingly complex for bank employees. To address this, there is a pressing need for an Machine learning models that can predict loan suitability. Such a model, driven by historical data and customer attributes, has the potential to streamline the loan approval process and mitigate lending risks. It aligns with India's financial inclusion goals, aiming to facilitate responsible lending practices, spur economic growth, and enhance financial stability.




## Research questions
* What customer behavior factors are most predictive of loan repayment?
* How can we develop machine learning models that accurately predict loan repayment based on customer behavior?

## Data

* Data Source : I am using a Kaggle dataset to predict loan defaults based on customer behavior. The dataset contains information about customer behavior and risk flags, which are indicators of how likely a customer is to default on a loan.
* Data Link :  https://www.kaggle.com/subhamjain/loan-prediction-based-on-customer-behavior
* Data Size : 5 MB
* Data Shape : Total number of rows 252000 , Total number of columns 13


Data Dictionary :

income: Income of the user.

age: Age of the user.

experience: Professional experience of the user in years.

profession: Profession of the user.

married: Marital status of the user (e.g., "Married" or "Single").

house_ownership: Ownership status of the user's residence (e.g., Owned, Rented, Neither).

car_ownership: Ownership status of the user's car (e.g., Yes or No).

risk_flag: Indicator of loan default (e.g., "1" for defaulted, "0" for non-defaulted).

current_job_years: Years of experience in the current job.

current_house_years: Number of years in the current residence.

city: City of residence.

state: State of residence.


# Target Variable and Predictors

Traget variable: risk_flag

Feature Variables: All the other columns in the dataset, such as "income," "age," "experience," etc., which are used to predict the "risk_flag."





