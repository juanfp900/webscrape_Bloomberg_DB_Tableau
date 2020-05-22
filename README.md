# Visualize Live Bloomberg Index Values with Tableau

[Link to Tableau View](https://public.tableau.com/profile/juanp5926#!/vizhome/WorldIndexValues/Dashboard1)

# Project Description
Display Index values of world markets with foreign and USD currency comparisons. 
Data that appears in visual starts from May 14, 2020 and updates daily.

# Project Goal
To make it easier for users to view updated Index values daily through the addition of charts, visuals and added colors. 
The bloomberg website makes it difficult to compare index values in its table like format and doesn't
have direct USD, foreign currency comparisons for each individual index. 

# Steps taken 
  - Data is scraped, manipulated and stored within three Pandas dataframes (Americas, EMEA, Asia Pacific).
  - Dataframes are transfered to a Postgres database using the SQLalchemy Python library. 
  - Each dataframe is stored in its own table and modified to prepare for Tableau.
  - Conenction occurs with postgres database and Tableau Desktop.
  - Data is visualized using Tableau.

(There is also code available within the Python file that sends dataframes to a .xlsx file since Tableau Public does not allow connection to a database or allows visuals to be displayed within Tableau Public). 

# Where did the data come from? 

The data came from the following Bloomberg links that show live market data. 
Data was extracted using Python web scraping.
 - [Americas Indexes](https://www.bloomberg.com/markets/stocks/world-indexes/americas)
 - [Europe-Africa-MdiddleEast Indexes](https://www.bloomberg.com/markets/stocks/world-indexes/europe-africa-middle-east)
 - [Asia Pacific Indexes](https://www.bloomberg.com/markets/stocks/world-indexes/asia-pacific)



