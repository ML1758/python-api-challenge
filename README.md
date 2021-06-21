# python-api-challenge

python-api-challenge Assignment - Milinda 'ML' Liyanage


## Summary

* This program is done in two stages.
* Getting a set of cities, doing some statistical analysis, and then mapping a selected set of cities on Google maps 

### The following steps were done in the first stage: 

* Create a random set of latitude and longitude coordinates. 
* Read the nearest city for each latitude and longitude combination
* Using the city list, obtain the weather by making an API call to the open weather map.
* Skip if there are no weather information for a particular city. Target is to get just over 500 cities
* The read data is then converted into a data frame
* Save the data on to csv file
* To do some statical analysis the data is cleaned by removing  any outliers
* Few scatter plots were done with latitude and other variables such as humidity, maximum temperature, cloudiness & wind speed.


### Analysis of the Data
* By looking at the scatter plot the maximum temperature rises as the latitude get to 0, i.e., close to the equator. This also can be confirmed by looking at the linear regression, where the northern hemisphere’s r value is at -0.67 and the southern hemisphere’s r value is at 0.7.
As both values are close to -1 and 1 respectively, we can conclude that there is a negative correlation between maximum temperature and latitude for the northern hemisphere and a positive  correlation between maximum temperature and latitude for the southern hemisphere.

* It can be seen that there is no significant relationship between the latitude and the humidity. This can be confirmed due to the r values for both, north and south hemispheres are close to 0.

* The wind speed for almost all cities selected are between 0 and 15 kmph. There are a few outliners, but they are also close to upper range. The r values for north and south hemisphere are close 0.1, therefore, it can be concluded that from the selected cities there are no windy cities.


### In the second stage the following steps were done: 

* Reading the previously saved csv file into a data frame. 
* Map the cities using humidity as the heat map.
* Reduce the cities by a set of conditions
* Getting a set of hotels within a 5k radius and overlaying on a humidity heat map.
* Markers were also shown with the hotel name, city, and country.


