# DATA 607 – Week 3A: Global Baseline Estimate

## Overview

This project implements a Global Baseline Estimate recommendation system using movie ratings provided in the DATA 607 course materials.

The objective is to predict how **Param would rate Pitch Perfect 2** based on the overall rating average, Param's rating behavior, and the average rating behavior for the movie.

## Technologies Used

- R
- R Markdown
- PostgreSQL
- DBI
- RPostgres

## Method

The original movie-rating matrix was converted into long format and stored in PostgreSQL. R was then used to retrieve and analyze the observed ratings.

The Global Baseline Estimate is calculated as:

**Predicted Rating = Global Mean + User Bias + Movie Bias**

The analysis produced:

- Global Mean: **3.9344**
- Param Mean: **3.5000**
- Param User Bias: **-0.4344**
- Pitch Perfect 2 Mean: **2.7143**
- Pitch Perfect 2 Movie Bias: **-1.2201**
- Predicted Rating: **2.2799**

Therefore, the estimated rating that Param would give to **Pitch Perfect 2 is approximately 2.28**.

## Files

- `DATA 607 Week 3A – Global Baseline.Rmd` – R Markdown source code and analysis
- `DATA-607-Week-3A-–-Global-Baseline.html` – Rendered HTML report
- `movie_ratings.csv` – Long-format movie ratings used for the database import
- `MovieRatings.xlsx` – Original course dataset

## AI Use

ChatGPT was used to help interpret the assignment requirements, organize the planned approach, improve the English writing, select an appropriate database structure, and provide coding guidance. I prepared and imported the movie-rating data, ran the code, reviewed the results, and confirmed the conclusions myself.

## Author

Patricio Romero  
DATA 607 – Fall 2026
