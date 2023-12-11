# Project Name
> Bike Sharing system 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Using techniques learnt in EDA and Liner regression module need to come out with analysis and identify attributes which are having influence on the bike rentals.
Also need to come out with a prediction model for finding demand for shared bikes.</br>
What are the independent variables present in the given data set and its impact on the bike rentals to be derived.
By having all these details, it will be helpful for the bike rental management team on predicting the bike rentals and be prepared for effective business

## Conclusions
- Here are the observations from above univariate analysis of categorical data 
	* We have more number of days whether weather was clear 
	* When compared with working days data, majority of them are for working days 
	* Data with Holidays is less 
- Here are the observations from above Bivariate analysis for categorical columns
	* In Summer and Fall seasons good amount of rentals are there when compared with other two seasons 
	* In Y2019 there are more number of rentals 
	* During April to October months there are more number of rentals 
	* When weather is Clear, there are more number of rentals 
- Here are the observations from above Univariate analysis for numerical columns
	* On Windspeed, good amount of data distributed between greater than 5 and less than 20 
	* On humidity, good amount of data distributed between greater than 40 and less than 90 
	* On temp and atemp data, around 10 to 30 its distributed. 
- Here is the equation based on the final model where R-squared value is 0.838, with p-values for all variables/features is less than 0.05 along with VIF of them is less than 5. <br><br><br>
	cnt = 0.2893 + temp * 0.4026 - windspeed * 0.1540 - season_Spring * 0.1034 + season_Winter * 0.0650 + yr_2019 * 0.2348 - mnth_Dec * 0.0510 - mnth_Jan * 0.0556 - mnth_Jul * 0.0643 - mnth_Nov * 0.0488 + mnth_Sep * 0.0537 - holiday_Yes * 0.0913 - weathersit_Light_Snow * 0.2949 - weathersit_Mist_Cloudy * 0.0812


## Technologies Used

- Python - version 3.11.4
- Pandas - version 1.5.3
- Numpy - version 1.24.3
- Seaborn - version 0.12.2
- Matplotlib - version 3.7.1
- sklearn - version 1.3.0
- statsmodels - version 0.14.0


## Acknowledgements
As part of UpGrad course, casestudy on "Bike Sharing system" was taken up and applied the learnings we had from EDA module and Liner regression module.


## Contact
Created by @Aswani-ReddyKV - feel free to contact!
