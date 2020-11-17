# javascript-examproject
My JavaScript exam project for the EC JavaScript Developer course fall semester 2020.

## __Requirements__  
-Must use live data and function properly  
-Use of MVC prefered  
  
### Required information for each city:  
-City name  
-Country  
-Currency  
-Exchange rate (vs SEK)  
-Input amount to exchange and the calculated amount in the other currency.  

### Weather, 5 day forecast with thefollowing information:
-Description and/or icon  
-Weekday  
-Temperature at or around 12 (noon)


An explanation to why the forecast times varies between 11:00 and 13:00 local time.

The weather data from the openweathermap.org is provided in UTC time which means that when data is collected for a timezone that is not evenly devisable by 3 it will not give you a reading for 12 noon in the local timezone. Hence the local time will vary between 11:00 and 13:00 depending on which is closest to 12 noon. Even half hours are supported but not 15 minutes.
