## Title and Author

* Project Title: U.S. CHRONIC DISEASE INDICATORS ANALYSIS

* Prepared for UMBC Data Science Master Degree Capstone by: Dr. Chaojie (Jay) Wang

* Author: Siva Sri Vasthsasa Mutukuri

* Link to the author's GitHub profile: https://github.com/DATA-606-2023-FALL-THURSDAY/Mutukuri_siva

* Link to the author's LinkedIn profile: https://www.linkedin.com/in/siva-mutukuri/

* Link to PowerPoint presentation file: 

* Link to Youtube Video:


## Background 


* Chronic diseases are a major public health concern in the United States. According to the Centers for Disease Control and Prevention (CDC),  chronic diseases such as heart disease, stroke, cancer, and diabetes are the leading causes of death and disability in the US. 

* U.S. Chronic Disease Indicators (CDI) is a database maintained by the Centers for Disease Control and Prevention (CDC) that provides access to state-level data on 20 over chronic disease indicators.


* The United States Chronic Disease Indicator is a crucial tool in the effort to monitor, manage, and combat chronic diseases in the United States. By standardizing the collection and exchange of health data related to chronic conditions, it plays a vital role in improving healthcare quality, patient outcomes, and public health strategies.




## Research questions

* Trends in Chronic Disease Prevalence: What are the trends in the prevalence of chronic diseases over the years covered by the dataset?

* Geographical Variations: Are there significant geographical variations in the prevalence of specific chronic diseases or health outcomes? Do certain regions have higher or lower rates of chronic conditions?

* Health Disparities: Health disparities exist among different demographic groups. For example among age groups and genders.


## Data

* Data Source : https://catalog.data.gov/dataset/u-s-chronic-disease-indicators-cdi/resource/f89aad64-f014-4e84-a1c1-cbb0d52b575a
* Description:  The the Centers for Disease Control and Prevention (CDC) Division of Population Health has created a standardized set of 124 indicators that states, territories, and large metropolitan areas can use to collect and report chronic disease data. These indicators were developed through consensus and are important for public health practice.
* The U.S. Chronic Disease Indicators (CDI) dataset includes data from the years 2001 to 2021.
* Data Size : 342 MB
* Data Shape : Total number of rows 1185676 , Total number of columns 34


Data Dictionary :

YearStart: The starting year of the data for a particular record.

YearEnd: The ending year of the data for a particular record.

LocationAbbr: Abbreviated code representing the location where the data was collected.

LocationDesc: Full name of the state or territory where the data was collected.

DataSource: Information about the source or organization providing the data.

Topic: General topic area of the data, such as "Cancer" or "Diabetes".

Question: Specific question or aspect of health being measured by the data.

Response: This column appears to be empty or contains no data.

DataValueUnit: Unit of measurement for the DataValue column.

DataValueType: Type of data being recorded.

DataValue: The actual data value for a particular record. 

DataValueAlt: An alternative data value, represented as a floating-point number.

DataValueFootnoteSymbol: Symbol related to footnotes for data values.

DatavalueFootnote: Actual footnotes associated with data values.

LowConfidenceLimit: Lower confidence limit for data values.

HighConfidenceLimit: Upper confidence limit for data values.

StratificationCategory1: General category for the stratification variable.

Stratification1: Specific category within the general stratification category.

StratificationCategory2: This column appears to be empty or contains no data.

Stratification2: This column appears to be empty or contains no data.

StratificationCategory3: This column appears to be empty or contains no data.

Stratification3: This column appears to be empty or contains no data.

GeoLocation: Geographic location information.

ResponseID: This column appears to be empty or contains no data.

LocationID: Identifier for the location where the data was collected.

TopicID: Identifier for the general topic area.

QuestionID: Identifier for the specific question or aspect of health.

DataValueTypeID: Identifier for the type of data.

StratificationCategoryID1: Identifier for the general stratification category.

StratificationID1: Identifier for the specific stratification category.

StratificationCategoryID2: This column appears to be empty or contains no data.

StratificationID2: This column appears to be empty or contains no data.

StratificationCategoryID3: This column appears to be empty or contains no data.

StratificationID3: This column appears to be empty or contains no data.


# Target Variable and Predictors

Traget variable:
The target variable is Datavalue. This column contains the actual data value for a particular record, such as the prevalence of a chronic disease in a population, the number of deaths from a chronic disease.

Features:
YearStart, YearEnd, Topic, LocationDesc, Question,StratificationCategory1,Stratification1





