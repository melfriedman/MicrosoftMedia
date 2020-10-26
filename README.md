![alt text](https://github.com/melfriedman/MicrosoftMedia/blob/main/pictures/film.jpg)

# MicrosoftMedia
Flatiron online Data Science phase 1 project

## Project partners
Austin Murray and Mel Friedman

## Business Problem and how we plan to solve it
Microsoft is starting their own movie studio and needs recommendations on what is currently doing well in the movie market. 
We are going to look at datasets and API’s from the biggest movie websites to gather current data, details and technical specs. 

## Where did we get our data?
Data sets from:
IMDB
TMDB

API’s:
IMDb API by apidojo found on Rapid API
GeoCoding API by Google Cloud API

The data we used was filtered by movies that only had a USA release. Foreign movies were included as long as they were still released in America. 

Data sets were filtered to only the last 5 years to get a current representation of what customers want.

# Findings
We compared runtime to ratings scores and the amount of ratings. We wanted to see if the length of the movie had any effect on how it was liked and how many people not only watched but voted on it.
Through our analysis we were able to show that movies that were between 150 to 175 minutes had high scores that had above average amount of votes. Showing that these were good movies seen by a large audience
![alt text](https://github.com/melfriedman/MicrosoftMedia/blob/main/pictures%20for%20readme/Runtime%20vs%20ratings.png)


We looked at what month did movies make the most profit in. By comparing the profit by month with the average median and standard deviation we could see that July was the clear winner. It was in the top for both average and median making it a top performer but also in the bottom half of standard deviation meaning those high profits are a normal tendency
![alt text](https://github.com/melfriedman/MicrosoftMedia/blob/main/pictures%20for%20readme/Profit%20vs%20Month.png)


Profit vs Genre was a question that intrigued us but as we analyzed the data we saw that yes some genres had the potential to earn profits at magnitudes higher than other genres the large Standard deviation also showed they could flop even harder.
![alt text](https://github.com/melfriedman/MicrosoftMedia/blob/main/pictures%20for%20readme/Profit%20vs%20Genre.png)

When going into the financial details we also wondered if the movies that had the highest world wide gross were also the movies with the highest return ratio. We found that this was not the case and the top 10 movies in either category had no overlap. This showed us that a movie that had a smaller budget may have made many more times that in gross profit, but still not nearly as much as some of the big blockbuster movies that had a higher budget.
![alt text](https://github.com/melfriedman/MicrosoftMedia/blob/main/visualizations/grossprofit.png) ![alt text](https://github.com/melfriedman/MicrosoftMedia/blob/main/visualizations/profitreturn.png)

Lastly, we wanted to know where movies were made and if a certain location produced higher grossing movies. ![alt text](https://github.com/melfriedman/MicrosoftMedia/blob/main/visualizations/world%20map.png) all the filming locations recorded
![alt text](https://github.com/melfriedman/MicrosoftMedia/blob/main/visualizations/heatmap.png) heatmap of where the movies with the highest return ratio were filmed

With these findings we believe that we have the data Microsoft would need to get started on creating their film studio and produce quality, high grossing movies that also have a high profit return.

![alt text]https://github.com/melfriedman/MicrosoftMedia/blob/main/pictures/popcorn.jpg ![alt text]https://github.com/melfriedman/MicrosoftMedia/blob/main/pictures/stonks.jpg

