# UpGrad Case Study | Bike Sharing Assignement | Multiple Linear Regression
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* 1. Reading and understanding the data:
* (a) Import data using pandas and other Libraries and reading the data
* (b) Understanding data structure - veiw columns
* (c) Check the dataset for anomolies - Check all the statistics and data types of the data
* (d) Fix data types, missing values or impute
* (e) Visualize the data - numerical and categorical data
* 2. Data Preparation:
* (a) Create dummy variables and binary numbers
* (b) Split the data into trainning and set
* (c) Re-scale the variables
* 3. Train the model:
* (a) Use RFE to check the top 10 variables
* (b) Use manual and business understanding to check other variables also.
4. Residual Analysis:
* (a) Plot residual errors
5. Predicting on test set and evaluating the model test set:
* (a) Use same variables to test the test set
* (b) Using R2 compare the r-score
* [General Info](#general-information)
> 
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Fall has the highest median, which is expected as weather conditions are most optimal to ride bike followed by summer.
- Median bike rents are increasing year on as year 2019 has a higher median then 2018, it might be due the fact that bike rentals are getting popular and people are becoming more aware about environment.
- Overall spread in the month plot is reflection of season plot as fall months have higher median.
- People rent more on non-holidays compared to holidays, so reason might be they prefer to spend time with family and use personal vehicle instead of bike rentals
- Overall median across all days is same but spread for Saturday and Wednesday is bigger may be evident that those who have plans for Saturday might not rent bikes as it a non-working day.
- Working and non-working days have almost the same median although spread is bigger for non-working days as people might have plans and do not want to rent bikes because of that
- Clear weather is most optimal for bike renting, as temperate is optimal, humidity is less, and temperature is less
- The following are the top 3 features contributing significantly towards explaining the demand of the shared bikes:
- Temp – 0.5527
- Year 2019 - 0.2332
- Cloudy – 1.49
- Based on equation derived from analysis
- y=0.1209+0.5527×temp−0.1552×windspeed+0.2332×Year2019+0.0894×summer+1.48×cloudy+0.1281×winter+0.0978×sept−0.2785×light−rain

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.20.3
- pandas - version 1.3.4
- matplotlib - version 3.4.3
- plotly - version 5.6.0
- seaborn - version 0.11.2
- statsmodels - version 0.12.2
- sklearn - version 0.24.2
- scipy - version 1.7.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by UpGrad team
- References if any...
- This project was based on assignment given by UpGrad [this tutorial](https://www.example.com).


## Contact
Created by Vishal [india.vishal.arora@gmail.com] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->