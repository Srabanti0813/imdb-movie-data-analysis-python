# IMDb Movie Data Analysis Using Python

An end-to-end data analysis project using IMDb movie data to explore movie ratings, genres, directors, actors, votes, duration, and gross income.

## Project Overview

This project uses Python to clean, analyze, and visualize IMDb movie data. It answers business-focused questions and identifies patterns related to movie performance, popularity, revenue, genres, and cast members.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning Performed

- Converted movie duration from text format to numeric values
- Cleaned gross income by removing symbols and commas
- Cleaned vote counts by removing commas
- Checked for missing values
- Verified data types and summary statistics

## Key Analysis Performed

- Identified hidden-gem movies with high ratings and low votes
- Found overhyped movies with low ratings and high gross income
- Analyzed the most common genres
- Identified directors and actors appearing in the most movies
- Compared movie duration with ratings
- Found genres with the highest average ratings and gross income
- Identified high-grossing directors
- Analyzed the relationship between votes and gross income
- Examined yearly movie releases and revenue trends
- Studied the effect of certificates and ensemble casts on movie performance
- Identified director–actor duos appearing most frequently
- Calculated director hit rates for movies rated above 7.5

## Visualizations Included

- Average movie ratings over the years
- Number of movies released per year
- Distribution of movie ratings
- Top 10 most frequent actors
- Relationship between release year and rating
- Distribution of votes, gross income, and ratings
- Number of movies by genre
- Correlation heatmap of numerical features

## File Structure

```text
imdb-movie-data-analysis-python/
│
├── IMdb_Project.ipynb
└── README.md
