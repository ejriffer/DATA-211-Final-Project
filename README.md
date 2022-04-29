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

<img width="162" alt="Screen Shot 2022-04-29 at 11 49 27 AM" src="https://user-images.githubusercontent.com/74326062/165979530-ea9d1cfb-e518-4862-a2fb-f4d991e635c2.png">
![1998highest-2](https://user-images.githubusercontent.com/74326062/165977385-c65ae919-e044-4119-a0e9-af5f09a501a2.png)
![1999highest-2](https://user-images.githubusercontent.com/74326062/165977408-db1133bc-f071-43a7-9168-3d1de197a705.png)
![2000highest-2](https://user-images.githubusercontent.com/74326062/165977424-c65be93e-048c-4d88-9bf3-9957e5ed1aea.png)
![2001highest-2](https://user-images.githubusercontent.com/74326062/165976978-d0ec51e7-8fe5-491f-872a-ebd70cafc3a9.png) 
![2002highest-2](https://user-images.githubusercontent.com/74326062/165975193-73c34f8c-0692-4396-935c-466a97fd72f4.png)
![2003highest-2](https://user-images.githubusercontent.com/74326062/165977463-36606994-2b24-47e6-88bc-918f03c0914f.png)
![2004highest-2](https://user-images.githubusercontent.com/74326062/165977476-67adfeed-9800-4a0d-a97e-e7318e9a1e01.png)
![2005highest-2](https://user-images.githubusercontent.com/74326062/165977485-86f6de2f-9001-47a8-b2ff-26d06a0d8dda.png)
![2006highest-2](https://user-images.githubusercontent.com/74326062/165977506-58baea74-05eb-4069-b082-108c0415fdaa.png)
![2007highest-2](https://user-images.githubusercontent.com/74326062/165977515-df5f84d0-ba57-49eb-9f3f-c3132a2bb6ec.png)
![2008highest-2](https://user-images.githubusercontent.com/74326062/165977526-532d8b60-69cc-4f1e-a57d-1ea796e79c56.png)
![2009highest-2](https://user-images.githubusercontent.com/74326062/165977542-c4b2c4a8-3bf4-4aec-9a51-1a5bacadf498.png)
![2010highest-2](https://user-images.githubusercontent.com/74326062/165977551-3c65852f-84d7-4156-8623-131f1141c793.png)
![2011highest-2](https://user-images.githubusercontent.com/74326062/165977558-fc6cb50e-67af-45e1-8c01-48456f716473.png)
![2012highest-2](https://user-images.githubusercontent.com/74326062/165977570-c702f896-3280-4bcf-aee8-87c5e80f06da.png)
![2013highest-2](https://user-images.githubusercontent.com/74326062/165977574-740cfec6-8545-4d57-beb6-0a070b1b185d.png)

## Statistical Categories by Year


