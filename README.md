# Proverty Data Project

## Objective
- Find features that impact Poverty level for different counties
- Predict poverty levels for counties across the United States based on given features
## Data Cleaning
- For variables that contained less than 5% missing values, the observation that contained the missing value was dropped.
- For variables that contained more than 5% missing values, but less than 20%, the missing values were calculated based on the median.
- If a variable contained more than 20% missing data, then the variable was dropped.
## Exploratory Data Analysis 

![alt text](https://github.com/neelgandhi26/Poverty-Data-Project/blob/master/Dashboard%201.png)

![alt text](https://github.com/neelgandhi26/Poverty-Data-Project/blob/master/Dashboard%202.png)

![alt text](https://github.com/neelgandhi26/Poverty-Data-Project/blob/master/Dashboard%203.png)

![alt text](https://github.com/neelgandhi26/Poverty-Data-Project/blob/master/Dashboard%204.png)

![alt text](https://github.com/neelgandhi26/Poverty-Data-Project/blob/master/corr_matrix.png)

## Model Building
First, categorical variables were converted to numerical variables by dummy encoding. Next, the data was split into train/test set with a 80/20 split.

Models Used:
- Linear Regression
- Ridge Regression
- Support Vector Machine
- Decision Tree
- Random Forest
- Gradiant Boosting 
## Model Performance
### Linear Regression
- R-Squared: 77.85%
- Mean Absolute Error: 2.35
### Gradiant Boosting Regressor
- R-Squared: 81.25%
- Mean Absoulte Error: 2.18
