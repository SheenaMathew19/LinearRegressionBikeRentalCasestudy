# Project Name: Bike-Sharing-Linear Regression-Case Study

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)


## General Information

### Project Background

> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario.In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits. 

### The business is curious about:

What factors are important for forecasting the demand for shared bikes.
How well those parameters capture what the bike needs

### Project Statement

> Create a model using the independent variables that are available to determine the factors that are important to the demand for shared bikes.
The management will utilise it to comprehend and adjust the business plan in order to fulfil demand levels and client expectations.


### Data Set

> The data is a CSV which contains information about daily bike demand for the entire American market based on weather surveys and societal trends.

## Conclusions

> Below three features are the most influential features for Bike Rentals:
- Temperature: with coefficient 0.5499
- Year:  with coefficient 0.2331
- Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds: with negative coefficient -0.2880
 
> best fitted line Linear Equation for Bike Rental is
cnt =0.0753 + 0.5499 * temp + 0.2331 * yr + 0.1318 * winter + 0.0972 * September + 0.0874 * summer + 0.0677 * Saturday + 0.0563 * workingday - 0.0813 * (Misty+Cloudy) - 0.1552 * windspeed - 0.2880 * (Light Snow/Rain)

> R squared value of both Training and test data set
- Train dataset R^2 : 0.836
- Test dataset R^2 : 0.7956
 

## Technologies Used

- Pandas 
- Seaborn 
- MatplotLib 
- Missingno

## Acknowledgements

This project was done as part of Case study for UpGrad IITB Programme on Artifical Inteligince and Machine Learning.