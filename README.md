# Bay Wheels visualization project
## by Tien Duong


## Dataset

The goal of this project is to analyze and visualize the `lyfy_bike_data.csv`. This project is part of the Udacity's Data analysis program. The Dataset contain 13 columns and 154967 rows that extracted from the lyft webpage under bay-wheel >https://www.lyft.com/bikes/bay-wheels/system-data<. The dataset consist of `longtitude` and `latitude` coordinates. Ride_type and ID under `ride_id` and `ride_type`. Start_station_name and ID under `start_station_name` and `start_station_name_id`. End_station_name and ID under `end_station_name` and `end_station_name_id`. Membership type under `member_casual`.

Sources of references for geopandas plotting that I used to generate the dataset coordinates.  
The open soures SF geographic data >https://data.sfgov.org/Geographic-Locations-and-Boundaries/Bay-Area-Counties/s9wg-vcph<

Plot generating tutorial by Ian Forrest >https://medium.com/@ianforrest11/graphing-latitudes-and-longitudes-on-a-map-bf64d5fca391<




## Summary

In the finding of my analysis, I was able to observe the different type of user behaviors between member and non member on different day of the week. Majority of the rides operate on Friday and Saturday by non-member and majority prefer using the electric bike over normal bike. Also by looking into the coordinates graph with time duration, majority of rides happen in San Francisco downtown city. 


## Insights


## Key Insights For Presentation
The key focus oy my presentation is focus on the different duration time rides user used throughout the week. First, I present sample of all numerical correlation using heatmap of the data. This will give quick visual insight for reader to understand the dataset. I follow up with the bar graph slides viewing of the two different set of of data of member and non member user's type with the weekday on the x axis and duration frequency on the y axis. Then, I introduce another heatmap plot with color map guided as a multivariate plot that present the same measurement as the previous chart but with the average duration time instead of frequencies. Finally, I final the presentation with the slide of geographic location coordinates plot of the given longtitude and latitude from the dataset.
