
# Bike Sharing:

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic and quarantine situation across the nation. Because of which company contracted a consulting company to understand the factors on which the demand for these shared bikes depends

The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands


## Business Goal:

We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features.

## Dataset Information

The dataset contains 730 rows and 16 columns.
- Link:  [Dataset](https://drive.google.com/drive/folders/16qA8CbXUJ2Xc5J5mOpF9VaUMRwAhYAPt?usp=sharing)


### Data Preparation:
1.	In the dataset some of the variables like 'weathersit' and 'season' have values as 1, 2, 3, 4 which have specific labels associated with them (as can be seen in the data dictionary). These numeric values associated with the labels may indicate that there is some order to them - which is actually not the case (Check the data dictionary and think why). So, it is advisable to convert such feature values into categorical string values before proceeding with model building. Please refer the data dictionary to get a better understanding of all the independent variables.
 
2.	The column 'yr' with two values 0 and 1 indicating the years 2018 and 2019 respectively. At the first instinct, you might think it is a good idea to drop this column as it only has two values so it might not be a value-add to the model. But in reality, since these bike-sharing systems are slowly gaining popularity, the demand for these bikes is increasing every year proving that the column 'yr' might be a good variable for prediction. So think twice before dropping it. 
 Finally, the 'cnt' variable indicates the total number of bike rentals, including both casual and registered. The model should be built taking this 'cnt' as the target variable.

## Result
1.	Build the Linear Regression Model for the given dataset and got the following result:
#### Train Data Set
- R-squared:                       0.824
- Adj. R-squared:                  0.820
#### Test Data Set
- R-squared:                       0.8093
- Adj. R-squared:                  0.8001
#### It can be observed that demand for bikes depends mainly on below variables:
#### yr, holiday, temp, Winter, spring, summer, Light_snow_rain, Mist_cloudy, July, Sept
- Demand increases with the year, temp
- Demand increases in winter,summer and in the month of Sept
- Demand decreases if it is holiday , Spring, Light Snow_Light Rain + Thunderstorm + Scattered clouds, Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist and in the month of July




## Software and Libraries

[Python 2.7 or Higher](https://www.python.org/downloads/)

[Numpy](https://pypi.org/project/numpy/)

[Matplotlib](https://pypi.org/project/matplotlib/)

[Pandas](https://pypi.org/project/pandas/)

[Jupyter Notebook](https://jupyter.org/install)

[Seaborn](https://pypi.org/project/seaborn/)

[Scikit-learn](https://pypi.org/project/sklearn/)

