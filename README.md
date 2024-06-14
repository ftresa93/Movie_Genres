# Movie Genres Data Analysis Project

### Table of Contents

- [Project Objective](#project-objective)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Findings](#findings)
- [References](#references)

### Project Objective: 

The objective of this project is to analyze movie genre data, gain insights, and address the following research questions (Q) and hypotheses (H).

### Data Sources:

The primary dataset used for the analysis "imdb_movies.csv" contains information about 4,803 movies. It provides a wide range of details about each movie, including budget, genres, production companies, release date, revenue, runtime, language, popularity, and more.

### Tools Used:

- Jupyter Notebook (Python) 

### Data Processing:

#### Data Import:

The imdb_movies dataset was imported into Python- Jupyter Notebook.

#### Data Cleaning and Preparation: 

- Removing Duplicates
- Handling Missing and Null Values
- Standardizing Data types
- Splitting data to analyze based on genres

#### Exploratory Data Analysis: 

Research Questions (Q)
1. Which genres are the most common(no. of movies made)?
2. Which genres have the highest avg. budget and revenue?
3. Which genres have the highest avg. popularity?
4. Which genres have the highest number of movies with a voting avg. >=8?

Research Hypothesis (H)
1. The best movie acc to vote avg. return high profit and revenue.
2. The best movies acc. to popularity return high profit and revenue.
3. Highly budgeted movies return high revenue and profit.
4. Highly budgeted movies have a high popularity.
5. The profit for each Genres by release year
 
### Findings:

- Common Genres: Drama is the most common genre, with the highest number of movies.
- Budget and Revenue: Adventure has the highest average budget and revenue. It also leads in average profit.
- Popularity: Adventure is the most popular genre, followed by Science Fiction.
- Voting Average: Drama has the highest number of movies with a voting average of >=8.
- Vote Average Correlation: The best movies according to voting average do return high profit and revenue. The correlation between voting average and profit/revenue is positive but not very strong.
- Popularity Correlation: The best movies according to popularity return high profit and revenue, showing a strong positive correlation.
- Budget Correlation: Highly budgeted movies tend to return high revenue, profits and have high popularity, the correlation is positive yet not very strong.
  
### References:

1. Kaggle-[Movie Dataset: Budgets, Genres, Insights](https://www.kaggle.com/datasets/utkarshx27/movies-dataset)
2.  Analyst builder
