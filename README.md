# Call For Code Spot: Australian Wildfires
Elvis C, Shruti Chaturvedi, Divyansh Choubisa, Albert Um

## Objective
The goal for this project is to forecast wildfires in Australia for February 2021. The estimated fire area represents the summation of fire activity in a 1km by 1km region. The Australian regions are 7 states:
- NSW = New South Wales
- NT = Northern Territory
- QL = Queensland
- SA = Southern Australia
- TA = Tasmania
- VI = Victoria
- WA = Western Australia



## Structure of Repository


## Data
The original zip datafile can be retrieved from the code challenge git page; provided [here](https://github.com/Call-for-Code/Spot-Challenge-Wildfires). <br>
The zipped data file includes the following:

```
Nov_10
└───Historical_Wildfires.csv
│   └─── :: Contains data on fire activites in Australi from 2005.
└───HistoricalWeather.csv
│   └─── :: Contains daily aggregates of weather including Precipitation
│        :: Humidty, Soil water content, Solar Radiation, Temperature
│        :: and Wind Speed.
└───HistoricalWeatherForecasts.csv
│   └─── :: Contains forecasted values for weather in 5, 10 or 15 lead times.
└───LandClass.csv
│   └─── :: Contains terrain properties of the 7 regions pulled on 2015.
└───VegetationIndex.csv
    └─── :: Contains monthly vegetation values(min, max, mean, variance) 
         :: for each region
```


## Preprocessing