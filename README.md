# European climate effect on weather
## A daily top 200 Spotify Analysis 2019


## Overview

Include the following points in your overview:

* The question I wanted to answer is if climate has an effect on peoples music choice. Please find the following two hypothesis for this analysis. 

* h_0 : Weather has no effect on music choice 
* h_1 : Weather has an effect on music choice 
* 
* I will test this hypothesis by using the top 200 daily Spotify charts and world weather API to see if there is a link between the climates and music choice. 

## Data Preparation

### Overview:

* What is your dataset about?
- the dataset consists of the top 200 daily charts for each European Country 
* Where/how did you obtain your dataset?
	* Webscraper for Spotify csvs
	* [Spotify API](https://developer.spotify.com/documentation/web-api/)
    * [World weather API](https://www.worldweatheronline.com/developer/api/)
* The dataset includes 1425909 rows × 24 columns.
* THE columns include: 'artist', 'position', 'streams', 'track' ,name', 'acousticness', 'cloud', 'danceability', 'date', 'energy', 'humidity','instrumentalness', 'key', 'liveness', 'loudness', 'rain', 'region','snow', 'speechiness', 'spotify_id', 'temp', 'tempo', 'valence','explicit', 'month'
.

### Data Wrangling and Cleaning

* Check dtypes
* Create for loop to cast data into the right types
* Check for NaNs
* Check for duplicates
* Rename the regions to use for mapping
* Drop irrelevant columns
* Make a weighted average for the different song anaylsis features so that all the countries have relative 
* Rearrange columns for congruiety




## Conclusion

* Northern Europe tend to play sad, quiet, downtempo music
* Southern Europe tend to play happy, danceable, energetic music 
* The largest disparaty between countries and climates is in winter where we can draw the most results
* In summer alot of countries around Europe is listening to the same music in the charts so there is not as much difference in results
* Europeans tend to listen to Explicit music in the winter months with the exception of the 24th and 25th of December where the listeners of Explict music drops by 50%
* On the 28th Explicit music listeners increase to 150% 

