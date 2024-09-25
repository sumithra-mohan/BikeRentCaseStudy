
# Bike-Renting-Prediction
> Build model using Linear Regression to understand the features which impact the bike rental orders.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

Steps Involved

Data Wrangling
Exploratory Data Analysis
Train test split of data
Dummy variables for categorical features with more than 2 type of categories
Scaling of numeric data using Min Max Scaler
RFE with top 10 features to build the model
Analyse the summary using stas module
Remove features with high p value / high VIF values
rebuild the model for new set of features
Residual analysis to validate assumption of Normal distribution of residuals
Validate model with test data using R2 finder

## Conclusions
- Both train and test data model match with R2 score of 80% (0.8018522851400387)
- Temperature , Humidity and Season are the features which impact the demand as they have higher co-efficients in the final model


<!-- You don't have to include all sections - just the one's relevant to your project -->
