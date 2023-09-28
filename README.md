
![Citi-Bikes](https://static.bc-edx.com/data/dl-1-2/m18/lms/img/citi-bike-station-bikes.jpg)

Congratulations on your new job! In this project, envision yourself as the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) program. You are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.


## Citi Bike Tableau Dashboard
Citi Bike Ridership Dashboard for May 2023 can be found [here](https://public.tableau.com/app/profile/jae.zakarauskas/viz/CitiBikeAnalysis_16898848996080/CitiBikeStory). Trip data used is for May 2023 and can be found [here](https://s3.amazonaws.com/tripdata/JC-202305-citibike-tripdata.csv.zip).

### Top 20 Most Popular Starting and Ending Stations for May 2023
This screenshot from the Tableau Dashboard shows the 20 most popular starting and ending stations using timestamp data for May 2023. Start stations are represented by blue markers and end stations are represented by red markers. Clusters of markers are in close proximity to Hoboken Terminal and other train stations, suggesting many riders are using Citi Bikes to commute to and from train stations. A large cluster is in close proximity to Stevens Institute of Technology (SIT). According to stevens.edu Common Data Set, there were 9,314 students enrolled during the 2022-2023 school year, as well as 335 faculty members, and 603 staff members. The cluster suggests riders rely on Citi Bikes to commute to and from SIT. 


![Screenshots use map data from Mapbox and OpenStreetMap and their data sources. To learn more, visit https://www.mapbox.com/about/maps/ and http://www.openstreetmap.org/copyright](https://github.com/jaezak/tableau_challenge/assets/122832045/5c9507e1-670c-494f-8757-bf089f76e154)
#### Screenshots use map data from Mapbox and OpenStreetMap and their data sources. To learn more, visit https://www.mapbox.com/about/maps/ and http://www.openstreetmap.org/copyright. © <a href='https://www.mapbox.com/about/maps/'>Mapbox</a> © <a href='http://www.openstreetmap.org/copyright'>OpenStreetMap</a> <strong><a href='https://www.mapbox.com/map-feedback/' target='_blank'>Improve this map</a></strong> 

## Top 20 Start and End Stations
Bar graphs depicting the top 20 start and end stations were created with parameters containing  station name data and count data. The graphs share 18 of the same stations, with 9 of them being in close proximity to train stations and ferry terminals. Another high traffic bike station is close to the South Waterfront Walkway, a riverside cycling and walking path, and another is close to a hospital. It is interesting to note the 6th most popular start and end station is Washington Street and First Street. Not only is this station located on the same block as Hoboken City Hall, it also directly across the street from Carlo's Bakery, established in 1910 and run by the Valastro Family for 4 generations. The bakery is featured in TLC's reality show "Cake Boss" since 2009 and has become a tourist attraction. This suggests a large amount of riders use the Washington and 1st Station to travel to and from City Hall and Carlo's Bakery.

![Top 20 Start and End Stations ](https://github.com/jaezak/tableau_challenge/assets/122832045/2f1de19f-7100-4467-a367-dbdf4101c6f9)

## Ridership by the Hour
![Ridership by the Hour](https://github.com/jaezak/tableau_challenge/assets/122832045/33159bf7-6a85-477d-b08f-540df3224efb) 

Visualization shows hourly ridership flow, taken from ride start and ride end timestamp data. Start and end rides peak at 8 am and 6 pm, suggesting many riders relying on Citi Bike to commute to and from work. Ridership is lowest at 3 am for both visualizations. Although there is no statewide law, most cities require bars to close at 2 am. Low ridership at 3 am suggests bar and nightlife patrons have headed home for the night.

## Bike Type and Rider Type
![bike_type_rider_type](https://github.com/jaezak/tableau_challenge/assets/122832045/9d722034-8b64-4acd-a673-122797acb021)
Visualization shows that 81.21% of the bikes rented in May 2023 were classic bikes, and 18.79% were electric. This shows there are simply more classic bikes available at any given time. Visualization shows that 72.1% of riders in May 2023 were membership riders. Considering how a majority of the top 20 most popular starting and ending stations were close to a mode of public transportation, this data suggests that a large amount of riders live in the area and rely on Citi Bikes for their daily commute to and from work. Customers who use Citi Bike on a frequent basis are more inclined to pay for a membership.

## Average Ride Duration
![Average Ride Duration](https://github.com/jaezak/tableau_challenge/assets/122832045/3c4a7ee0-3b1a-4735-ae89-b00b1ef5f67c)

Average ride duration and percent of total rides is visualized below. Bar graph shows Citi Bike members average 11.2 minutes per ride, whilst casual riders average 25.8 minutes per ride. This suggests members are locals who primarily utilize Citi Bikes as a mode of transport to and from work, whilst casual riders utilize Citi Bikes for leisure. Data shows that 66.9% of rides for May 2023 were 1-10 minutes in length, further supporting this claim. The category labeled "false starts" depicts rides that were less than a minute in length and should be considered an outlier. 





