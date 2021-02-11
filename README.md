# python-api-challenge
This is a two part project, WeatherPy and VacationPY.

Random coordinates are generated and the current weather is pulled from the OPenWeatherMap API.
The data is then used to narrow down your preffered vacation destination.

### WeatherPy
This script utilizes the python library, scipy, and JSON to make API calls to retrieve weather data.
All information is used to create a respresentative model with a series of scatter plots of weather data
versus the latitude of the city.  A linear regressins is then run between the Northern and Southern hemispheres.

### VacationPy
With all of the data gathered a desired location is selected by setting a preffered temperature, humidity, cloudiness, and wind speed.
Using JSON requests with the GMAPS api the closest hotels are found.
