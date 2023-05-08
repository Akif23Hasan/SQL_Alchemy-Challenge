# SQL_Alchemy-Challenge - Climate Analysis and Flask API Design
This challenge involves analysing a climate database using Python, SQLAlchemy ORM queries, Pandas, and Matplotlib. After whihc the project requires the designing process of a Flask API based on the queries that were developed.

## Requirements
* Download the 2 CSV files and sqlite file provided in the Resources folder.
* Python v3.10.9
* Install SQL Alchemy
* Install Numpy 
* Install Pandas
* Install Datetime
* Install Matplotlib


## Part 1: Analys and Explore the Climate Data
In this section, we analysed and explored the climate data using Python, Pandas, and Matplotlib. The following tasks were performed:

1) Perform a precipitation analysis and a station analysis.
2) For the precipitation analysis:
3) Find the most recent date in the dataset.
4) Using that date, get the previous 12 months of precipitation data by querying the previous 12 months of data.
5) Load the query results into a Pandas DataFrame.
6) Sort the DataFrame values by "date".
7) Plot the results using the DataFrame plot method.
8) Use Pandas to print the summary statistics for the precipitation data.
9) Design a query to calculate the total number of stations in the dataset.
10) Design a query to find the most-active stations.
11) Using the most-active station id, calculate the lowest, highest, and average temperatures.
12) Design a query to get the previous 12 months of temperature observation (TOBS) data.
13) Filter by the station that has the greatest number of observations.
14) Query the previous 12 months of TOBS data for that station.
15) Plot the results as a histogram with bins=12.

## Part 2: Design Your Climate App
In this section, we design a Flask API based on the queries developed in Part 1. The following routes were created:

* Start at the homepage.
* List all the available routes.
* JSON List for: 
1) /api/v1.0/precipitation
2) /api/v1.0/stations
3) /api/v1.0/tobs
4) /api/v1.0/<start>
5) /api/v1.0/<start> and /api/v1.0/<start>/<end>

Both responses for 4 and 5 returend a list of the minimum temperature, the average temperature, and the maximum temperature for a specified start or start-end range.

## References
Menne, M.J., I. Durre, R.S. Vose, B.E. Gleason, and T.G. Houston, 2012: An overview of the Global Historical Climatology Network-Daily Database. Journal of Atmospheric and Oceanic Technology, 29, 897-910, https://doi.org/10.1175/JTECH-D-11-00103.1Links to an external site., measurements converted to metric in Pandas.

