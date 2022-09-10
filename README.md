# Boombikes-LinearRegression-Assignment
> Linear Regression performed on the Boombikes bike dataset as part of assignment, which includes detailed Analysis along with conclusions to make bike renting more profitable.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Multiple linear regression is performed on the dataset.
- The project is done as part of assignment in the Machine Learning module.
- We are trying to find the number of rentals issued from the company based on numerous independent values such as temperature, weather, humidity, holiday, etc.
- The Boombikes dataset is being used.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The R-Squared value for train set is 82% whereas for test set has a value of 81%, suggesting that our model is able to explain the variance quite accurately on the test set and thus we can conclude that it is a good model.

Developed model's mean squared error is almost 0 on both the training and testing datasets, suggesting that the variance is accurately predicted on the test set. The p-values and VIF were used to select the significant variables. Utilized RFE for automated selection of variables.

We can observe that there are few variables with negative coefficients, A negative coefficient suggests that as the independent variable increases, the dependent variable tends to decrease. We have spring, mist cloudy , light snow variables with negative coefficient. The coefficient value signifies how much the mean of the dependent variable changes given a one-unit shift in the independent variable while holding the other variables in the model constant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
pandas
seaborn
matplotlib
statsmodels
sci-kit learn
numpy

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project is my first one on Linear Regression. I'd like to thank the mentor, Siddesh Gunjal.

## Contact
Created by [@pramodkhandare] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->