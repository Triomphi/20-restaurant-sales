# Restaurant Revenue Prediction
*Predict annual restaurant sales based on objective measurements*

**Data Description**

TFI has provided a dataset with 137 restaurants in the training set, and a test set of 100000 restaurants. The data columns include the open date, location, city type, and three categories of obfuscated data: Demographic data, Real estate data, and Commercial data. The revenue column indicates a (transformed) revenue of the restaurant in a given year and is the target of predictive analysis. 

**Data  fieds**

**Id :** Restaurant id. 

**Open Date :** opening date for a restaurant

**City :** City that the restaurant is in. Note that there are unicode in the names. 

**City Group:** Type of the city. Big cities, or Other. 

**Type:** Type of the restaurant. FC: Food Court, IL: Inline, DT: Drive Thru, MB: Mobile

**P1, P2 - P37:** There are three categories of these obfuscated data. Demographic data are gathered from third party providers with GIS systems. These include population in any given area, age and gender distribution, development scales. Real estate data mainly relate to the m2 of the location, front facade of the location, car park availability. Commercial data mainly include the existence of points of interest including schools, banks, other QSR operators.

**Revenue:** The revenue column indicates a (transformed) revenue of the restaurant in a given year and is the target of predictive analysis. Please note that the values are transformed so they don't mean real dollar values. 


[Here is a link to the dataset](https://www.kaggle.com/c/restaurant-revenue-prediction/data?select=test.csv.zip)
