# Which NBA recruting year has the best overall players?

This project explores NBA data between the years of 1998 and 2013 in order to determine which recruit year has produced the best overall NBA players based on certain performance indexes in the dataset. I would like to see if the conclusions reached with this data match the generally held opinions that are not based on any statistical information. 

## Data

The data used for this project comes from players.csv and paths.csv. The specific columns used are:

**name**: The player's name.

**recruit_year**: The year that the player was recruited to a college team or their last year of high school. This columnn was chosen over draft year as not every player was drafted, and therefore had no draft year. 

**highest**: The highest level reached by that player, which is one of the following: highSchool, college, draft, rookie, bad, good, great, or allstar. The levels are determined by either their highest level played or their average rank in the NBA if they made it that far. 

**nba_men_ws48**: The average win share Per 48 (ws48) minutes across all of a player's eligible seasons. This measure is based on their offense, defense, and playing time. A 'win share' is worth 1/3 of a team win.

**nba_mean_pipm**: The average player impact plus minus (pipm) across all of player's eligible seasons. This measure is a 'luck-adjusted' version of plus-minus which estimates a player's value over the course of a season based on their offenseive and defensive efficiency. 

**nba_mean_wa**: The average wins added (wa) across all of player's eligible seasons. This measure shows how many more games a team won due to that player. 

## Highest Rank by Year

The first step in my analysis was to total the number of each higest rank by year. The below graphs show the number of each highest rank for each recruit year.

![Players Highest Status by Year](https://user-images.githubusercontent.com/74326062/166969509-51fc101d-d027-4b78-9809-adc9c65ddf3e.png)

Based on the above graphs you can see that a majority of the players from each recruit year do not progress past college. The year with the most 'allstars' is 2004 with 7.

EXPAND ON DIFFERENT HIGH POINTS IN THE DATA

## Statistical Categories by Year

The next step in my analysis was graphing the average of each statistical category by recruit year to see if we could determine which year had the highest number for each measure.

![Mean WS 48 by Recruit Year](https://user-images.githubusercontent.com/74326062/166815007-a2d772b2-c12a-4a05-934d-24a256f31b88.png)
![Mean VORP by Recruit Year](https://user-images.githubusercontent.com/74326062/166814821-88d76c2d-f5f4-416f-aa91-31ee10f2c907.png)
![Mean PIPM by Recruit Year](https://user-images.githubusercontent.com/74326062/166815223-7802edb1-3ff9-4bf6-a9a0-f3ae585770d9.png)
![Mean WA by Recruit Year](https://user-images.githubusercontent.com/74326062/166815372-5eccc4d4-f0d3-428f-8fe9-0df5f1222126.png)

Based on the graphs above we can see that 2 recruit years seem to be at the top of each statisitcal category: 2003 and 2009. In fact, 2003 has the best number for every statistical measure used in this project. Looking into this recruit class, the general consensus seems to agree that this is one of the best classes of all time. This class includes players such as: LeBron James, Carmelo Anthony, Chris Bosh, and Dwayne Wade.

EXPAND

## Missing Data

One further comment to make about this data is the large number of missing values. The below chart shows the percentage of each class that has no statistical data.

![Percent Null by Year-2](https://user-images.githubusercontent.com/74326062/166815734-cc146f47-24c1-4c9a-9a79-683ba39cd32f.png)

Researching further, I believe there are null values for players who did not make it into the NBA, or did not play for a very long time. Because of this they have no information to be listed. So, the smaller amount of nulls for a recruit year means more players made it into the NBA and played for a longer time. Recruit year 1999 has the smallest amount of nulls at 69%. 

EXPAND

## Final Conclusions

EXPAND

## Sources

Goldenberg, R. G. (2019, March 4). The Pudding NBA Data. GitHub. Retrieved April 29, 2022, from https://github.com/the-Pudding/data/blob/master/hype/README.md 
