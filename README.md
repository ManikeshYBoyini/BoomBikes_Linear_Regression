# Boombikes-LinearRegression-Assignment 
> Linear Regression performed on the Boombikes bike rental dataset as part of an assignment for coursework in the course Executive PG in Machine Learning and AI from IIIT Bangalore. 


## Table of Contents
1. Problem statement 
2. Business goal 
3. Steps to be followed in this exercise
4. Data visualization
5. Train test split
6. Model building
7. Residual Analysis
8. Testing modal
9. Conclusions

<!-- You can include any other section that is pertinent to your problem -->

## Business Goal of the Assignment:

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Conclusions
- Since bookings tend to increase on warmer, good-weather days, the company should focus on increasing bike availability and running promotions during the summer months to boost bookings further.

- An R-squared value of 0.82 on the test data indicates that the model is a strong predictor, capturing 82% of the variance. This accuracy could be further improved by exploring other regression techniques, such 
   as Random Forest.
- Our developed model's mean squared error is almost 0 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set. The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.

- The major steps included in the python notebook are data interpretation, data visualisation, data pre-processing, model training, feature selection, residual analysis, model evaluation on the test set. 

- Concepts such as EDA, p-value, VIF were used and model building was done using statsmodels library

## Technologies Used
- pandas
- seaborn
- matplotlib
- statsmodels
- sci-kit learn
- numpy

