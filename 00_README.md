# movie-prediction-revenue

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) focusing on movies from the Full TMDB Movies Dataset 2024. For a detailed walkthrough, please view the source code in order from:

- Data cleaning
- Data Visualization
- Univariate and Multivariate regression
- Random forest regression
- Evaluation

## Contributors
- @Jxredkong
- @shawnchow7
- @ednasx

## Problem Definition

Are we able to predict the revenue for a given movie?

##Models Used

- uni-variate Regression
- Multi-variate Regression
- Random forest Regression

##Conclusion

- Vote_count and budget have high correlation scores with revenue
- Multi-variate regression using categorical variables does not perform well due to the low R2 value 
- Random forest regression does perform well using both numerical and categorical 
- Yes, it is possible to predict a movie's revenue if given the correct model to predict
- The best model is the Random Forest model provides a robust framework for predicting movie revenue with high accuracy and flexibility.

## What did we learn from this project?

- Handling incomplete dataset 
- How to combine both numerical and categorical variables into a regression model by one-hot encoding the categorical variables and then by using a random forest regression.
- RandomForestRegressor from sklearn
- Collaborating using GitHub
