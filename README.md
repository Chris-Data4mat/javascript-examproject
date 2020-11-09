# javascript-examproject
My JavaScript exam project for the EC JavaScript Developer course fall semester 2020.

An explanation to why the forecast times varies between 11:00 and 13:00 local time.

The weather data from the openweathermap.org is provided in UTC time which means that when data is collected for a timezone that is not evenly devisable by 3 it will not give you a reading for 12 noon in the local timezone. Hence the local time will vary between 11:00 and 13:00 depending on which is closest to 12 noon. Even half hours are supported but not 15 minutes.
