# NEW MOVIE STUDIO

![movieStudio](https://github.com/user-attachments/assets/226733c5-363e-4f29-bcb0-52f3d49b8d5f)


## Overview

Your company is venturing into the movie industry by creating a new movie studio. With the rise of original content creation by major companies, there's an opportunity to tap into this lucrative market. However, your company lacks the necessary insights and expertise in filmmaking. The objective of this project is to analyze current trends in the movie industry, focusing on what type of films are performing best at the box office, and translate these findings into actionable insights for the new movie studio.

## Business Understanding

### Stakeholder
- **Head of the company's new movie studio**

### Key Business Questions
1. What is the best season to release movies to maximize popularity and domestic gross?
2. What is the most successful genre in terms of revenue?
3. Is there a relationship between movie runtime, domestic gross, and production budget?
4. What are the leading movie studios and their average production budgets?
5. Can the film industry be a consistent profit center?
6. What is the correlation between vote average and popularity?

## Data Understanding and Analysis

### Source of Data
1. [Box Office Mojo](https://www.boxofficemojo.com)
2. [IMDB](https://www.imdb.com)
3. [Rotten Tomatoes](https://www.rottentomatoes.com)
4. [TheMovieDB](https://www.themoviedb.org)
5. [The Numbers](https://www.the-numbers.com)


#### The datasets used for this analysis include:
- bom.movie_gross.csv.gz: Box office gross data from Box Office Mojo.
- rt.movie_info.tsv.gz: Movie information from Rotten Tomatoes.
- rt.reviews.tsv.gz: Movie reviews from Rotten Tomatoes.
- tmdb.movies.csv.gz: Movie data from The Movie Database (TMDB).
- tn.movie_budgets.csv.gz: Movie budgets from The Numbers.
- im.db: Additional movie data from IMDB.

### Description of Data
The datasets include various columns such as:
1. **Movie Title**: The title of the movie.
2. **Release Year**: The year the movie was released.
3. **Genre**: The genre(s) of the movie (e.g., Action, Comedy, Drama).
4. **Director**: The name of the director(s).
5. **Cast**: The main cast members.
6. **Budget**: The production budget of the movie.
7. **Box Office Gross**: The total revenue generated by the movie.
8. **Average Score**: The average rating given by critics or audiences.
9. **Number of Reviews**: The total number of reviews received.
10. **Popularity**: A metric indicating the popularity of the movie.
11. **Runtime**: The duration of the movie in minutes.
12. **Language**: The primary language of the movie.
13. **Country**: The country where the movie was produced.
14. **Production Company**: The company that produced the movie.
15. **Release Date**: The specific date when the movie was released.
16. **Awards**: Any awards won by the movie.
17. **Rating Certificate**: The movie's certification rating (e.g., PG, R).
18. **Synopsis**: A summary of the movie's plot.

## Data Preparation
### The datasets were cleaned and merged as necessary. Steps included:
1. Loading and inspecting the datasets.
2. Handling missing values and correcting data types.
3. Merging datasets on common keys such as movie titles and release dates.

## Data Analysis
### The analysis addressed the following key questions:
1. Best Release Seasons: Analyzed box office performance by release month to identify
optimal seasons.
2. Successful Genres: Evaluated the popularity and box office success of different genres.
3. Runtime and Budget Analysis: Investigated the impact of movie runtime and
production budget on box office performance.

## Results
### Key Findings
1. Optimal Release Timing:
Movies released during the summer (June to August) and winter holiday seasons
(November to December) tend to perform better in terms of domestic gross.
2. Genre Performance:
Action, adventure, and family-friendly genres show high popularity and
profitability. These genres have broad audience appeal and tend to receive
higher box office revenue and better reviews.
3. Budget and Runtime Optimization:
Movies with moderate budgets (between $30M to $100M) and runtimes of 90 to
120 minutes tends to achieve a good balance between production cost and box
office revenue.

## Visualizations

1. **Best Season to Release Movies**
![movieSeasons](https://github.com/user-attachments/assets/3d6c0da6-cb63-4d32-8ece-3879019b5d4f)
- The analysis shows that movies released during the summer (June to August) and winter holidays (November to December) tend to perform better in terms of domestic gross.


2. **Most Successful Genre**
![successfulGenre](https://github.com/user-attachments/assets/958eb54f-704f-4823-8b56-42b4082a5243)
- Sci-Fi, Adventure, and Animation genres show high popularity and profitability. These genres have broad audience appeal and tend to receive higher box office revenue and better reviews.



3. **Runtime vs Domestic Gross, Worldwide Gross, and Production Budget**
![runtime](https://github.com/user-attachments/assets/7285ee07-0a78-4cd5-9a42-3ba73cd4f381)
- The analysis indicates that movies with moderate budgets (between 30𝑀𝑡𝑜30𝑀𝑡𝑜100M) and runtimes of 90 to 120 minutes tend to achieve a good balance between production cost and box office revenue.


4. Correlation Heatmap of Movie Variables
![corr](https://github.com/user-attachments/assets/972f7a00-ced6-43c8-8be3-96c9503de3be)
- A strong positive correlation exists between the production budget and domestic and worldwide gross revenues, indicating that higher budgets tend to result in higher earnings. Additionally, the runtime shows a moderate positive correlation with worldwide gross, suggesting that longer movies may achieve greater global revenue, though this relationship is weaker for domestic gross. Overall, these insights suggest that investing in higher production budgets and potentially longer runtimes could be associated with better financial performance, providing valuable guidance for future movie production strategies.


## Business Recommendations
1. Release Timing: Focus on scheduling major movie releases during the summer and
winter holiday seasons to maximize box office returns.
2. Genre Focus: Prioritize the production of action, adventure, and family-friendly movies.
These genres have a proven track record of success and offer higher potential returns.
3. Budget and Runtime: Optimize production budgets to fall within the $30M to $100M
range and aim for movie runtimes between 90 to 120 minutes. This strategy balances
cost and potential revenue, enhancing profitability.

## Next Steps
1. Further Genre Analysis: Conduct a deeper dive into sub-genres to identify niche
markets.
2. Marketing Strategy: Analyze the impact of marketing spend on movie success.
3. International Markets: Explore box office performance trends in international markets.


## Links
- [Presentation](https://www.canva.com/design/DAGMJ2qyf1Y/MgGOPKwV9VkOCHNHMHFkkw/edit?utm_content=DAGMJ2qyf1Y&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
- [Tableau](https://public.tableau.com/app/profile/zachariah.komu/viz/Studio_17221983411970/Dashboard1#2)


## Repository Navigation Instructions

1. **zippedData**: Contains raw and processed data files.
2. **Notebooks**: Jupyter notebooks with analysis and visualizations.
3. **Slides**: Presentation slides summarizing the project findings.
4. **README.md**: This file, provides an overview of the project.

