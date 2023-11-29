# python-api-challenge
Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

Requirement 2: Compute Linear Regression for Each Relationship
To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.

Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values as you can see in the following image

You should create the following plots:

Northern Hemisphere: Temperature vs. Latitude

Southern Hemisphere: Temperature vs. Latitude

Northern Hemisphere: Humidity vs. Latitude

Southern Hemisphere: Humidity vs. Latitude

Northern Hemisphere: Cloudiness vs. Latitude

Southern Hemisphere: Cloudiness vs. Latitude

Northern Hemisphere: Wind Speed vs. Latitude

Southern Hemisphere: Wind Speed vs. Latitude

Part 2: VacationPy
In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.

Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

To succeed on this deliverable of the assignment, open the VacationPy.ipynb starter code and complete the following steps:

Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.

Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

A max temperature lower than 27 degrees but higher than 21

Wind speed less than 4.5 m/s

Zero cloudiness


Analysis:
Temperature vs. Latitude Linear Regression Plot

-----------------------------------
Observations about linear relationship:Northern Hemisphere
The regression displays a negative relationship between temperature and latitude
In the northern hemisphere, as the latitude increases the distance from the equator increases
As you move away from the equator, the max temperature decreases.

Observations about linear relationship:Southern Hemisphere
The regression displays a sligtly positive relationship between temperature and latitude.
In the southern hemisphere, as the latitude increases the distance from the equator decreases
As you move closer to the equator, the max temperature generally increases.

Humidity vs. Latitude Linear Regression Plot


-----------------------------------------
Observations about linear relationship:Northern Hemisphere
The relationship is slightly positive, though there doesn't appear to be a strong coorelation between humidity and latitude

Observations about linear relationship:Southern Hemisphere
The relationship is slightly positive.
Humidity increases as cities get closer to the equator.

Cloudiness vs. Latitude Linear Regression Plot
---------------------------------------------
Observations about linear relationship:Northern Hemisphere
There does not appear to be a coorelation between latitude and cloudiness.

Observations about linear relationship:Southern Hemisphere
There does not appear to be a coorelation between latitude and cloudiness.

Wind Speed vs. Latitude Linear Regression Plot
-------------------------------------------
Observations about linear relationship: Northern Hemisphere
There does not appear to be a coorelation between latitude and wind speed.

Observations about linear relationship:Southern Hemisphere
There does not appear to be a coorelation between latitude and wind speed.