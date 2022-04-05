# Income-census-Data_Analysis
### Performed EDA and Machine learning model on Income census dataset.

#### Dataset Description:

- The dataset provided included income census data having entries of individuals within the United States mentioning their current occupation along with additional information.

- The target output we tried to achieve through this dataset was to use a Machine Learning model with Microsoft Azure to try and predict the income of individuals ( greater than or less than 50,000$) based on the available datapoints.

- Created a summary of the dataset represented in an excel sheet to have a better understanding of the entries(shared the stats in the repo) 

- Our dataset contains 14 column variables and a total of 32402 observations


- The dataset contains 5 numeric variables and 9 categorical variables


#### Dataset Cleaning: 

- Income census Data Missing Values in the dataset.

   1.Under ‘Native country’ we noted 583 entries where a native country was not mentioned, we choose to classify all these entries under “Other”

   2.Under ‘Occupation’ we noted 1843 entries where the current occupation was not mentioned, and choose to represent these values under “Other”

   3.Under ‘Work class’, it was noted that 1836 entries were not specified.

#### Data Transformation:

We choose to split the individuals within the dataset based on their age groups and created an additional column to represent these values. These age groups include:

  Beginner - 0 to 26
  Experienced - 27 to 40
  Senior Worker - 41 to 59
  Retired 60 and above
 
We also created an additional column for classification of individuals based on education level:

  Schooling - 9 and below
  Undergrad - below 13 
  Postgrad - above 13

#### Modelling:

Performed modelling to predict the income groups based on the feature varibales.

- The Dashboard is publish in Power BI My workspace. To visit the dashboard [click here](https://app.powerbi.com/groups/me/reports/477cd6fd-5b48-4edc-960a-cd4ad90432ff/ReportSection)

