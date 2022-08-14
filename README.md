# propertypriceregression
> Building a Multiple Linear Regression model for property price company to predict. Company is having sale of houses data from australia.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- In this project, we are trying to build a MLR model to prediict price of a property for a US based company which has decided to enter Autralian Market, 
- We are using RFE to find the top 570 variable and then will apply ridge & lasso model to find the optimal values of alpha, coef and features
- Data set contain sale of houses in Australia which has more than 80 attributes in file

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 Lasso Regression is final model
- Conclusion 2 R2_score for train data is 88.28%
- Conclusion 3 R2_score for test data is 84.37%
- Conclusion 4 Top features : YrSold_Old, BsmtHalfBath, BedroomAbvGr, BsmtQual, Somerst
- Conclusion 5 R2_score is decreasing with increase in alpha values

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

- Pandas - version 	 1.0.5
- Numpy - version 	 1.18.5
- Matplotlib - version 	 3.2.2
- Seaborn - version 	 0.10.1
- Sklearn - version 	 0.23.1


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements


## Contact
Created by [@sanngh] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->