# DATA 607 Week 3A – Global Baseline

This repository contains the planned approach and data preparation for a movie-rating recommendation analysis using PostgreSQL and R.

## Objective

The objective is to estimate Param's missing rating for *Pitch Perfect 2* using the Global Baseline recommendation method.

## Data

The source data came from the `MovieRatings` worksheet in the provided Excel workbook. The original rating matrix was converted to long format with three variables:

- `critic`
- `movie`
- `rating`

Blank cells and the question mark were treated as missing observations. The prepared dataset contains 61 observed ratings.

## Workflow

1. Prepare the movie-rating data.
2. Import the observed ratings into PostgreSQL.
3. Retrieve the data from PostgreSQL using R.
4. Validate the imported observations.
5. Calculate the Global Baseline estimate in R.

## Repository Files

- `movie_ratings.csv`: observed movie ratings in long format
- `DATA-607-Week-3A-Global-Baseline.Rmd`: R Markdown source
- `DATA-607-Week-3A-Global-Baseline.html`: rendered report
- `Week 3A.Rproj`: RStudio project file

## Published Report

[View the report on RPubs](https://rpubs.com/howtwo3/data607-week3a-global-baseline)

## Tools

- R and RStudio
- PostgreSQL
- pgAdmin
- DBI
- RPostgres

## AI Use

ChatGPT was used to help interpret the assignment requirements, organize the planned approach, improve the English writing, select an appropriate database structure, and provide coding guidance. The data, code, results, and conclusions were reviewed and confirmed by the author.