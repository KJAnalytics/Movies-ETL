# Movies-ETL
ETL project for Movies Hackathon

#Overview:
With the extensive information with regards to movies, budets, ratings, cast/crew, stars, box office returns available, Amazing Prime has requested a project be initiated to sort through the sources of data available and create a databse with tables to assess the information.  Focus for the project is data from Wikipedia from 1990 to 2018.

#Technologies and sources utilized for the project include:
- Wikipedia, Kaggle, and MovieLens to collect source data as .csv or JSON formats for the analysis.
- Jupyter Notebook and Python utilizing Pandas, json, numpy, time, requests, sqlalchemy-create_engine feature, psycopg2, and importing passwords from config using .gitignore protocols for security.
- PostgresSQL and sql to create the database in pgAdmin.

#Deliverables 
- Create an ETL Function to read in the three datasets from Wiki, Kaggle, and Movie Lens creating Panda dataframes.
- Transform and clean the data to include targeted datasets and remove data with references to adult content. Finally link the dataframes using joins.
- Using the transformed dataset - create a SQL database in pgAdmin.

Key Learnings:
- When working with multiple datasets in different formats, how the data is pulled in initially sets the tone for the cleaning process.  
- Password protections are critical when accessing on line data sets and the use of config and .gitignore files are imperative are maintaining security of your unique identifiers when posting to GitHub or other repository sources.
- Directory of files and locations are crucial.  I found that maintaining an offcode diagram of .csv, .ipynb, and folder structure helps when needing to link to this files in your code.




