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
* What features are most important for predicting loan suitability?
* How can we develop machine learning models that accurately predict loan approvel based on customer information?

## Data

* Data Source : I am using a Kaggle dataset to predict loan defaults based on customer behavior. The dataset contains information about customer and risk flags, which are indicators of how likely a customer getting loan or not.
* Data Link :  https://www.kaggle.com/subhamjain/loan-prediction-based-on-customer-behavior
* Data Size : 5 MB
* Data Shape : Total number of rows 252000 , Total number of columns 13


Data Dictionary :

income: Income of the user.

age: Age of the user.

experience: Professional experience of the user in years.

profession: Profession of the user.

married/single: Marital status of the user (e.g., "Married" or "Single").

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

## Exploratory Data Analysis

#### Data Loading
- Loaded the csv data file and read the data file.
-  Print the shape of the dataset.

#### Data cleaing
- Read the columns that the present in the dataset.
- check the null values present in the dataset.
- Remove the unwanted columns.
- Columns names are unevenly represented like some are in lower case and some are in upper case, so convert the all columns in lower case.
- clean and extract alphabetical portions from the 'city' and 'state' columns of the DataFrame.
- Convert the columns( Married/Single,House_Ownership, Car_Ownership )from catagorical to numerical variables.

#### Expoloratory Data Analysis
- **Analysis among the professions**
  
  ![download](https://github.com/DATA-606-2023-FALL-THURSDAY/Mutukuri_siva/assets/113646588/01c23964-c0ad-4569-a757-c7dcfd8071ea)

  Using the barplot to findout Top 15 professions in the dataset.
 
- **Create a countplot for 'house_ownership'**.
  
  ![download](https://github.com/DATA-606-2023-FALL-THURSDAY/Mutukuri_siva/assets/113646588/2a5aa72d-c4ed-44e0-9d8d-2050c3b88b19)

  In the above graph we can observe that rental individuals are higher compaire to the two other categories.
  
- **How is house ownership related to risk flag?**
  
  ![download](https://github.com/DATA-606-2023-FALL-THURSDAY/Mutukuri_siva/assets/113646588/4f1baa6f-35bb-454a-9a2d-35cad0d61f62)
  
  We can see from the charts above that renters have the highest risk of defaulting while people that own properties are less likely to default.

- **Find out how many individuals are married and how many are single in the dataset**

  ![download](https://github.com/DATA-606-2023-FALL-THURSDAY/Mutukuri_siva/assets/113646588/082fcfd4-fdfc-421b-9383-133314b46225)
  
  From the above graph we can observed that single are higher then the married individuals.
  
- **How is Marital Status related to risk flag?**

  ![download](https://github.com/DATA-606-2023-FALL-THURSDAY/Mutukuri_siva/assets/113646588/fb7ba19c-4486-4755-930f-ee2141e12105)
   
  We can observe that the low risk factor among married individuals is lower than the single individuals.
   
- **Identify the profession with the highest income in the dataset**.
  
  ![download](https://github.com/DATA-606-2023-FALL-THURSDAY/Mutukuri_siva/assets/113646588/df406052-1185-48ee-8a60-742e8e98706c)
  
  From the above graph top 3 professions are Petroleum engineer, psychologist, designer and last 3 professions are drafter, flight attendent, Police officer.

- **counting the risk flag**
  
  ![download](https://github.com/DATA-606-2023-FALL-THURSDAY/Mutukuri_siva/assets/113646588/d79464e5-8756-4b17-9555-9b672a0085e0).
  
  In the dataset, the "risk_flag" column contains significantly more 0 values (221,004) than 1 values (30,996). This class imbalance indicates that the dataset is unbalanced, as one class (0) greatly outnumbers the other class (1).

- **Using the RandomOverSampler for the balancing the dataset**
  
  ![download](https://github.com/DATA-606-2023-FALL-THURSDAY/Mutukuri_siva/assets/113646588/888dcc14-5a88-4188-9333-9a1cb2fb2e81) 

  Now the dataset is balanced among the distribution between low risk and high risk factors in the riskflag column.





