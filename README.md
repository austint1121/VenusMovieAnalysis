# Team Venus' Movie Analysis

**Authors**: 
- [Matthew Turner](https://github.com/austint1121)
- [Andrew Witman](https://github.com/andrewwhitman)
- [Wayne Harrison](https://github.com/wharr1203)


## Overview

The goal of this project is to provide actionable insights to the head of Microsoft's new fictional movie studio. We
used data from Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers. After analyzing the data the group
decided to recommend a genre of movie to make, which month to release the movie in, and how long the movie should be.
The results of our analysis found that the safest genre of movie to make would be an Animated film. We found that movies 
released during the summer would typically have a higher return on investment then any other month. Finally, we found
animated movies typically had the highest return on investment when they were 100 minutes long.
Therefore, we recommended that:

1. Microsoft makes an animated movie
2. The studio should release the movie during the summer months
3. The studio should aim to make the movie approx. 100 minutes long.
***
## Business Problem

Our group was presented the fictional scenario:

Microsoft sees all the big companies creating original video content, and they want to get in on the fun. They have
decided to create a new movie studio, but they don't know anything about creating movies. You are charged with exploring
what types of films are currently doing the best at the box office. You must then translate those findings into
actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

***

## Data
There are 11 CSV files comprising the dataset. This section will seek to understand the source, properties, and business
relevance of the data. In particular, we will explore the structure of the data in each file, inspect individual data
elements to understand their properties, and consider the relationships between the data in each file and to the
business problem.

IMDb is an online database  containing information related to films, tv shows, video games, and the like. We used 
this dataset for information about a movie's genre, and runtime. We also used this dataset for information on how IMDB's
user's rated movies

The Movie DB is a user editable database for movies and TV shows. We used this dataset to determine when a movie was
released.

The Numbers is a website used as a source for movie financial data. We used this data to find metrics on a movie's profit,
budget, gross revenue, profit margin, and return on investment.


***

## Information

Please review our full analysis in [our Jupyter Notebook](./VenusFinalNotebook.ipynb) or our [presentation](./presentation.pdf).

For any additional questions, please contact **name & email, name & email**

## Repository Structure

```
├── Data                                <- Directory containing both cleaned and raw data
│   ├── zippedData                      <- Compressed, unmodified data from our sources 
│   ├── imdb_data                       <- Cleaned data from IMDB
│   ├── tmdb_data                       <- Cleaned data from TheMovieDB
│   └── tn_data                         <- Cleaned data from The Numbers
├── Images                              <- Folder containing graphs from notebook and presentation
│   └── ...
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── VenusFinalNotebook.ipynb            <- Narrative documentation of analysis in Jupyter notebook
└── README.md                           <- The top-level README for reviewers of this project
              

``` 