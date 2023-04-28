# BIKE SHARE DEMAND PREDICTION

## Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes. 

![Smmove-bike-dock](https://user-images.githubusercontent.com/123857050/235152003-0196dad3-b770-4adb-b81c-36b30e4b37a1.png)
## About dataset:
### This dataset contain information about rental bike . this dataset contain 8760 rows and 14 columns.
# Dataset
### - Date : year-month-day
### - Rented Bike count - Count of bikes rented at each hour
### - Hour - Hour of he day
### - Temperature-Temperature in Celsius
### - Humidity - %
### - Windspeed - m/s
### - Visibility - 10m
### - Dew point temperature - Celsius
### - Solar radiation - MJ/m2
### - Rainfall - mm
### - Snowfall - cm
### - Seasons - Winter, Spring, Summer, Autumn
### - Holiday - Holiday/No holiday
### - Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

# Library Used
### - Pandas : For loading the dataset and performing data wrangling
### - NumPy : For performing data wrangling and math operation 
### - Calendar : To convert month number to month name
### - Matplotlib : For data visualization.
### - Scipy(kda) : For data visualization. 
### - Seaborn : For data visualization.
### - Missingno : For Num Values visualization. 
### - Sklearn : For Machine Learning Models.
### - Statsmodels : For variance inflation factor

# Steps involved
### - Installing libraies and getting the dataset.
### - Performing EDA (exploratory data analysis).
### - Drawing conclusions from the data.
### - Using Transformation 
### - Preprocessing the data.
### - Feature Engineering
### - Handling Multicollinearity
### - Lable Encoding for categorical data 
### - HYPERPARAMETER TUNING
### - Training different models.
### - Feature Importances
### - Evaluating metrics of all the models.
![image](https://user-images.githubusercontent.com/123857050/235155198-6c26c45c-c3ca-4d42-ae8e-0f935014baff.png)
 
# Algorithms used
### 1)LinearRegression
### 2)random forest
### 3)Lasso regression
### 4)Ridge regression
### 5)Elasticnet regression
### 6)Support Vector Regression
### 7) Bayesian regression
### 8)Dicision Tree regression
### 9)Random Forest regression
### 10)Extra-Trees regression

# Conclusion

### * From above its clear that extra-tree regression model is the best model for this dataset.
### * Elasticnet regularization performed very poorly.
### * Random forest model also gives better results compared to other models
### * random forest and extra-trees model gives less random mean squer error compare to other models.
