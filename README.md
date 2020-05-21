# Visualize Live Bloomberg Index Values with Tableau

[Link to Tableau View](https://public.tableau.com/profile/juanp5926#!/vizhome/WorldIndexValues/Dashboard1)

# Project Description
Display world index values of various world markets. 
Data that appears in visual starts from May 14, 2020 and updates daily

# Steps taken
Live data was scraped (BeautifulSoup library), manipulated, stored in Pandas dataframes and sent to Postgres database using the SQLalchemy Python library. 
Data was queried and modified in PgAdmin4 using SQL to prepare for Tableau.
The database was then conencted to Tableau Desktop.
(There is also code available within the Python file that sends dataframes to a .xlsx file since Tableau public does not allow connection to a database). 

# Where did the data come from? 

The data came from the following Bloomberg links that show live market data. 
Data was extracted using Python web scraping.
 - [Americas Indexes](https://www.bloomberg.com/markets/stocks/world-indexes/americas)
 - [Europe-Africa-MdiddleEast Indexes](https://www.bloomberg.com/markets/stocks/world-indexes/europe-africa-middle-east)
 - [Asia Pacific Indexes](https://www.bloomberg.com/markets/stocks/world-indexes/asia-pacific)



