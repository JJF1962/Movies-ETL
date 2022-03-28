# Movies-ETL
##  Objective
The objective of this module was to learn how to use the Extract; Transform; Load (ETL) process to create data pipelines, an essential skill for Data Analysis.
as better detailed as follows:
##  Resources and main learning points
As described in the section 8.0.2 it was learned the following during this module and challenge 8
* Create an ETL pipeline from raw data to a SQL database.
* Extract data from disparate sources using Python.
* Clean and transform data using Pandas.
* Use regular expressions to parse data and to transform text into numbers.
* Load data with PostgreSQL.  (pgAdmin).
* In summary it was used Python, Pandas, ETL process, code refactoring, Postgress SQL(pgAdmin) and Git Hub.
##  Results
The resorces learned mentioned in the previous point were learned and allow us to execute four Deliveries:
* Deliverable 1: Write and ETL Function to read three data files 
We used the starter code  ETL-function-test.ipynb, renamed ETL_function_test.ipynb and we refactor de code in the execution of the challenge, firstly it was created a function to read in the three files and give it a name, in the second step consisted in to read the Kaggle Metadata and MovieLens ratings CSV files as Panda Dataframes, in the Step 3 open the Wikipedia JSON file and use the jason.load() function to convert it in to a raw data. In the following step it was used a code provided to return three DataFrames; in the step 6 we used the variables provide to create a path to Wilkipedia data, the Kaggle metadata and MoviLens rating data files, step 7 set the three variables equal to the function created in Step1 , step 8 Dataframes form the return statementand step 9-11 that all three files were converted to a tata frame as shown in the three figures below

The wiki_movies Dataframes

![this is an image](https://github.com/JJF1962/Movies-ETL/blob/main/Resources/The%20wiki_movies_df.PNG)

The Kaggle_metadata DataFrame

![this is an image](https://github.com/JJF1962/Movies-ETL/blob/main/Resources/The%20kaggle_metadata.PNG)

The ratings DataFrame

![this is an image](https://github.com/JJF1962/Movies-ETL/blob/main/Resources/The%20ratings%20Dataframe.PNG)

* Deliverable 2: Extract and transform the Wilkipidia Data
It was used Python, Pandas, the ETL process and code refactoring, extract and transform the Wilkipidia data to merge it the Kaggle metadata; while extracting the IMDb IDs using aregular expression string and dropping duplicates, use a try-except block to catch errors. As you can see in the figures below wiki_movies_df with the TV shows are filtered  and the cleaned Wikipedia data is converted to a Pandas

![this is an image](https://github.com/JJF1962/Movies-ETL/blob/main/Resources/wiki_movies_df.PNG)

* Deliverable 3: Extract and transfor the Kaggle Data
In the execution of this deliverable it was used Phyton, Pandas, the ETL process, and code refactoring, extract and transform the Kaggle metadata and MovieLens rating data, then converteded data into separate Dataframes, aditionally it was merged the Kaggle metadata DataFrame with the Wikipedia movies DataFrame, to finalizes, it was merged  Th MoviLens Rating and DataFrame with the movies_df DataFrame to create the movies_with_ratings_df as shown below:

![this is an image](https://github.com/JJF1962/Movies-ETL/blob/main/Resources/movies_with_ratings_df.PNG)

* Deliverable 4: Create the Movie Database
It was copied  ETL_clean_kaggle_data.ipynb rename the file ETL_create_database.ipynb, I used Vs code to storage my config import db_password, the use of pgAdmin, was very challenging and took long time to run the long files also in my Jupyter Notebook. In the PgAdmin I deleted the tables and let the system reloaded and the data runned more complete,  PgAdmin run out of memory. 
movies_df DataFrame and MovieLens rating CSV data to a SQL database.

![this is an image](

##  Summary & Conclusion
