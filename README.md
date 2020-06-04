# Ann Arbor Weather Data Visualization

Used real world weather data to display the minimum and maximum temperature for a range of dates using line graphs. Additionally, demonstrated procedure of composite charts, by overlaying a scatter plot of record breaking data for a given year.

An NOAA dataset has been stored in the file `data/C2A2_data/BinnedCsvs_d400/fb441e62df2d58994928907a91895ec62c2c42e6cd075c2700843b89.csv`. The data comes from a subset of The National Centers for Environmental Information (NCEI) [Daily Global Historical Climatology Network](https://www1.ncdc.noaa.gov/pub/data/ghcn/daily/readme.txt) (GHCN-Daily). The GHCN-Daily is comprised of daily climate records from thousands of land surface stations across the globe.

Each row in the datafile corresponds to a single observation.

Variables:
* **id** : station identification code
* **date** : date in YYYY-MM-DD format (e.g. 2012-01-24 = January 24, 2012)
* **element** : indicator of element type
    * TMAX : Maximum temperature (tenths of degrees C)
    * TMIN : Minimum temperature (tenths of degrees C)
* **value** : data value for element (tenths of degrees C)
 
1. Plotted Line graph of the record high and record low temperatures by day of the year over the period 2005-2014. The area between the record high and record low temperatures for each day is shaded.
2. Overlaid a scatter of the 2015 data for any points (highs and lows) for which the ten year record (2005-2014) record high or record low was broken in 2015.
3. Removed leap days (i.e. February 29th) from the dataset for the purpose of this visualization.
4. Used color scheme that takes into account accessibility for people who are not as perceptive to colors as others!
5. Added hovering over the points in the plot, to allow one to see the exact reading being pointed over on the bottom right.
