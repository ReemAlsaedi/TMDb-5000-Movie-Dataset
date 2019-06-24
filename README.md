# TMDb-5000-Movie-Dataset

### Project Overview 
The Movie Database provides movie data for public use. Given that major films costing over $100 million to produce can still flop, Analyse this data is more important than ever to the industry. Can we tell the direction of films and changes budget over time? Which languages are most popular ?
Can we classify the data to we can predict in the future?
This is a great place to start digging in to those questions, with data on the plot, cast, crew, budget, and revenues of several thousand films.

### Data
The Movie Database provides two datasets:
tmdb_5000_movies (Movie credits data):
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

* tmdb_5000_credits:
- movie_id
- title
- cast
- crew
We will merge the two datasets in order to get all the informations about the actors and the directors of their relative movie.

### What will I need to install?
It is highly recommended that you use the project workspace to complete and submit this project. Should you decide to download the data, you will need to remove it from your computer via the agreement with Arvato Bertlesmann. If you choose to use your machine to complete this project, below are a list of the requirements.

This project uses Python 3 and is designed to be completed through the Jupyter Notebooks IDE. It is highly recommended that you use the Anaconda distribution to install Python, since the distribution includes all necessary Python libraries as well as Jupyter Notebooks. The following libraries are expected to be used in this project:
- NumPy
- pandas
- Sklearn / scikit-learn
- Matplotlib (for data visualization)

