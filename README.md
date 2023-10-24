# weather-conditions-analysis

I applied what I've learned about Python APIs to answer questions on countries, cities and weather, by creating a Python script to visualize the weather of over 500 cities of varying distances from the equator to know what is the weather like as we approach the equator. The analysis is broken into two deliverables, WeatherPy and VacationPy

# Data used

* output_data/cities.csv

![Alt text](<Screenshot 2023-10-21 030924.png>)

# VacationPy

* Using the information provided in the output_data/cities.csv file, I created a city map that shows a point on the map for each city listed in the city_data_df DataFrame.

![Alt text](<Screenshot 2023-10-21 031744.png>)

# WeatherPy

* I created plots to showcase the relationship between Weather Variables and Latitude

# Created Scatter Plots Requested
* Latitude Vs. Temperature
![Alt text](<Screenshot 2023-10-21 035741.png>)

* Latitude Vs. Humidity
![Alt text](<Screenshot 2023-10-21 040013.png>)

* Latitude Vs. Cloudiness
![Alt text](<Screenshot 2023-10-21 040212.png>)


* Latitude vs. Wind Speed 
![Alt text](<Screenshot 2023-10-21 040639.png>)

# I Computed Linear Regression for Each Relationship
* Temperature vs. Latitude Linear Regression Plot

* Northern Hemisphere
There is a mid positive correlation between temperature and latitude, with a correlation coefficient of 0.4340881444737878 on Northern Hemisphere.

![Alt text](<Screenshot 2023-10-21 042644.png>)

* Southern Hemisphere
There is a strong positive correlation between temperature and latitude, with a correlation coefficient of 0.7089110991922667 on Southern Hemisphere.

![Alt text](<Screenshot 2023-10-21 042837.png>)
