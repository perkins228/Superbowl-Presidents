
![ELECTIONS.SBWINNERS](Images/elections.jpg)

# DATA SETS:

• Super Bowl finals from years 1967 to 2020 from Kaggle: https://www.kaggle.com/timoboz/superbowl-history-1967-2020</br>
• US presidential election results from years 1797 - 2009: https://gist.github.com/namuol/2657233 from Lou Acresti’s Github.


## EXTRACT: 
• Download Kaggle dataset and GitHub dataset as CSVs.</br>
• Validate both datasets. </br>
• Challenge: Load CSVs into Postgres using PG Admin’s import tool.</br>
• CSVs will be imported to pandas using from_csv with pandas.</br>

![Images/SB1.jpg](Images/SB1.jpg)

## TRANSFORM: 
• Once imported, verify data integrity and create aggregates as necessary. </br>
• Drop irrelevant columns in each dataset.</br>
• Rename appropriate columns for readability. </br>

![Clean up](Images/CU.jpg)

• Extract the year from (full) date columns. Create new column for “year”. Complete for both data sets. </br>
• Once imported, join the tables based on year.  

![Joined](Images/Join.jpg)

## LOAD: 
• While extracting/loading, read through each dataset and create a Postgres table to load into. </br>
• Extract appropriate columns for each dataset—only include relevant columns in analysis.</br>
• Write the portion of the python script that loads the data into the Postgres database. </br>
