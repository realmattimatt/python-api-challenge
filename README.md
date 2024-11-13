# python-api-challenge
## Description:
Used Python, Pandas, hvplot, requests, os, matplotlib, scipy.stats, numpy, sklearn, openweathermap API, citipy and geoviews to create a Python script to visualize the weather of over 500 cities of varying distances from the equator.

Then use your weather data skills to plan future vacations based on consumer preferences in weather. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

### Dependancies to install.
1. import hvplot.pandas
2. import pandas as pd
3. import requests
4. import matplotlib.pyplot as plt
5. import numpy as np
6. import time
7. from scipy.stats import linregress

### Import API key
1. from api_keys import geoapify_key

### How to run. 
1. Update api_keys
2. Open and run WeatherPy.ipynb
3. After completion run VacationPy
4. ideal_weather_df = city_data_df[(city_data_df["Max Temp"] < 27) & (city_data_df["Max Temp"] > 11) & (city_data_df["Humidity"] < 50)] Changing the values for Max Temp or Humidity will affect the outcomes. You can add "&(city_data_df["Cloudiness"] < ?)" or and "&(city_data_df["Wind Speed"] < ?)"

###Sources
1. Class instruction
2. Peer help
3. Xpert Learning Assist
4. Stack Overflow
5. CS50P
6. Office hours
7. Tutor session with Brandon
8. ChatGPT
9. Documentation for many things like hvplot, requests, os, citipy, openweathermap etc. 

