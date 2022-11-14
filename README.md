# New Jersey Real Estate Prediction Model with Advanced Statistics 

## T-test / Z-test
We want to use the t-tests and z-tests to see if the sample means differ among the categorical variables we are testing. This will help us tell if a categorical variable will be useful as an explanatory variable in the regression- if the means of assessed price between two dummy variables are the same, it likely has no impact on assessed value.
## Anova
We want to use single-factor ANOVA to see if the sample means differ among the categorical variables with more than two categories. This test will be used for the same purpose as the t- and z-tests, but will be applied to the Home Style variable
## Chi-Square Test 
We want to use the Chi-Square Test for Independence to see if assessed value is dependent on our categorical variables. In order to do so, we converted assessed value into a categorical variable that categorized the assessed value of homes depending on if their assessed value was above or below the mean. We then applied the test to each categorical variable to see if assessed value would be affected.
## Regression Model 
A total of 362 observations have been collected about house pricing in New Jersey. We worked on this data as it follows:
1. Determine the correlation between variables 
2. Use regression analysis to make predictions for assessed value for given values such as lot size, number of bathrooms, room, etc.
3. Use various goodness-of fit-measures to determine the regression model that best fiits the data. 
## Logistic Model 
This case differs from the linear, quadratic, and logarithmic models because we are going to predict a probability that a house has a certain characteristic.
A total of 362 observations have been collected about house pricing in New Jersey. We are going to use this data to create several models:
1. Use the independent variables of lot size, bathrooms, total rooms, and basement to determine the probability of assessed value being above or below the mean.
2. Use assessed value and taxes to predict the likelihood of a home containing a garage.
3. Use assessed value and taxes to predict the likelihood of a home containing a basement.
