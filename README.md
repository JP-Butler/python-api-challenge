# Carelton Data Analytics Boot Camp
# Module-6 Python-API-Challenge
-------------------------------------------------

![EARTH.](https://1drv.ms/i/s!AquoX1sNxzjsqTxdcdCMdKQOfz3S?e=N9PICR)
(Image credit: Thamrongpat Theerathammakorn / EyeEm via Getty Images)

This challenge puts to use the concepts learned in the sixth week of our Data Boot Camp such as Python requests, API's, JSON traversals and some new Python libraries such as citipy and geoViews. Using this new knowledge along with the OpenWeather and Geoapify API's we put the question "What is the weather like as we approach the equator?" to the test and how can we use data to answer it.


## Table of Contents

- [About](#about)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## About
This challenge is broken down into two parts. In Part 1 - WeatherPy the citypy Python Library was used in conjunction with the OpenWeatherMap API to make a request for at minimum 500 cities of varying distances from the equator for analysis. Using the JSON formatted response, certain data was extracted such as latitude, longitude, temperature, humidity, cloudiness and wind speed. Subsequent scatter plots, line regression plots and written analysis were made comparing this retrieved data. For instance:
* Latitude vs. Temperature
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed
Two line regression plots were made for each of the above comparisons as well. One for the cities found in the northern hemisphere and the other for the cities in the southern hemisphere.
Part 2 - VacationPy builds on top of part 1 by importing the "cities.csv" file that stores the data retrieved from the API request in Part 1 and the city_data_df DataFrame created from it to create more complex map visualizations with the hvplot.pandas plotting API. Two map visualizations were created, the first with a point for all the cities in the data with the size of the point representing the humidity% of the city. The second was given some additional parameters to display an "ideal vacation spot" such as preferred temperature, humidity, cloudiness and the nearest hotel within 10000 meters. With all listed information in a convenient hover message above the point of the city.

## Installation
Scripts written entirely in Python(version 3 or higher needed). Python Dev environment needed in Jupyter Notebook (recommended) to run files.
Necessary Python Libraries:
* pandas
* matplotlib
* numpy
* hvplot
* geoviews
* citypy
* scipy

## Usage
The cities retrieved for the data in Part 1 was acquired using the numpy random number generator "np.random". Found in the second cell of the WeatherPy file. Meaning the cities generated and subsequent plots in the remainder of the project will differ each time the code is ran. Therefore the intial output found when first accessing the file will change once the code is tested. 
Please contact contributor at bottom of page if issues arise.

## Contributing

Justin Butler, GitHub (JP-Butler) [My GitHub Profile](https://github.com/JP-Butler)