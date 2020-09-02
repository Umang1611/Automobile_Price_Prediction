# Automobile old cars Price Prediction
Huge demand of used cars in the Indian Market today.  While new car sales were recorded at 3.6 million units, around 4 million second-hand cars were bought and sold. There is a slowdown in new car sales and that could mean that the demand is shifting towards the pre-owned market. In fact, some car sellers replace their old cars with pre-owned cars instead of buying new ones.  The goal of the case is as follows:  • Perform EDA  • Check for multicollinearity  Predict the price of old cars

## Notebook has following sections:

1- Data understanding and exploration

2- Data cleaning

3- Data preparation: Feature Engineering and Scaling

4- Feature Selection for Model Building

5- Linear Regression Assumptions Validation and Outlier Removal

6- Removing Multicollinearity, Model Re-evaluation and Assumptions Validation

## EDA steps done:

* Removing duplicates
* Missing value treatment
* Outlier Treatment
* Normalizing and Scaling( Numerical Variables)
* Encoding Categorical variables( Dummy Variables)
* Bivariate Analysis

## Data Cleaning
Impute missing values we use mean imputer.

## Data Preparation: feature engineering
Mean encoding for categorical variable can be done in a different form as well...thats taking reference of your dependent variable

## Model Building
Since our dependent variable price looks to be linearly related to most of the independent variables we are using Linear Regression only and not other types of regression like Polynomial, Random Forest/Boosting regression etc
