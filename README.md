# *Adam Dunbar's Unit 6 API Homework*

## "WeatherPy"

### Summary of Findings:
In this study, I attempted to see the affects (if any) that Latitude has on various weather vairables (see below). 

Data was collected on Friday, July 26th, 2019 at 10:00 am PDT, thus the figures presented in the final database are a nice snapshot into the weather conditions for a Northern Hemisphere Summer and a Southern Hemisphere Winter. 

I found that Temperature has a strong negative relationship with Latitude. That is, as Latitude increases, Temperature decreases in a predictable way. The other variables of Humidity, Cloud Cover and Wind Speed were not significantly dependant on Latitude.

### Deliverables:
1. [**Jupyter Notebook with Analysis**](https://github.com/Siderall/HW6-WeatherPy-AD/blob/master/WeatherPy_final.ipynb)
2. [**Raw Data Print Log**](https://github.com/Siderall/HW6-WeatherPy-AD/blob/master/final_data-log.txt)
* 611 cities were randomly selected from the cities.csv database and then used to make an API call to the OpenWeatherMap API. Some of the cities were skipped because they didn't exist in the OpenWeatherMap database. In total, 544 cities were returned from the API call.
3. [**Finalized Database (CSV)**](https://github.com/Siderall/HW6-WeatherPy-AD/blob/master/city_weather_data.csv)
*  The lists that were filled up during the API call process were then formatted into a Pandas Data Frame and exported to CSV.
4. [**Plot 1: Latitude vs Temperature**](https://github.com/Siderall/HW6-WeatherPy-AD/blob/master/Plot1_Latitude_Temp.png)
5. [**Plot 2: Latitude vs Humidity**](https://github.com/Siderall/HW6-WeatherPy-AD/blob/master/Plot2_Lat_Hum.png)
6. [**Plot 3: Latitude vs Cloud Cover**](https://github.com/Siderall/HW6-WeatherPy-AD/blob/master/Plot3_Lat_Cloud.png)
7. [**Plot 4: Latitude vs Wind Speed**](https://github.com/Siderall/HW6-WeatherPy-AD/blob/master/Plot4_Lat_Winf.png)

### Further Discussion:
One consideration to note with this data is the appearance of clustering in the scatter plots for cities with positive value Latitudes (Northern Hemisphere). The Northern Hemisphere has significantly higher land mass than the Southern Hemisphere, and thus there are not as many cities present in the Southern half of the Earth than in the Northern half. This means that when I randomly selected cities from the World Cities database (cities.csv), a higher number of them were from the Northern Hemisphere, giving the clustering affect seen in some of the Scatter Plots.
