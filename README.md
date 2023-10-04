# ExploratoryDataAnalysis_PropertyMarket

In this Data Analyst Portfolio project, I have scraped the Otodom website data using the Bright Data tool and then load the data into the Snowflake database. 

In the Snowflake database, I analyzed, cleaned, and transformed data and finally build reports to answer some of the most common questions related to the property market in Poland. 

Part 1 - scrape data from otdom and imported into snowflake to scrape the data we used bright data 
in snowflake we had to flatten the data because it was in JSON format then we loaded it into table in snowflake 

Part 2 - I did some data transformations using python and geocode API 
the location which was in latitude and longitude format was transformed to proper address 
and loaded that into another table in snowflake 

I did other transformation for another field which was title which was in polish 
I transformed it into english using google translater API 
loaded the english title in another table in snowflake


Part 3 - Then we joined all the three tables and did cleaned the data , analysed it and build reports using sql 



