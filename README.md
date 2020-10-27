# python-api-challenge


**Data Analysis For VacationPy and WeatherPy by Shanil Lobanwala**

**Note** The tables on github do not look as clean as on the jupyter notebook IDE which is why I've attached images to the readme as well incase user does not want to clone them locally and see them on an ide. The file is located inside my_submission directory. There are two projects, one is called [WeatherPy](https://github.com/slobanwala1/python-api-challenge/blob/main/my_submission/starter_code/WeatherPy.ipynb). The other is called [VacationPy](https://github.com/slobanwala1/python-api-challenge/blob/main/my_submission/starter_code/VacationPy.ipynb). The Images are located in [my_submission/Images/output_data](https://github.com/slobanwala1/python-api-challenge/tree/main/my_submission/Images/output_data). 

**WeatherPy** first has us generate a random amount of city names and grabs there information from the weather API and we make statistical analysis on them as well as plotting graphs to see trends and
correlations.

## Here are the snapshots and analysis:

**Temperature (F) vs. Latitude**

<br>
<br>
<img src="https://github.com/slobanwala1/python-api-challenge/blob/main/my_submission/Images/output_data/Fig1.png" width="500">

**Humidity (%) vs. Latitude**

<br>
<br>
<img src="https://github.com/slobanwala1/python-api-challenge/blob/main/my_submission/Images/output_data/Fig2.png" width="500">

**Cloudiness (%) vs. Latitude**

<br>
<br>
<img src="https://github.com/slobanwala1/python-api-challenge/blob/main/my_submission/Images/output_data/Fig3.png" width="500">

**Wind Speed (mph) vs. Latitude**

<br>
<br>
<img src="https://github.com/slobanwala1/python-api-challenge/blob/main/my_submission/Images/output_data/Fig4.png" width="500">

**Northern Hemisphere - Temperature (F) vs. Latitude**

<br>
<br>
<img src="https://github.com/slobanwala1/python-api-challenge/blob/main/my_submission/Images/output_data/Fig5.png" width="500">

**Southern Hemisphere - Temperature (F) vs. Latitude**

<br>
<br>
<img src="https://github.com/slobanwala1/python-api-challenge/blob/main/my_submission/Images/output_data/Fig6.png" width="500">

**Northern Hemisphere - Humidity (%) vs. Latitude**

<br>
<br>
<img src="https://github.com/slobanwala1/python-api-challenge/blob/main/my_submission/Images/output_data/Fig7.png" width="500">

**Southern Hemisphere - Humidity (%) vs. Latitude**

<br>
<br>
<img src="https://github.com/slobanwala1/python-api-challenge/blob/main/my_submission/Images/output_data/Fig8.png" width="500">

**Northern Hemisphere - Cloudiness (%) vs. Latitude**

<br>
<br>
<img src="https://github.com/slobanwala1/python-api-challenge/blob/main/my_submission/Images/output_data/Fig9.png" width="500">

**Southern Hemisphere - Cloudiness (%) vs. Latitude**

<br>
<br>
<img src="https://github.com/slobanwala1/python-api-challenge/blob/main/my_submission/Images/output_data/Fig10.png" width="500">

**Northern Hemisphere - Wind Speed (mph) vs. Latitude**

<br>
<br>
<img src="https://github.com/slobanwala1/python-api-challenge/blob/main/my_submission/Images/output_data/Fig11.png" width="500">

**Southern Hemisphere - Wind Speed (mph) vs. Latitude**

<br>
<br>
<img src="https://github.com/slobanwala1/python-api-challenge/blob/main/my_submission/Images/output_data/Fig12.png" width="500">


## Three observable trends:

1. In the Northern Hemisphere the r value was negative since as we move away from the equator the temperature will decrease and thus the r value will be negative and we will have a downwards graph for
Max Temp vs. Latitude

2. In the Southern Hemisphere the r value is positive since it makes sense for a positive correlation as we get closer to the equator the tempearture will increase for Max Temp vs Latitude

3. Humidity, Cloudiness, and Wind Speed were kind of all around the place and it was hard to make a correlation or an observable trend but if I had to guess looking at the graphs Humidity increases as we get away from the equator and stays around an average value when near the equator. For Cloudiness its more cloudy near the equator then away from it. For wind speed the wind speed is more clustered away from the equator while more spread out near the equator.



**VacationPy** uses the csv of cities to clean it, and then narrow it for certain ideal weather conditions. After that we create a heat map of hotels in those narrowed down cities.

## Here are the snapshots:

**Heat Map before narrowing it down to ideal conditions**

<br>
<br>
<img src="https://github.com/slobanwala1/python-api-challenge/blob/main/my_submission/Images/output_data/Fig13.png" width="500">

**Heat Map after narrowing it down to ideal conditions with labels**

<br>
<br>
<img src="https://github.com/slobanwala1/python-api-challenge/blob/main/my_submission/Images/output_data/Fig14.png" width="500">

