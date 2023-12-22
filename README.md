# Games-Classification

## Part 1: Data Scraping
The first part of this project is the data scraping of the games present in the pages of Metacritic, carried out through the Selenium library. The page links for each game were saved in a txt file, while the following data was saved in a json file:

- Title
- Release date 
- Platform
- Metascore
- Number of reviews from critics
- User score
- Number of user ratings
- Game developer
- Gender
- Number of players

## Part 2: Data Processing
In the second part of this project, all collected data is processed to ensure its consistency and usefulness. This includes cleaning up missing values, converting data to the correct format, and encoding categorical data.

## Part 3: Classification model training
In the third and last part of this project, the processed data is used to train a classification model. This model is used to predict a game's metascore score based on other information such as game developer and genre.
