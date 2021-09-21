# python-api-challenge
Week 6 Python API Homework

WeatherPy.ipynb was coded to gather a list of over 500 random cities weather information.

The data was then visualized in scatter plots based on:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

After each plot there is a brief analysis.

Then linear regression was run and visualized in scatter plots on each of the following:
* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots there is a brief analysis.

Each figure was saved into images as a .png and the weather data frame was exported into output_data as a .csv

VacationPy.ipynb was coded to do the following from the csv generated from WeatherPy.ipynb:
* Create a heat map that displays the humidity for every city.
* Narrow down the DataFrame to find ideal weather conditions.
* Use Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.
* Plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.

Each map was copied into images as a .png.



