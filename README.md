<p align="center">This is centered text</p> # PREDICTING PRIMARY CONTRIBUTORY CAUSES OF CRASHES IN CHICAGO
![cars](https://github.com/user-attachments/assets/e288361c-7ced-4d8d-b649-4471d2da5027)

## Problem Statement
Traffic safety is paramount in big cities because of its significant impact on human lives and city resources. This project leverages data science techniques to analyze and predict vehicle crashes in Chicago using the city of Chicago, Driver & Passenger, and Vehicles datasets. By understanding the major factors contributing to accidents, we can develop a predictive model to identify the likelihood of crashes in Chicago. The model aims to provide insight into the factors contributing to crashes to enable authorities to take proactive measures to mitigate the occurence of accidents and improve road safety.

### Aim
The primary objectives are to:

1. Identify the most significant contributing factors to road accidents in Chicago.
2. Provide insights into patterns and trends
3. Help stakeholders implement targeted interventions to reduce road accidents.
4. Develop the best model to address the predictors for road accidents the best  based on metrics.

 
## Data
The Crash data shows traffic crash information within the City of Chicago's streets. It can be found in [Crashes](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if/about_data) and contains 48 columns with over 880K rows. 

Vehicles dataset in [Vehicles](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Vehicles/68nd-jvt3/about_data) contains information about vehicles (or units as they are identified in crash reports) involved in a traffic crash. “Vehicle” information includes motor vehicle and non-motor vehicle modes of transportation, such as bicycles and pedestrians. This dataset has 71 columns with over 1.8M rows.

Driver and Passenger dataset in [People](https://data.cityofchicago.org/Transportation/Traffic-Crashes-People/u6pd-qa9d/about_data) contains information about people involved in a crash and if any injuries were sustained. Each record corresponds to an occupant in a vehicle listed in the Crash dataset. It has 29 columns and over 1.94M rows.

For analysis, the relevant columns from each dataset that best fit our business problem.

## Contents
1. Data Understanding
2. Data Cleaning and EDA
3. Data Analysis
4. Data preparation for modeling
5. Modelling and Evaluation
6. Conclusion

#### Data Understanding : 
      - Exploring the raw data set and understanding the values of each column

#### EDA : 
      - Understanding the null values and evaluating the best steps to eliminate them

      - Imputing null values with meaningful data 
      
      - Removing irrelevant and redundant columns

#### Data Analysis : 
      - Creating visualizations for data understanding
      - Deriving statistics from the data

#### Data Preparation for Modeling : 
       - Engineering New Columns

       - Splitting and pre-processing the Data

#### Modeling and Evaluation : 
       - Creating multiple models including Logistic Regression, Decision Trees Classifier, Random Forest, and XGBoost

       - Performed feature importance to the model to extract the key contributory factors




## Findings
 1. Logistic Regression has an accuracy score of 76%
 2. Decision Tree has an accuracy score of 70%
 3. Tuned Decision Tree has an accuracy score of 80%
 4. Random Forest Classifier has an accuracy score of 76%
 5. XGBoost has an accuracy score of 79%

Main features are : Driver Action, Secondary contributary cause(Environmental, Driver Action) and Driver Vision(Obstruction)



## Repository Guide
#### Notebook
The final notebook can be found [here](https://github.com/joakimTI/GROUP-5-PROJECT/blob/main/index.ipynb)

#### Presentation
The presentation can be found in .pdf format [presentation](https://github.com/joakimTI/GROUP-5-PROJECT/blob/main/Presentation.pdf)


## Team Members
[Joakim Tipape](https://github.com/joakimTI)

[Brian Ouko](https://github.com/WellBrian)

[Hanan Dayah](https://github.com/Hanan-Dayah)

[Dorothy Chomba](https://github.com/Messagefordorothy)

[Alex Kaswii](https://github.com/Alexkaswii)

[Zenah Biwott](https://github.com/Biwott54)



