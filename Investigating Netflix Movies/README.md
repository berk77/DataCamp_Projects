# Investigating Netflix Movies
In this project, the duration of the movies on Netflix is examined. The question that is tried to be answered here is whether the movie durations are getting shorter and shorter. To find out, first of all, all movie durations are visualized by years. Although it is perceived that the durations are shortening at first glance, it is understood that the films should be examined according to their genres in order to reach a clearer conclusion. In order to achieve the desired result, visuals are presented in which genres such as "Children", "Stand-Up", and "Documentaries" can be distinguished.

## Data
<a href="datasets/netflix_data.csv"> Netflix_data.csv </a> data is used in the project. The dataset consists of data from movies and TV shows. The data are as described below.

* show_id      : Unique ID for every Movie / Tv Show
* type         : Identifier - A Movie or TV Show
* title        : Title of the Movie / Tv Show
* director     : Director of the Movie
* cast         : Actors involved in the movie / show
* country      : Country where the movie / show was produced
* date_added   : Date it was added on Netflix
* release_year : Actual Release year of the move / show
* duration     : Total Duration - in minutes or number of seasons
* description  : The summary description
* genre        : Genre

## Results

As can be seen, non-typical genres such as children's films and documentaries are all clustered in the lower half of the plot. In other words, if the analysis is made without distinguishing these genres, it may be felt that the movie durations are getting shorter and shorter. Although the predictions are proven to be correct, the answer to the main question cannot be reached without additional analysis.

![](Investigating%20Netflix%20Movies/images/scatter.png)
