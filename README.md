# Proverty Data Project

## Objective
- Find features that impact Poverty level for different counties
- Predict poverty levels for counties across the United States based on given features
## Data Cleaning
- For variables that contained less than 5% missing values, the observation that contained the missing value was dropped.
- For variables that contained more than 5% missing values, but less than 20%, the missing values were calculated based on the median.
- If a variable contained more than 20% missing data, then the variable was dropped.
## Exploratory Data Analysis 

![alt text](https://github.com/neelgandhi26/Poverty-Data-Project/blob/master/barplot1.PNG)

![alt text](https://github.com/neelgandhi26/Poverty-Data-Project/blob/master/barplot2.PNG)

![alt text](https://github.com/neelgandhi26/Poverty-Data-Project/blob/master/barplot3.PNG)

![alt text](https://github.com/neelgandhi26/Poverty-Data-Project/blob/master/scatterplot1.PNG)

![alt text](https://github.com/neelgandhi26/Poverty-Data-Project/blob/master/scatterplot2.PNG)

![alt text](https://github.com/neelgandhi26/Poverty-Data-Project/blob/master/scatterplot3.PNG)

![alt text](https://github.com/neelgandhi26/Poverty-Data-Project/blob/master/scatterplot4.PNG)

![alt text](https://github.com/neelgandhi26/Poverty-Data-Project/blob/master/scatterplot5.PNG)

![alt text](https://github.com/neelgandhi26/Poverty-Data-Project/blob/master/scatterplot6.PNG)

## Model Building
First, categorical variables were converted to numerical variables by dummy encoding. Next, the data was split into train/test set with a 75/25 split.

Models Used:
- Linear Regression
- Ridge Regression
- Support Vector Machine
- Decision Tree
- Random Forest
- Gradiant Boosting 
## Model Performance
### Linear Regression
- Mean Absolute Error: 2.35
### Ridge Regression
- Mean Absolute Error: 2.34
### Support Vector Machine
- Mean Absolute Error: 1.78
### Decision Tree
- Mean Absolute Error: 2.75
### Random Forest
- Mean Absolute Error: 2.08
### Gradiant Boosting Regressor
- Mean Absoulte Error: 1.86
## Feature Importance
![alt text](https://github.com/neelgandhi26/Poverty-Data-Project/blob/master/feature_importance.PNG)
