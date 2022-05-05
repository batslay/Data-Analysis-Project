## NYC Citibike Trips
Citi Bike is New York City ’ s bike-sharing system with thousands of bikes at hundreds of stations and is available 24/7 every day of the year. Citi Bike is a convenient solution for quick trips around the City. Users could unlock a bike at any station and ride wherever they want.
## Dataset Description 
The dataset that is used comes from bigquery public data with table ID "bigquery-publicdata:new_york_citibike.citibike_trips `". The dataset contains information about NYC Citibike trips from July 1, 2013, to May 31, 2018. The dataset consists of 58,937,715 rows and 16 columns.
## How To Do: 
1. Open the link https://console.cloud.google.com/ on the browser and sign in using a Gmail account
2. Select "Navigation menu" -> "BigQuery"
3. Then, select a project (if you already have a project), create a project with the desired name, and then click create (if you don't have a project).
4. In the Explorer section, search "new_york_citibike" to find the dataset, here I use the dataset with the ID "bigquery-public-data.new_york_citibike" which has been provided by bigquery-public-data
5. The new_york_citibike dataset contains 2 tables, namely the "citibike_stations" and "citibike_trips" tables, in this project I focus on analyzing by querying the "citibike_trips" table.
6. Then, after performing SQL queries, do exploration using Google Data Studio to facilitate data analysis with visualization by clicking "EXPLORE DATA" -> "Explore with Data Studio"
