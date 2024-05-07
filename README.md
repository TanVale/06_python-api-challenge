# 06_python-api-challenge

# Part 1: WeatherPy
In this challenge I have - 
Created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I used the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and problem-solving skills to create a representative model of weather across cities.

To get started, the code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination was provided.

Requirement 1: Created Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, I used the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, I created a series of scatter plots to showcase the following relationships:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed

Requirement 2: Computed Linear Regression for Each Relationship
To fulfill the second requirement, I computed the linear regression for each relationship. Separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). 
Next, I created a series of scatter plots -

- Sample scatter plot with the linear regression line.
- Northern Hemisphere: Temperature vs. Latitude
- Southern Hemisphere: Temperature vs. Latitude
- Northern Hemisphere: Humidity vs. Latitude
- Southern Hemisphere: Humidity vs. Latitude
- Northern Hemisphere: Cloudiness vs. Latitude
- Southern Hemisphere: Cloudiness vs. Latitude
- Northern Hemisphere: Wind Speed vs. Latitude
- Southern Hemisphere: Wind Speed vs. Latitude

# Part 2: VacationPy

In this deliverable, I used my weather data skills to plan future vacations. Also, I used Jupyter notebooks, the geoViews Python library, and the Geoapify API.
The main tasks were to use the Geoapify API and the geoViews Python library and employ my Python skills to create map visualizations.

I completed the following steps:

Created a map that displays a point for every city in the city_data_df DataFrame. The size of the point is the humidity in each city.
Humidity map
Narrowed down the city_data_df DataFrame to find the ideal weather condition. For example:
A max temperature lower than 27 degrees but higher than 21
Wind speed less than 4.5 m/s
Zero cloudiness




