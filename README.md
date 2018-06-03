# New York Subway Hearbeat Visualization

## Overview
Visualization is important for people to understand the life data. This project using the turnstile data in New York subway, and desire to show the flow over the spaces.

New York Subway HeartBeat
![New York Subway Heartbeat](https://github.com/Ruby1993/New-York-Subway-Hearbeat-Visualization/blob/master/Visual.gif)

## Process

- Checked the inconsistency in station name between the subway turnstile data and station data in order to identify the location of each turnstile.

- Calculate the differece of the cumulated entries and exits by each sensor while time increasing.

- Changed the field format, identified the outliers because of the sensors failures, and updated the value.

- Summarized the data based on stops, dates and hours and using python folium to visulize the population traffic in each subway station with average interpolation by hour as the turnstile data is recorded by 4 hour.

## Result

- For the visualization, the organge circle means more people enter the subway then people left the subway. The blue circle means more people left the subway then people came in the subway.

- In general, more people came out of the subway in Manhattan from 8am to 3pm, and they usually came from different bourough. After 4pm, there are more people came in the subway which is matched worker's behavior.

- During one day, there are two rush hour peaks. One is from 7pm to 9pm and another one is from 8am to 9am. On the other hand, less people in the subway from 5am to 7am and from 6pm to 7pm.
