# CitiBike Analytics

Tableau visualisations of Citibike New York Data

## Notes:
* Multiple data sets were joined and then filtered to create a date range covering 12 months in line with US Seasons:
    * March 19th – June 19th 2020 (Spring)
    * June 20th – Sept 22nd 2020 (Summer)
    * Sept 22nd - Dec 20th 2020 (Autumn/Fall)
    * Dec 21st – March 19th 2020 (Winter)
* COVID restrictions in New York City throughout 2020 may have resulted in limited data as it is concentrated in Jersey City

## Dashboard 1: Maintenance requirements vs Availability requirements
* Worksheet: 12 months of bike usage by time
* Worksheet: Number of trips vs Avg trip duration over time
* Worksheet: Number of trips vs Avg trip duration vs Hour of day

This dashboard was designed to see detailed usage of bikes throughout 12 months (Spring 2020 to Winter 2021) to plan maintenance.  

Bar charts indicate bikes which have the most use, either by number of times they were used or length of time used.

By tracking which station bikes requiring urgent or ASAP maintenance are located, it can also be determined if bikes in the “soon” and “consider” category are nearby. Hence including them in the maintenance collection.

The line chart helps understand what months the demand for bikes is low, allowing for scheduled maintenance. The number of trips spike in September (late Summer/early Autumn) and dip considerably in October and continue to go down. October/November would be an ideal period for maintenance, potentially as many bikes may require maintenance after such a busy period. 

Ever though trip numbers are low through Winter and early Spring (December to March), there are spikes in trip duration in February and March. A second maintenance period could be scheduled for bikes with high time usage in April, so the optimum number of bikes are back in use and recently maintained before the trip numbers pick up again in May

The scatterplot indicates trip numbers for the time of day (Aggregated from the whole year). Not surprisingly, the earliest hours of the morning experience the lowest demand with the highest at 6pm. Particularly in the busier months, bikes out of use for maintenance should be back in circulation by 10am, as demand rises from there. If it was determined that bikes need urgent maintenance, they could be collected from 8pm when demand has drop significantly. 

The data could be made more usefully if it included the last time a bike was serviced. Usage could be then measured from that date. Information around how often a bike needs to receive maintenance on average to keep it running at it’s optimum could inform the thresholds used to measure maintenance priority.

![D1 - Maintenance requirements vs Availability requirments](https://raw.githubusercontent.com/jMacProd/Citibike-NY/main/Images/D1%20-%20Maintenance%20requirements%20vs%20Availability%20requirments.png)

## Dashboard 2: Usage by Gender vs Age
* Worksheet: Number of trips by Gender vs Age groups
* Worksheet: Number of trips by Gender vs Time of travel
* Worksheet: Number of trips by Age group vs Time of travel

This dashboard was designed for quick and easy understanding of key concepts around the use of Citibike by gender and age. It is focused more on visualisation than detailed data.

To aid these visualisations, ages have been grouped (ie 20s, 30s, 40s).

The bubble chart clearly shows that males are by far the most users of Citibike across all age groups with males in their 30s being the highest users. The map visualisation for popular stations (see Popular Stations Dashboard) supports this finding as Jersey City has a high male/female ration with a median age of up to 35.  

The line chart not surprisingly shows the 30s age bracket as generally the most users throughout the day. Interestingly, the second highest users across the day are the 50s age bracket. And that bracket has the highest usage from 9pm to 5am. Further demographics data would be useful to determine more about this age bracket. 

The hour of the day area chart has little impact on gender use of the bikes. It follows the usual trend determined in Dashboard 1. 

![D2 - Usage by Gender vs Age](https://raw.githubusercontent.com/jMacProd/Citibike-NY/main/Images/D2%20-%20Usage%20by%20Gender%20vs%20Age.png)

## Dashboard 3: Popular Station Maps
* Worksheet: Popular Start Stations
*  Worksheet: Popular Stop Stations

Possibly due to COVID restrictions, activity for these 12 months of data is concentrated on Jersey City. There’s a couple of stations that stand out as both popular starting and stopping stations. 

Thanks to Google and Google Maps, here’s some potential reason for the high usage of these stations

**Grove Street PATH**
* Downtown Jersey City. Cheaper tourist accommodation and transportation hub.

**Newport Parkway**
* A lot of tourist accommodation, easy access to New York.

**Liberty Light Rail**
* Access to Liberty State Park. Views of New York City and Statue of Liberty.

**Hamilton park**
* Historic Downtown Jersey City.

**Sip Avenue**
* Located near Journal Square business district, transportation hub

Although not a lot of stopping station data was different to the starting station data, using the dynamic date slider, it shows that in the summer months there were some stopping stations scattered around the other areas of New York.

![D3 - Popular stations](https://raw.githubusercontent.com/jMacProd/Citibike-NY/main/Images/D3%20-%20Popular%20stations.png
)

## Story 1: Maintenance requirement versus availability
* Worksheet: 12 months of bike usage by number of trips
* Worksheet: 12 months of bike usage by time
* Dashboard 1: Maintenance requirements vs Availability requirements
* Dashboard 3: Popular Stations Maps

## Story 2: Maintenance requirement versus availability
* Worksheet: Number of trips vs Avg trip duration over time
* Dashboard 2: Usage by Gender vs Age
