
![ELECTIONS.SBWINNERS](Images/elections.jpg)

#DATA SETS:
•	Super Bowl finals from years 1967 to 2020 from Kaggle: https://www.kaggle.com/timoboz/superbowl-history-1967-2020 
•	US presidential election results from years 1797 - 2009: https://gist.github.com/namuol/2657233 from Lou Acresti’s Github.


#EXTRACT: 
•	Download Kaggle dataset and GitHub dataset as CSVs. 
•	Validate both datasets. 
•	Challenge: Load CSVs into Postgres using PG Admin’s import tool.
•	CSVs will be imported to pandas using from_csv with pandas.

![1st Pull](Images/SB1.jpg)

#TRANSFORM: 
•	Once imported, verify data integrity and create aggregates as necessary. 
•	Drop irrelevant columns in each dataset.
•	Rename appropriate columns for readability. 

![Clean up](Images/CU.jpg)

	Extract the year from (full) date columns. Create new column for “year”. Complete for both data sets. 
•	Once imported, join the tables based on year.  

![Joined](Images/Join.jpg)

#LOAD: 
•	While extracting/loading, read through each dataset and create a Postgres table to load into. 
•	Extract appropriate columns for each dataset—only include relevant columns in analysis.
•	Write the portion of the python script that loads the data into the Postgres database. 
