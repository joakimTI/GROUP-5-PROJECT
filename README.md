# PREDICTING PRIMARY CONTRIBUTORY CAUSES OF CRASHES IN CHICAGO
![cars](https://github.com/user-attachments/assets/e288361c-7ced-4d8d-b649-4471d2da5027)

## Problem Statement
In big cities, traffic safety is of paramount importance because of its significant impact on human lives and city resources. This project leverages data science techniques to analyze and predict vehicle crashes in Chicago using datasets from the city of Chicago, Driver and Passanger, and Vehicles. By understanding the major factors contributing to accidents, we can develop a predictive model that can identify the likelihood of crashes in Chicago. The model will aim to provide insights into the factors contributing to crashes, enabling authorities to take proactive measures to reduce the number of accidents and improve road safety.

### Aim
Our primary objectives are to:

1. Identify the most significant contributing factors to road accidents in Chicago.
2. Provide insights into patterns and trends to help stakeholders implement targeted interventions to reduce road accidents.
3. Develop a Model based on metrics that address the predictors for road accidents the best.


## Data
The Crash data shows information about each traffic crash on city streets within the City of Chicago limits and under the jurisdiction of Chicago Police Department (CPD). It can be found in [Crashes](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if/about_data) and contains 48 columns with over 880K rows. 

Vehicles dataset in [Vehicles](https://data.cityofchicago.org/Transportation/Traffic-Crashes-Vehicles/68nd-jvt3/about_data) contains information about vehicles (or units as they are identified in crash reports) involved in a traffic crash. “Vehicle” information includes motor vehicle and non-motor vehicle modes of transportation, such as bicycles and pedestrians. This dataset has 71 columns with over 1.8M rows.

Driver and Passanger dataset in [People](https://data.cityofchicago.org/Transportation/Traffic-Crashes-People/u6pd-qa9d/about_data) contains information about people involved in a crash and if any injuries were sustained. Each record corresponds to an occupant in a vehicle listed in the Crash dataset. It has 29 columns and over 1.94M rows.

For our analysis, we picked relevant columns from each dataset to come up with a model that best fit our business problem.

## Contents
1. Data Understanding
2. Data Cleaning and EDA
3. Data Analysis
4. Data preparation for modelling
5. Modelling and Evaluation
6. Conclusion

#### Data Understanding : 
      - Exploring the raw data set and understanding the values of each column

#### EDA : 
      - Understanding the null values and evaluating the best steps to take to eliminate them

      - Replacing null values with meaningful data 
      
      - Removing irrelevant and redundant columns

#### Data Analysis : 
      - Creating visualizations to better understand the data

      - Deriving statistics from the data

#### Data Preparation for Modelling : 
       - Engineering New Columns

       - Splitting and pre-processing the Data

#### Modelling and Evaluation : 
       - Created multiple models including Logistic Regression, Decision Trees Classifier, Random Forest and XGBoost

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
Presentation can be found from here in .pdf format [presentation](https://github.com/joakimTI/GROUP-5-PROJECT/blob/main/Presentation.pdf)


## Team Members
[Joakim Tipape](https://github.com/joakimTI)

[Brian Ouko](https://github.com/WellBrian)

[Hanan Dayah](https://github.com/Hanan-Dayah)

[Dorothy Chomba](https://github.com/Messagefordorothy)

[Alex Kaswii](https://github.com/Alexkaswii)

[Zenah Biwott](https://github.com/Biwott54)



