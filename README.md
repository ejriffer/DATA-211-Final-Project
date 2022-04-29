# Which NBA recruting year has the best overall players?

This project explores NBA data between the years of 1998 and 2013 in order to determine which recruit year has produced the best overall NBA players. 

## Data

The data used for this project comes from players.csv and paths.csv. The specific columns used are:

**name**: The player's name.

**recruit_year**: The year that the player was recruited to a college team or their last year of high school. This columnn was chosen over draft year as not every player was drafted, and therefore had no draft year. 

**highest**: The highest level reached by that player, which is one of the following: highSchool, college, draft, rookie, bad, good, great, or allstar. The levels are determined by either their highest level played or their average rank in the NBA if they made it that far. 

**nba_men_ws48**: The average win share Per 48 (ws48) minutes across all of a player's eligible seasons. This measure is based on their offense, defense, and playing time. A 'win share' is worth 1/3 of a team win.

**nba_mean_vorp**: The average value over replacement player (vorp) across all of player's eligible seasons. This measure shows how much a player contributes to their team in comparison to a 'replacement' level player who would be statistically below average, ie. a freely avaliable free agent. 

**nba_mean_pipm**: The average player impact plus minus (pipm) across all of player's eligible seasons. This measure is a 'luck-adjusted' version of plus-minus which estimates a player's value over the course of a season based on their offenseive and defensive efficiency. 

**nba_mean_wa**: The average wins added (wa) across all of player's eligible seasons. This measure shows how many more games a team won due to that player. 

## Highest Rank by Year

The first step in my analysis was to total the number of each higest rank by year. The below graphs show the percent of each highest rank for each recruit year. 

![2001highest-2](https://user-images.githubusercontent.com/74326062/165976978-d0ec51e7-8fe5-491f-872a-ebd70cafc3a9.png) ![2002highest-2](https://user-images.githubusercontent.com/74326062/165975193-73c34f8c-0692-4396-935c-466a97fd72f4.png)



## Statistical Categories by Year


