## Project Overview

This project is aimed at generating insights to help Microsoft open a new movie studio.The project explores the types of films that are currently doing the best at the box office. The findings are the translated into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. 

    ##Research Questions
    1. What movie genres have perfomed the best for all time?
    2. Is movie production budget directly related to the popularity/gross revenue? 
    3. Which cast and crew are associated with the most popular movies?


### The Data

Dataset used:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

API calls made to TMDB to get genre movie names associated with with genre_ids.

* imdb.title.basics
* imdb.title.ratings
* bom.movie_gross


### Key Points

1. tmdb.movies.csv.gz and [imdb.title.basics.csv.gz merged with imdb.title.ratings.csv.gz on the 'tconst' column] datasets were used to discover the best performing movie genres of all time. Movies genres were grouped by ratings and vote count. Barh plots rendered.

2. tn.movie_budgets.csv.gz and bom.movie_gross.csv.gz datasets was used to check for correlation between movie production budget and it's gross revenue. A scatter plot was rendered.

3. imdb.title.principles.csv.gz, imdb.title.akas.csv.gz, and imdb.name.basics.csv.gz were used to investigate the cast and crew are associated with the most popular movies. A barh was rendered. 

###Reccomendations

1. Based on the analysis, Microsoft should source more movies with a bias for Romance, Drama, and Animation genres for their new movie studio.

2. Microsoft new movie studio should make block buster films (i.e. high budget movies) since there is a direct relationship between production budget and gross revenues raked in by such movies

3. The movies should star top movie principals especialy: Guy Hendric Dyas Tim Miller Jeffrey Ford Lauren Shuler Donner Hideki Ikari Atsushi Wada Mizuki Sashide Yuri Hane Rikako Sakata Nako Mizusawa


## Summary

Microsoft's new movie studio should be of blockbuster movies that have a blend of Romance, Drama, Family, and Animation genres. The movies should strive to have either Guy Hendric Dyas, Tim Miller, Jeffrey Ford, Lauren Shuler Donner, Hideki Ikari, Atsushi Wada, Mizuki Sashide, Yuri Hane, Rikako Sakata, Nako Mizusawa in their cast. 
