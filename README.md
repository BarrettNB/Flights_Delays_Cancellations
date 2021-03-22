# Effects of Weather Events on Flight Delays and Cancellations

## Introduction

"Your flight has been cancelled." These may be the five most hated words for an airline passenger. They disrupt travel plans, cost everyone time and money, and can hurt an airline's reputation. However, in some cases an airline has no choice but to cancel a flight or to delay one. If we could create an algorithm that would allow an airline to discover that they need to delay or cancel a flight a long time in advance, they could buy time for the customer to change their travel plans, perhaps with the help of that airline.

This project seeks to establish the relationship of weather events to the likelihood of commercial airline flight delays and cancellations. Flight data was compiled from the Bureau of Transportation Statistics website; weather events were taken from a Kaggle webpage (URL below) based on the paper "Short and Long-term Pattern Discovery Over Large-Scale Geo-Spatiotemporal Data" by Moosavi, et al. All flights in 2016-2019 among four major airports, and the weather events in those cities, were selected.

## Documents

[Final report](https://docs.google.com/document/d/1XQ8gl-qLqRCllhvkCPSiF7Lv7svK_WlYhrgTpIE-oFQ/edit?usp=sharing)

## Data Sources

[Weather data](https://www.kaggle.com/sobhanmoosavi/us-weather-events)

[Flight data (URL subject to change)](https://www.transtats.bts.gov/Tables.asp?DB_ID=120&DB_Name=Airline%20On-Time%20Performance%20Data&DB_Short_Name=On-Time)

## Notebooks

Data is collected and filtered from the weather events and from flights; weather events in Part 1a, flights in 1b. This is done with the goal of merging the data, which occurs in Part 2. Part 3 runs through exploratory data analysis. In Part 4, machine learning algorithms are considered, and the results and implications of the selected model are analyzed.

[Part 1a: Weather Events](https://github.com/BarrettNB/Springboard_Capstone_2/blob/master/Steps_2-3_DataWrangling_EDA_1a_WeatherEvents.ipynb)

[Part 1b: Flights](https://github.com/BarrettNB/Springboard_Capstone_2/blob/master/Steps_2-3_DataWrangling_EDA_1b_Flights.ipynb)

[Part 2: Merging Flight and Weather Data](https://github.com/BarrettNB/Springboard_Capstone_2/blob/master/Steps_2-3_DataWrangling_EDA_2_Merging.ipynb)

[Part 3: Exploratory Data Analysis](https://github.com/BarrettNB/Springboard_Capstone_2/blob/master/Steps_2-3_DataWrangling_EDA_3_Analysis.ipynb)

[Part 4: Machine Learning and Analysis](https://github.com/BarrettNB/Springboard_Capstone_2/blob/master/Step_4_Training.ipynb)
