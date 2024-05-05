# python-api-challenge
Module 6: Python APIs
# Timeline:
    1. Sat May 4th, ~3PM created repository in github
    2. Sat May 4th, 4:22PM created base url for API retrieval and retrieved data for 581 Cities
    3. Sat May 4th, 4:58PM went back and added "metric" to my api url to make scatter plots easier to read. 
    4. Sat May 4th, 6:18PM completed scatter plots for:
        Lat vs Temp
        Lat vs Humidity
        Lat vs Cloudiness
        Lat vs Wind Speed
    5. Sat May 4th, 7:45PM completed first linear regression using def function
    6. Sat May 4th, 8:04PM completed all linear regression scatter plots for Northern and Southern Hemispheres:
        Northern Hemisphere: Temperature vs. Latitude
        Southern Hemisphere: Temperature vs. Latitude
        Northern Hemisphere: Humidity vs. Latitude
        Southern Hemisphere: Humidity vs. Latitude
        Northern Hemisphere: Cloudiness vs. Latitude
        Southern Hemisphere: Cloudiness vs. Latitude
        Northern Hemisphere: Wind Speed vs. Latitude
        Southern Hemisphere: Wind Speed vs. Latitude
    7.Sat May4th, 9:06PM added description for linear regression
       
# Linear Regression Analysis
    ## Lat vs Temp: 
        Linear Relationship: In the Northern Hemisphere, there exists a significant negative correlation (r = -0.85) between cities located farther from the equator (latitude 0) and their temperatures. Specifically, cities situated farther from the equator tend to exhibit lower maximum temperatures compared to those located near the equator. In the Southern Hemispher, there exist a moderate postive correlation (r = .78) between cities located farther from the equator (latitude 0) and their temperatures. Similar to cities in the Northern Hemisphere, cities situated farther from the equator tend to exhibit lower maximum temperatures compared to those located near the equator.
    ## Lat vs Humidity:
        Linear Relationship: There is no significant correlation between latitude and humidity for cities in both the Northern Hemisphere (r = 0.05) and Southern Hemisphere (r = 0.17). This indicates that regardless of the distance from the equator, humidity levels do not show a discernible correlation with latitude.
    ## Lat vs Cloudiness: 
        Linear Relationship: There is no significant correlation between latitude and cloudiness for cities in both the Northern Hemisphere (r = 0.14) and Southern Hemisphere (r = 0.21). This indicates that regardless of the distance from the equator, cloudiness levels do not show a discernible correlation with latitude.
    ## Lat vs Wind Speed: 
        Linear Relationship: There is very weak correlation between latitude and wind speed for cities in both the Northern Hemisphere (r = -0.03) and Southern Hemisphere (r = -0.16). This indicates that regardless of the distance from the equator, wind speed levels do not show a discernible correlation with latitude.
    