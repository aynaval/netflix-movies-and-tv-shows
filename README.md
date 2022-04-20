# Project Name : Netflix movies and TV shows 

#### -- Project Status: Completed

## Project Intro/Objective
The purpose of this project is to perform unspervised Ml to categorize the data into optimal clusters.


### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling

### Technologies
* Python


## Project Description
The purpose of the project is to do unsupervised machine learning on the dataset to find the optimal clusters. Dataset has  7787 rows and 12 column. The columns are namely :
1. show_id : Unique ID for every Movie / Tv Show
2. type : Identifier - A Movie or TV Show
3. title : Title of the Movie / Tv Show
4. director : Director of the Movie
5. cast : Actors involved in the movie / show
6. country : Country where the movie / show was produced
7. date_added : Date it was added on Netflix
8. release_year : Actual Releaseyear of the movie / show
9. rating : TV Rating of the movie / show
10. duration : Total Duration - in minutes or number of seasons
11. listed_in : Genere
12. description: The Summary description 

EDA is done on Dataset to find different patterns and insights from the data. There are no duplicate columns in the dataset. There are missing values in director , cast,date_added and country columns. Missing values in director caolumn is imputed with 'unknown', country column with mode of the column and caste with 'unkown'. Missing values in date_added are deleted. Columns created , added_year,added_month and added_month_name from date_added column . age_rating is crreatd based on rating column. Insights from :
* It is evident that there are more movies on Netflix than TV shows.
* The 'TV-MA' rating is used in the majority of the film. The TV Parental Guidelines provide a "TV-MA" classification to a television programme that is intended solely for mature audiences.
* The number of movies on Netflix is growing significantly faster than the number of TV shows.
* It appears that Netflix has focused more attention on increasing Movie content that TV Shows. Movies have increased much more dramatically than TV shows.
* Because of covid-19, there is a significant drop in the number of movies and television episodes produced after 2019.
* US, India and UK are the top producers of content.
* The majority of the films are between 85 and 120 minutes long, which is appropriate.
* Those movies that have a rating of NC-17 have the longest average duration.
* It is evident that international tv shows, tv dramas, and tv comedies are the top three genres with the most content on Netflix.
* The Directors who produce the most material are Raul Campos and Jan Sutler. They work in 18 movies as a director.

Data was transformed from listed in and rating columns to binary values. Multilabelbinarizer is used allows us to encode multiple labels per instance. silhouette score and elbow method are used to find the optimal clusters, which is 20 clusters with silhouette score of  0.88. t-SNE method to reduce the dimension so, we can plot the clusters in two-dimensional space.




## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- data visualization

## Getting Started

1. Clone this repo. 
2. Raw Data is being kept [here](https://github.com/aynaval/netflix-movies-and-tv-shows/blob/main/NETFLIX_MOVIES_AND_TV_SHOWS_CLUSTERING.ipynb) within this repo.
3. Data processing/transformation, EDA and modeling scripts are being kept [here](https://github.com/aynaval/netflix-movies-and-tv-shows/blob/main/netflix_titles.csv)






  
