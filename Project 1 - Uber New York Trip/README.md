## Uber TLC FOIL Response

This file contains data on over 4.5 million Uber pickups in New York City from April to September 2014, and 14.3 million more Uber pickups from January to June 2015. Trip-level data on 10 other for-hire vehicle (FHV) companies, as well as aggregated data for 329 FHV companies, is also included. All the files are as they were received on August 3, Sept. 15 and Sept. 22, 2015. 

FiveThirtyEight obtained the data from the [NYC Taxi & Limousine Commission (TLC)](http://www.nyc.gov/html/tlc/html/home/home.shtml) by submitting a Freedom of Information Law request on July 20, 2015. The TLC has sent us the data in batches as it continues to review trip data Uber and other HFV companies have submitted to it. TLC records requests can be made [here](http://www.nyc.gov/html/tlc/html/passenger/records.shtml).

In New York City, the Taxi & Limousine Commission (TLC) licenses drivers and vehicles to carry fare-paying passengers. Having a TLC driver's license (now known as the universal license), grants drivers the authority to transport passengers using a TLC licensed vehicle. Unlike in other cities, you need a special license from the TLC to drive with Uber in New York City.

In files about uber-trip-data in NYC from April-September 2014, i.e. `uber-raw-data-apr14.csv`, `uber-raw-data-may14.csv`, etc. The files are separated by month and each has the following columns:

Header | Definition
---|---------
`Date/Time` | The date and time of the Uber pickup
`Lat` | The latitude of the Uber pickup. The measurement of distance north or south of the Equator
`Lon` | The longitude of the Uber pickup
`Base` | The TLC base company code affiliated with the Uber pickup

The globe is split into an imaginary 360 sections from both top to bottom (north to south) and 180 sections from side to side (west to east). The sections running from top to bottom on a globe are called longitude, and the sections running from side to side on a globe are called latitude.
Every location on earth has a global address. Because the address is in numbers, people can communicate about location no matter what language they might speak. A global address is given as two numbers called coordinates. The two numbers are a location's latitude number ("Lat") and its longitude number("Lon").. 

The `Base` codes are for the following Uber bases:

Base Code | Base Name
---|---------
B02512 | Unter
B02598 | Hinter
B02617 | Weiter
B02682 | Schmecken
B02764 | Danach-NY
B02765 | Grun
B02835 | Dreist
B02836 | Drinnen

There is a file `uber-raw-data-janjune-15.csv.zip`. This about uber-trip-data in NYC from January-June 2015, the details of the columns in this file is:

Header | Definition
---|---------
`Dispatching_base_num` | The [TLC base company](http://www.nyc.gov/html/tlc/html/industry/base_and_business.shtml) code of the base that dispatched the Uber
`Pickup_date` | The date and time of the Uber pickup
`Affiliated_base_num` | The [TLC base company](http://www.nyc.gov/html/tlc/html/industry/base_and_business.shtml) code affiliated with the Uber pickup
`locationID` | The pickup location ID affiliated with the Uber pickup

The file `Uber-Jan-Feb-FOIL.csv` contains aggregated daily Uber trip statistics in January and February 2015.
