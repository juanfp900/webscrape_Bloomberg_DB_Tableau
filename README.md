# Visualize Live Bloomberg Index Values with Tableau

[Link to Tableau View!](https://public.tableau.com/profile/juanp5926#!/vizhome/WorldIndexValues/Dashboard1)

# Project Description
Display the index changes from various markets around the world in an intuative way. 
Live data was scraped, stored in dataframes and sent to Postgres database using the SQLalchemy Python library. 
Data was queried and modified in PgAdmin4 to prepare for Tableau. The database was then conencted with Tableau and
filters, formats and calculated values, parameters were added to visualize the data as shown in the link above


# Where did the data come from? 

The data came from the following Bloomberg links that show live market data. 
Data was extracted using Python web scraping.
[Americas Indexes](https://www.bloomberg.com/markets/stocks/world-indexes/americas)
[Europe-Africa-MdiddleEast Indexes](https://www.bloomberg.com/markets/stocks/world-indexes/europe-africa-middle-east)
[Asia Pacific Indexes](https://www.bloomberg.com/markets/stocks/world-indexes/asia-pacific)
live data was scraped and sent to Postgres database using the SQLalchemy Python library by connecting to Postgres database. 
The data was viewed using using PGAdmin4

