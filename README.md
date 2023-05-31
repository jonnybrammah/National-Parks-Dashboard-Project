# National-Parks-Dashboard-Project

![Yosemite National Park](https://roadtrippingcalifornia.com/wp-content/uploads/2022/06/El-Capitan-Yosemite.jpg)

## Project Overview

The goal of this project was to collect, clean, transform and visualize data about National Park Services (NPS) Lands to help a user plan a visit to parks. Our intended user was a person who may not be typically "Outdoorsy" and so may not know huge amounts about National Park Lands, but who is interested to visit some, either nearby or as part of a road trip. The goal was to provide them some actionable and easily digestable takeaways from the wealth of data about National Parks available. The visualizations focus on National Parks proper, but also contain information about all other NPS lands, including National Monuments, Memorials, Historical Sites, etc. The full range of park designations can be found in our dashboard.

Our two hubs for showing the visualizations are:
- [Map](https://github.com/jonnybrammah/National-Parks-Dashboard-Project/tree/main/Data%20Visualization/Map) which shows the location of all NPS lands, where the circle is scaled to represent the number of visitors to that park. When a particular park is clicked, basic information about the park, including its designation, entrance fee, and total visitors in 2022 is displayed.
- [Dashboard](https://github.com/jonnybrammah/National-Parks-Dashboard-Project/tree/main/Data%20Visualization/Graph) which shows the number of visitors for each month of 2022 and how this changed across the year. This also shows the average Yelp review for a park. The designation of a park (Park, Monument, Memorial, etc.) can be selected on this dashboard and two bar charts at the bottom will show:
   - The "Hidden Gems" of that designation, which are parks with very few visitors in 2022 but that are highly rated by Yelp Users (an average 5 star rounded rating), sorted from least visited
   - The Free parks for that designation, which are parks with no entrance Fee. This is sorted from most visited to least visited, but includes all free parks.

-----

## Table of Contents
1. [Overview of National Park Information](https://github.com/jonnybrammah/National-Parks-Dashboard-Project/blob/main/README.md#overview-of-national-park-information)
2. [Data Collection](https://github.com/jonnybrammah/National-Parks-Dashboard-Project/blob/main/README.md#data-collection)
3. [Data Visualizations](https://github.com/jonnybrammah/National-Parks-Dashboard-Project/blob/main/README.md#data-visualizations)
   - [Map Plot](https://github.com/jonnybrammah/National-Parks-Dashboard-Project/blob/main/README.md#map-plot)
   - [Dashboard](https://github.com/jonnybrammah/National-Parks-Dashboard-Project/blob/main/README.md#dashboard)
4. [Conclusions](https://github.com/jonnybrammah/National-Parks-Dashboard-Project/blob/main/README.md#conclusions)

-----

## Overview of National Park Information
There were 469 NPS Properties collected in the dataset, divided into different designations (National Park, National Monument, National Memorial, etc.)

The five most common designations included in the dataset are:
| Designation | Number |
| --- | --- |
| National Monument | 79 |
| National Historic Site | 78 |
| National Historical Park | 63 |
| National Park | 51 |
| National Historic Trail | 17 |

The remaining designations having fewer properties listed under them with around 30 having fewer than 10 and around 20 having only one property in that designation.

The number of visitors at NPS properties hovers at just over 300 million each year. In 2022 there were roughly 312 million visitors, which is down from the pre-COVID record of 330 million in 2017. The number of visitors over all NPS properties over the previous 25 years can be seen here:

![Visitors over last 25 years](https://raw.githubusercontent.com/jonnybrammah/National-Parks-Dashboard-Project/main/Output/Images%20for%20Presentation/Visitors_for_previous_25_years.png)

Of these parks, National Parks proper have the highest number of visitors, with more than 80 million in 2022. This represents about twice the amount of visitors of any other designation.

![Visitors by designation](https://raw.githubusercontent.com/jonnybrammah/National-Parks-Dashboard-Project/main/Output/Images%20for%20Presentation/Park_visitors_by_designation.png)

-----

## Data Collection

Data was collected from a few places and later cleaned and transformed.
- [The National Park Service API](https://www.nps.gov/subjects/developer/api-documentation.htm) which contained data about the locations and entry fees of National Park Service Lands, though not visitor information.
- [National Park Visitor User Statistics](https://irma.nps.gov/Stats/) which contained data about how many visitors a National Park had each month going back for many years. This data was downloadable as csv files, but with so many parks to download data from, this process could be simplified by scraping the information.
- [Yelp API](https://fusion.yelp.com/) which contained information about average Yelp rating for the NPS Lands. This was used to let users know how parks were rated and to identify "Hidden Gems".

-----

## Data Visualizations

### Map Plot

### Dashboard

-----
## Conclusions

-----
### Acknowledgements

This project was completed with contributions from J. Brammah, K. Farabaugh, A. Hussain, and G. Jimenez.
