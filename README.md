# Project Name
===============

BoomBikes: We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
======================

BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demand

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
===============

Equation of our best fitted line is:

count=0.4914×temp+0.0916×September+0.0645×Saturday+0.0527×summer+0.0970×winter+0.2334×Year+0.0566×workingday−0.03041×lightsnow−0.0786×mistcloudy−0.0650×spring

Final Result Comparison between Train model and Test:
- Train R^2 : 0.826
- Train Adjusted R^2 : 0.82
- Test R^2: 0.8115
- Test Adjusted R^2: 0.790564
- Difference in R^2 between train and test: 1.5%
- Difference in adjusted R^2 between Train and test: 3.15% which is less than 5%

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

Name: numpy; Version: 1.26.4
Name: pandas; Version: 2.2.2
Name: seaborn; Version: 0.13.2
Name: matplotlib; Version: 3.9.2
Name: statsmodels; Version:0.14.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements


## Contact
Created by [@Chaituz] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->