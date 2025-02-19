# Movies-ETL

## I. Overview of Project

### Background
The Amazing Prime Video company wants to determine which low budegt movies being released will become popular to buy streaming rights at a bargain. They decide to hold a hackaton for this and Britta has been tasked with providing the datasets. They loved her work but now they want to keep it updated on a daily basis.

### Objective
Britta needs help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. We need to refactor the code to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.


## II. Analysis and Results

### A. Writing an ETL Function to Read Three Data Files

**wiki_movies_df**

![](analysis/1.wiki_movies_df.PNG)

**kaggle_metadata_df**

![](analysis/1.kaggle_metadata_df.PNG)

**ratings_df**

![](analysis/1.ratings_df.PNG)



### B. Extracing and Transforming the Wikipedia Data

**wiki_movies_df**

![](analysis/2.wiki_movies_df.PNG)


**wiki_movies_df.columns**

![](analysis/2.wiki_movies_df.columns.PNG)


### C. Extracing and Transforming the Kaggle Data

**movies_with_ratings**

![](analysis/3.movies_with_ratings.PNG)

**movies_df**
![](analysis/3.movies_df.PNG)



### D. Creating the Movie Database 

**movies_query**

![](Resources/movies_query.PNG)

**ratings_query**

![](Resources/ratings_query.PNG)

