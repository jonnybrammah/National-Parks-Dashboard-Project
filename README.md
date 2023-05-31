# National-Parks-Dashboard-Project

![Yosemite National Park](https://www.usnews.com/object/image/0000017e-e523-de90-a17f-edb3388f0000/1-intro-stock.jpg?update-time=1644521797113&size=responsive970)

## Project Overview

The goal of this project was to collect, clean, transform and visualize data about National Park Services (NPS) Lands to help a user plan a visit to parks. Our intended user was a person who may not be typically "Outdoorsy" and so may not know huge amounts about National Park Lands, but who is interested to visit some, either nearby or as part of a road trip. The goal was to provide them some actionable and easily digestable takeaways from the wealth of data about National Parks available. The visualizations focus on National Parks proper, but also contain information about all other NPS lands, including National Monuments, Memorials, Historical Sites, etc. The full range of park designations can be found in our dashboard.

Our two visualizations are:
- [Map] which shows the location of all NPS lands, where the circle is scaled to represent the number of visitors to that park. When a particular park is clicked, basic information about the park, including its designation, entrance fee, and total visitors in 2022 is displayed.
- [Dashboard] which shows the number of visitors for each month of 2022 and how this changed across the year. This also shows the average Yelp review for a park. The designation of a park (Park, Monument, Memorial, etc.) can be selected on this dashboard and two bar charts at the bottom will show:
   - The "Hidden Gems" of that designation, which are parks with very few visitors in 2022 but that are highly rated by Yelp Users (an average 5 star rounded rating), sorted from least visited
   - The Free parks for that designation, which are parks with no entrance Fee. This is sorted from most visited to least visited, but includes all free parks.

-----

## Table of Contents


-----

## Data Collection

Data was collected from a few places and later cleaned and transformed.
- [The National Park Service API](https://www.nps.gov/subjects/developer/api-documentation.htm) which contained data about the locations and entry fees of National Park Service Lands, though not visitor information.
- [National Park Visitor User Statistics](https://irma.nps.gov/Stats/) which contained data about how many visitors a National Park had each month going back for many years. This data was downloadable as csv files, but to simplify this process could also be scraped online.
- [Yelp API](https://fusion.yelp.com/) which contained information about average Yelp rating for the NPS Lands. This was used to let users know how parks were rated and to identify "Hidden Gems".


## Data Visualizations

### Map Plot

### Dashboard

## Conclusions

### Acknowledgements
