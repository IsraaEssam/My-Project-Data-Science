# Movies Analysis 🎬

## Overview

This project explores movie data to identify trends and relationships related to movie budgets, revenues, directors, and audience ratings.
The analysis was performed using Python and focuses on data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization.

## Questions

The analysis investigates the following questions:

1. What are the movies with the highest budgets?
2. What are the movies with the highest revenues?
3. Is there a correlation between movie budget and revenue?
4. Who directed the movie with the highest revenue?
5. Which directors have directed the largest number of movies?
6. Which directors have the highest total revenue?
7. What are the movies with the highest average ratings?
8. Who directed the movies with the highest average ratings?

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statistics / Correlation Analysis
* Jupyter Notebook

## Dataset

The project uses a movie dataset containing information such as:

* Movie title
* Budget
* Revenue
* Director
* Popularity
* Vote count
* Vote average
* Release year
* Runtime
* Additional movie information

## Data Preparation

The dataset was inspected and cleaned before performing the analysis.

Main preprocessing steps included:

* Inspecting the dataset structure and data types.
* Checking missing values.
* Removing unnecessary columns that were not required for the analysis.
* Removing records with missing IMDb IDs.
* Removing records with missing director information.
* Investigating missing values in cast and genre information.
* Removing the `cast` and `genres` columns where missing values affected the analysis.
* Checking movie titles for repeated names and potential duplicates.

## Exploratory Data Analysis

The analysis explored relationships between movie characteristics and financial performance.

### Budget and Revenue

The relationship between movie budget and revenue was examined using correlation analysis.

The calculated correlation coefficient was approximately **0.735**, indicating a relatively strong positive relationship between movie budget and revenue in this dataset.

### Highest Budget

The movie with the highest budget in the analyzed dataset was:

**The Warrior's Way — $425,000,000**

### Highest Revenue

The movie with the highest revenue in the analyzed dataset was:

**Avatar — $2,781,505,847**

### Directors

The analysis examined directors based on:

* Number of movies directed
* Directors associated with the highest-revenue movies
* Directors associated with highly rated movies

**Woody Allen** had the largest number of movies in the dataset, with **45 movies**.

### Highest-Rated Movie

The movie with the highest `vote_average` in the analyzed dataset was:

**The Story of Film: An Odyssey**

Its director was **Mark Cousins**.

## Key Insights

* Higher movie budgets tend to be associated with higher revenues, with a correlation of approximately **0.735**.
* *Avatar* generated the highest revenue among the movies analyzed.
* *The Warrior's Way* had the highest recorded budget in the dataset.
* Woody Allen had the largest number of movies among the directors analyzed.
* Movie ratings and financial performance were explored through descriptive and comparative analysis.

## Project Structure

```text
Movies-Analysis/
│
├── movies_analysis_Israa.ipynb
├── tmdb-movies.csv
└── README.md
```

## Future Improvements

Possible improvements to this project include:

* Calculate total revenue for each director using group-by analysis.
* Investigate the effect of missing or zero budget/revenue values.
* Perform deeper statistical analysis.
* Create additional visualizations for the main findings.
* Explore trends by release year and movie genre.
* Build predictive models in a future machine learning project.

## Author

**Israa Essam**
