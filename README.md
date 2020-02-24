# Stroke-Prediction-Project

## Problem Defination
Stroke is a major cause of death in the United States every year. With stroke being a common health issue within the United States, it is important to analyze data related to this issue to determine ways to further prevent it from occurring. The dataset that was analyzed focused on a variety of factors and the relationships shared with health-related issues, such as a stroke.

## Discover the Data

The features in the data sets are and test_features are:

+ **Gender**: Male or Female
+ **Age**: Contains age >18+
+ **Race**: Race of the person
+ **Marital Status**: Married or Single
+ **Weight (lbs)**:Weight of a person in pounds
+ **Height (Inches)**: Hegiht in inches 
+ **BMI**: BMI of a person
+ **Condition of Teeth**: Oral Health of a person
+ **Diabetic/Not Diabetic**: Is the person diabatic or non diabetic
+ **Heart Attack**: Suffered from heart attack in the past or not
+ **Cholesterol**: High or Normal

## Exploratory Data Analysis 

### Basic observations

+ The datasets have total **26k** *number of observation*
+ **7** *numerical variables* and **8** *categorical variables*
+ Stroke is our target variable
+ There are no duplicates in the data and there are no values missing in the dataset

### Univariate Analysis

+ The below figure shows the distribution of the categorical variables with target variables
![Target vs Categorical variable](https://github.com/DhruTewa/Stroke-Prediction-Project/blob/master/Images/Categorical_Univariate_Analysis.png)

+ The below figure shows the distribution of the numerical variables
![Numerical variables Distribution](https://github.com/DhruTewa/Stroke-Prediction-Project/blob/master/Images/Numerical_Univariate_Analysis.png)

### Outliers Analysis

We can see some outliers in the cholestrol variable and will check it 
![Outliers Detection](https://github.com/DhruTewa/Stroke-Prediction-Project/blob/master/Images/Outlier%20Analysis.png)


### Bivariate Analysis

+ The below graph shows the distribution of the target varaiable with the numberical varaiables:

![Target vs Numerical variable](https://github.com/DhruTewa/Stroke-Prediction-Project/blob/master/Images/Target%20vs%20Numerical%20variable.png)


### Features correlation

+ There is a **positive correlation** between:
    + weight Vs waist 
    + weight Vs height 
    + BMI Vs weight 
 

![Features_Correlation](https://github.com/DhruTewa/Stroke-Prediction-Project/blob/master/Images/variable_correlation.png)

## Model Developement

We will evaluate algorithms using the accuracy  and f1-score metrics.

For model developement we are selecting three linear models
- Logistics regression(LR)
- DecisionTree
- KNN Classifier
- RandomForestClassifier
- Gaussian NB

The algorithms all use default tuning parameters. By comparing the below table accuracy of Logistic Regression is heighest and hence we will select it as the model for prediction.


![Model Comparision](https://github.com/DhruTewa/Stroke-Prediction-Project/blob/master/Images/Model%20Score.JPG)
