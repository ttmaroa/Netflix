# Netflix Data Analysis

## Project Overview
This project involves an exploratory data analysis (EDA) of a Netflix dataset, aiming to uncover insights into content distribution, popular genres, top directors, and rating trends on the platform. The analysis covers both movies and TV shows, providing a comprehensive view of Netflix's content library.

## Data Source
The dataset used for this analysis is `netflix_titles.csv`, which contains information about movies and TV shows available on Netflix.

## Analysis Steps
The following steps were performed:
1.  **Data Loading**: Loaded the dataset into a pandas DataFrame.
2.  **Missing Value Handling**: Filled missing values in 'director', 'cast', and 'country' columns with 'Unknown'. Rows with missing 'date_added', 'rating', or 'duration' were dropped.
3.  **Content Distribution Analysis**: Examined the distribution of 'Movie' versus 'TV Show' titles.
4.  **Top Directors**: Identified directors with the most content on Netflix.
5.  **Movie Release Trends**: Analyzed the trend of movie releases over the years.
6.  **Top TV Show Countries**: Identified countries producing the most TV shows.
7.  **Content Rating Distribution**: Explored the distribution of content ratings (e.g., TV-MA, PG-13).
8.  **TV-MA Movies by Country**: Determined which countries produce the most 'TV-MA' rated movies.

## Key Findings
*   Netflix's library is predominantly composed of **movies**, although TV shows also constitute a significant portion.
*   A substantial number of titles have 'Unknown' directors, suggesting incomplete data or uncredited works.
*   There has been a notable increase in movie releases over the years, with a high volume in recent years.
*   The **United States** leads in the production of both TV shows and movies, particularly in the 'TV-MA' category.
*   'TV-MA' and 'TV-14' are the most common content ratings, indicating a prevalence of mature content on the platform.

## Technologies Used
*   Python
*   Pandas (for data manipulation)
*   Matplotlib (for data visualization)
*   Seaborn (for data visualization)
