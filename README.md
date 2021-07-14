# incubyte_assesment
Python ETL to seperate records from each country to seperate tables

# dataflow
Source: source.txt file -- Has records with '|' seperated columns <br />
Target: SQLite database with seperate tables for each country records <br/><br/>

# Transformation process
1)Reading the source file and store it as Pandas Dataframe <br />
2)Cleaning the data <br />
3)Creating a new SQLite database for target <br />
4)Creating new table for each country in record <br />
5)Load the records to specific country table <br />



