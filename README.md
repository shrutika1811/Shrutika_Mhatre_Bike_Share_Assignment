# Bike Sharing Assignment
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- General information about project :
	A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
	
- Background of the project :
	1->A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
	2->In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
	3->They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
	4->Which variables are significant in predicting the demand for shared bikes.
	5->How well those variables describe the bike demands
	6->Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 
	
- The business probem that this project is trying to solve :
	1->We are required to model the demand for shared bikes with the available independent variables.
	2->It will be used by the management to understand how exactly the demands vary with different features.
	3->They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.
	4->Further, the model will be a good way for management to understand the demand dynamics of a new market. 
	
- The dataset that is being used :
1->We have been provided with day.csv dataset that contails following columns:
- dteday
- season
- yr
- mnth
- holiday
- weekday
- workingday
- weathersit
- temp
- atemp
- hum
- windspeed
- casual
- registered
- cnt

2->We have also been provided with the dictionary test file that contains the meaning of above columns
	


## Conclusions
- 1)Year 2019 saw a steep increase in the number og bike rents from almost 3300 in 2018 to 5700 in 2019.
- 2)Most bikes are rented in the month of May to October. May to October month covers most of the summer and fall seasons in USA. Thus this impact can be easily seen in season barplot as well, as there is significant count of bike rentals in summer and fall season as compared to winter and spring.
- 3)It can be seen that people usually prefer to rent bikes while the weather is clear.
- 4)Little misty weather makes the preferrances for bike rental a little less, whereas even a light snow discourages people for bile rental.
- 5)Thus the sales of BoomBikes on clear days, thus BoomBikes should have a close check on wether forecast and thus keep the availability of bikes for such days so that customers won't face any issues.
- 6)Also it is seen that count of BoomBikes has seen increase in fall season.
- 7)Thus BoomBikes can surely plan for more and more advertisements from summer season itself such that by fall season BoomBikes can reach maximum target audience and increase the chances on improving the business.



## Technologies Used
- pandas
- numpy
- seaborn
- matplotlib.pyplot
- statsmodels.api
- sklearn.preprocessing
- MinMaxScaler
- sklearn.model_selection
- train_test_split
- sklearn.feature_selection 
- RFE
- sklearn.linear_model
- LinearRegression



## Contact
Created by [@shrutika1811] - feel free to contact me!
