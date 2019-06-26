# TMDb-5000-Movie-Dataset

###  Project Motivation
The Movie Database provides movie data for public use. Given that major films costing over $100 million to produce can still flop, Analyse this data is more important than ever to the industry. Can we tell the direction of films and changes budget over time? Which languages are most popular ? Can we classify the data to we can predict in the future?
This is a great place to start digging in to those questions, with data on the plot, cast, crew, budget, and revenues of several thousand films.


### Data
The Movie Database provides two datasets:
tmdb_5000_movies.csv (Movie credits data):
- budget
- genres
- homepage
- id
- keywords
- original_language
- original_title
- overview
- popularity
- production_companies
- production_countries
- release_date
- revenue
- runtime
- spoken_languages
- status
- tagline
- title
- vote_average
- vote_count

* tmdb_5000_credits.csv:
- movie_id
- title
- cast
- crew
We will merge the two datasets in order to get all the informations about the actors and the directors of their relative movie.

### The files
- Write A Data Science Blog Postipynb: code notebook
- Write A Data Science Blog Post.html

### The libraries used 
- NumPy
- pandas
- Sklearn / scikit-learn
- Matplotlib (for data visualization)

### A summary of the results: 
Through clustering , we have noticed that, revenue, profit, vote count, budget, popularity, Adventure genre , Action genre have a positive correlation, that mean this attribute tend to increase together.
We can say that Adventure and Action genre tend to Increase revenue, profit, vote count, budget, popularity.

runtime, Drama, History, vote average, War genre, France country , United Kingdom country , Italy country , Sweden country , Denmark country and Germany country have a positive correlation, that mean this attribute tend to increase together. And they have a negative correlation with Comedy genre, United States of America country , Family genre and Animation genre.
We can say that Europe countries tend to watch Drama, History, and War films. While America tends to watch Comedy, Family and Animation films.
