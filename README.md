# python-api-challenge
Module 6 Challenge

We seek to answer the following question: "What is the weather like as we approach
the equator?"

PART 1
Analysis found in: WeatherPy.py

Using weather data from over 500 cities of varying distances from the equator, we are
seeking to create a representative model of weather across cities. Using plots, we will visually demonstrate the relationship between weather variables and latitude.

The weather variables included in the analysis are:
1. Temperature
2. Humidity
3. Cloudiness
4. Wind Speed

Each of the above weather variables will be modelled against latitude and plots
will be displayed for each weather variable. Following this, two plots for each
weather variable will be created - one for Northern Hemisphere data and one for 
Southern Hemisphere data.

PART 2
Analysis found in: VacationPy.py

For the range of cities found in the cities.csv dataset, we will:
1. Present a map that shows both the location of each city and also visually displays
the relative humidity of that city (through size of location marker).
2. Present a dataframe ('city_data_df') that includes only cities whose weather
variables are considered ideal:
    - Maximum temperature of between 15 and 25 degrees celcius.
    - Humidity of 50% or less.
    - Cloudiness of 25% or less.
    - Wind speed of 3 metres per second or less.
3. Present a dataframe ('hotel_df') that, for a range of cities, shows their country,
coordinates and humidity.
4. Find the hotel located nearest to each city (using each city's listed 
coordinates and within 10km of these coordinates) and display in hotel_df dataframe.
This will be done using the Geoapify Places API.
5. Display on a map the location of each of these hotels. Include, in the hover 
message the following: longitude, latitude, city name, humidity, hotel name, country.