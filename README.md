# MODULE 6
### Python-api-Challenge

#### Background
This module challenge was boken down into two parts. The first part of this activity included creating a representative model of weather across cities created from the citipy library and openweathermap APIs. The second part included using the Geoapify API and the geoViews Python library and employing our Python skills to create map visualizations for vacation ideas using our citipy library. 


#### Instructions
1. WEATHERPY:
   
   a. Create Plots to Showcase the Relationship Between Weather Variables and Latitude:
   
      --Latitude vs. Temperature
   
      --Latitude vs. Humidity
   
      --Latitude vs. Cloudiness
   
      --Latitude vs. Wind Speed
   
   
   b. Compute Linear Regression for Each Relationship:
   
      -Northern Hemisphere: Temperature vs. Latitude
   
      -Southern Hemisphere: Temperature vs. Latitude
   
      -Northern Hemisphere: Humidity vs. Latitude
   
      -Southern Hemisphere: Humidity vs. Latitude
   
      -Northern Hemisphere: Cloudiness vs. Latitude

      -Southern Hemisphere: Cloudiness vs. Latitude
   
      -Northern Hemisphere: Wind Speed vs. Latitude
   
      -Southern Hemisphere: Wind Speed vs. Latitude
   

2. VACATIONSPY: Use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations
   
   
      -Create a map that displays a point for every city in the city_data_df
   
      -Narrow down the city_data_df DataFrame to find your ideal weather condition
   
      -Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
   
      -For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
   
      -Add the hotel name and the country as additional information in the hover message for each city
   

#### References
1. https://geoviews.org/user_guide/index.html
2. https://openweathermap.org/guide
