# NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING![image](https://user-images.githubusercontent.com/114327970/219944839-09606aa6-aa2a-4ca8-8cbd-46da512188ec.png)
📖 Data Summery
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Fixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset. Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

show_id : Unique ID for every Movie / Tv Show

type : Identifier - A Movie or TV Show

title : Title of the Movie / Tv Show

director : Director of the Movie

cast : Actors involved in the movie / show

country : Country where the movie / show was produced

date_added : Date it was added on Netflix

release_year : Actual Release Year of the movie / show

rating : TV Rating of the movie / show

duration : Total Duration - in minutes or number of seasons

listed_in : Genere

description: The Summary description




DATA PIPELINE:
Know Your Data: The first step in this project was to examine the various features of the dataset, understand the structure of the data and identify any patterns or trends. We looked at the shape of the data, the data types of each feature, and a statistical summary.
Exploratory Data Analysis: We conducted an exploratory analysis of the data to identify patterns and dependencies, and to draw conclusions that would be useful for further processing.
Data Cleaning: We checked for duplicated values in the dataset and then addressed any null values and outliers by imputing empty strings and dropping some of the null rows.
Textual Data Preprocessing: We used techniques such as stop word removal, punctuation removal, conversion to lowercase, stemming, tokenization, and word vectorization to prepare the textual data for clustering. We also used Principal Component Analysis (PCA) to handle the curse of dimensionality.
Cluster Implementation: We used K-Means and Agglomerative Hierarchical clustering algorithms to cluster the movies and determine the optimal number of clusters.
Content-Based Recommendation System: We built a content-based recommendation system using the similarity matrix obtained from cosine similarity, which will provide the user with 10 recommendations based on the type of movie/show they have watched.

