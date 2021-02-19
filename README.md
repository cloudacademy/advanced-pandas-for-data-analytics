# Advanced Pandas for Data Analytics

This repository provides the data in support of the course Advanced Pandas for Data Analytics, provided by Cloud Academy.

## Data

We have used the Bike Sharing Dataset in this course, which all are available in the data folder. I suggest to follow the following steps in order you to be able to replicate the course steps in your local host.

Open your favourite terminal emulator, and then:

#### 1. Clone the repo
```bash
git clone https://github.com/cloudacademy/advanced-pandas-for-data-analytics.git
```
#### 2. Create a python virtualenv
```bash
mkvirtualenv - p python3 <NAME_ENV>
```
#### 3. Install the necessary requirements:
```bash
pip install -r requirements.txt
```
#### 4. Open a jupyter notebook by running:
```bash
jupyter notebook
```
You are now ready to get your hands dirty: enjoy!

## Dataset Characteristics

Among many fields, it is worth to map the following variables:
 * workingday: if day is neither weekend nor holiday is 1, otherwise is 0.
 * weathersit: 
     * _Clear, Few clouds, Partly cloudy, Partly cloudy_ mapped in value 1;
     * _Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist_ mapped in value 2;
     * _Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds_ mapped in 3;
     * _Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog_ mapped in 4.
  * temp: Normalized temperature in Celsius. The values are divided to 41 (max).
  * atemp: Normalized feeling temperature in Celsius. The values are divided to 50 (max).
  * hum: Normalized humidity. The values are divided to 100 (max).
  * windspeed: Normalized wind speed. The values are divided to 67 (max).
  * casual: count of casual users.
  * registered: count of registered users.
  * cnt: count of total rental bikes including both casual and registered.
