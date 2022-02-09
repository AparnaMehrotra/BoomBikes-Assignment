# Boom Bikes Sharing Assignment
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to ongoin Covid-19 pandaemic. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends in the American market. The company wants to know:

> Which variables are significant in predicting the demand for shared bikes?
> How well those variables describe the bike demands?
> We are required to model the demand for shared bikes with the available independent variables. It will be used by the business to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
> We have developed this case study as part of the Linear Regression Module for the Executive PG Programme in Machine Learning & AI - IIIT,Bangalore.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends in the American market. The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands
- We have used day.csv as dataframe

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The top 3 features contributing significantly towards explaining the demand of shared bikes are-

	- temp with the coefficient of 0.5499
	- weathersit_Light Snow/Rain (weathersit = 3) with the coefficient of -0.2880
	- year (yr) with a coefficient of 0.2331
- Interpretation and Suggestions-
	- Demand is more during Summer months(higher temperature) and clear weather conditions. So, we can do more promotions during this period.
	- The demand has significantly increased in the year 2019 as compared to 2018 as people must have become more aware towards conserving environment and shared bikes rentals is one of the ways to conserve it.
	- During spring, and light snow/rain/misty weather conditions the demand goes down as we can see that there is a negative correlation with these variables. Business can provide some offers and discounts during this time to increase the demand.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas library - version 1.3.5
- numpy library - version 1.20.1
- matplotlib library - version 3.3.4
- seaborn library - version 0.11.1
- statsmodels - version 0.12.2
- sklearn - version 0.24.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was based on Linear Regression Module for the Executive PG Programme in Machine Learning & AI - IIIT,Bangalore.


## Contributors
- <a href="https://github.com/AparnaMehrotra/">Aparna Mehrotra</a>


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
