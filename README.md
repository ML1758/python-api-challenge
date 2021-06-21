# python-api-challenge

python-api-challenge Assignment - Milinda 'ML' Liyanage


## Summary

* This program is done in two steps.
* Getting the set cities and then mapping them on Google maps 

### The following steps were done in the first stage: 

* Create a random set of latitude and longitude coordinates. 
* Read the nearest city for each combination
* Using the city list, obtain the weather making an API call to the open weather map.
* Skip If there are no weather information for a particular city. Target is to get just over 500 
* The read data is then converted into a data frame
* Save the data on to csv file
* To do a statical analysis the data is cleaned by removing  any outliers
* Few scatter plots are done with latitude and other values such as humidity, maximum temperature, cloudiness & wind speed.


## Analysiss of the Data
* By looking at the scatter plot the maximum temperature rises as the latitude get to 0, i.e., close to the equator. This also can be confirmed by looking at the linear regression, where the northern hemisphere’s r value is at -0.67 and the southern hemisphere’s r value is at 0.7.
As both values are close to -1 and 1 respectively, we can conclude that there is a negative correlation between maximum temperature and latitude for the northern hemisphere and a positive  correlation between maximum temperature and latitude for the southern hemisphere.

* It can be seen that there is no significant relationship between the latitude and the humidity. This can be confirmed due to the r values for both, north and south hemispheres are close to 0.

* The wind speed for almost all cities selected are between 0 and 15 kmph. There are a few outliners, but they are also close to upper range. The r values for north and south hemisphere are close 0.1, therefore, it can be concluded that from the selected cities there are no windy cities.


### The following steps were done in the second stage: 

* Read previosly saved csv file in a data frame.
Usung google mapsCreate a random set of latitude and longitude coordinates. 
* Read the nearest city for each combination
* Using the city list, obtain the weather making an API call to the open weather map.
* Skip If there are no weather information for a particular city. Target is to get just over 500 
* The read data is then converted into a data frame
* Save the data on to csv file
* To do a statical analysis the data is cleaned by removing  any outliers
* Few scatter plots are done with latitude and other values such as humidity, maximum temperature, cloudiness & wind speed.
