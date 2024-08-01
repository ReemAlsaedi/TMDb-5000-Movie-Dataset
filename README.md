# TMDb-5000-Movie-Dataset
## Problem Statement:

The objective is to analyze the TMDB 5000 Movie Dataset to uncover trends and patterns in the film industry. Key questions to address include: How have film budgets and directions changed over time? Which languages are the most popular? Can we classify and predict future film success based on historical data? This analysis aims to provide actionable insights that could inform future film production and marketing strategies.

## Dataset Overview:

The TMDB 5000 Movie Dataset comprises two primary datasets: tmdb_5000_movies and tmdb_5000_credits. The tmdb_5000_movies dataset includes information such as budget, genres, homepage, id, keywords, original language, original title, overview, popularity, production companies, production countries, release date, revenue, runtime, spoken languages, status, tagline, title, vote average, and vote count. The tmdb_5000_credits dataset provides details on movie_id, title, cast, and crew. This comprehensive dataset offers insights into various aspects of films, including their production details, financial performance, and popularity.


## Results:

By the end of this project, I will have performed a thorough analysis of the movie dataset, including examining changes in film budgets and trends over time, identifying popular languages, and applying feature scaling in preparation for dimensionality reduction techniques. The insights gained will help understand industry trends and predict future film performance, contributing to a data-driven approach in the film industry.


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
