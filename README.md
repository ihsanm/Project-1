# City Crime Data
## User story
As a user
* I want to find the crime data of my city or other cities. 
* I want to know the various types of crime  and the data through the chart
* I also want to  find the police information of the city.
* SO THAT I can find out about the safety of the city where I live or travel and etc.

## Our motivation for development

* We want to be able to view recent crime information for any given location in the UK as we feel this would be useful for anybody thinking of perhaps taking a city break in the UK, or is having to relocate for work etc. and would like to know which areas are the safest.
* We also felt that it is nice to know the levels and types of crime for the area in which you live. Could be the impetus for locking away you bike if bicycle theft is prevalent for example.

## Acceptance Criteria

* It will be done when the user can search for a location in Great Britain and
  * view local crime statistics in graph and table form
  * view information about the location police force (including social media links).
* The user can automatically view data for their current location
* Previous searches will be accessible for future access
* The site theme will switch to a dark theme if it is currently night time at the user location
* User will be able to override the default theme with one button click
* As the user types a search query an autocomplete list will display of matched locations.


## The APIs we used and the function
 * Uses the [UK Police Data API](https://data.police.uk/docs/) to get the crime in searched area.
 * Uses [OpenWeatherMap](https://openweathermap.org/api/geocoding-api) to get the longitude and latitude.
 * Uses the [UK Police Force API](https://data.police.uk/docs/method/force/) to get a brief summary of the localities police force.
 * Uses the [Google Places API](https://developers.google.com/maps/documentation/places/web-service/autocomplete) to get an autocomplete list as the user types
  * Uses a [Reverse Geocoding API](https://api.bigdatacloud.net/data/reverse-geocode-client) to get the approximate user location by IP address
  * Uses https://api.sunrise-sunset.org to calculate the sun rise/sunset for a given location

 Though these the site:
 * Finds the crime data and use a spider graph to display crime in given city.
 * Previous searches will be stored in local storage and can be revisited.
 * A clear search history button which will remove all previous searches.
 
 ## The screenshots
![image of screenshot1](./screenshots/1.png)
![image of screenshot2](./screenshots/2.png)
![image of screenshot3](./screenshots/3.png)
![image of screenshot4](./screenshots/4.png)


 ### Bonus feature
 * MAPS!
 
 ## Github URL: https://github.com/ihsanm/City-crime-data
 ## Deployed Site: https://ihsanm.github.io/City-crime-data/
