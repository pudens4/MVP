# MVP

## Overview
In this project, I will determine the Most Valuable Player of the NBA season based on 
analytics. I use a list of metrics to define MVP, then use data analysis to determine the deserving MVP. 

### Metrics 
Most Valuable Player is a straightforward definition. It is the player that is the most valuable 
to a team, with that we can compare the value of the players to a team and the overall league to determine 
who is the MVP. 

How valuable a player is to a team? <br/>
I create a formula to compute a player value to a team based on several metrics

How do we measure value? <br/>
- Game played
- minutes played
- points per game
- assists per game
- rebound per game
- plus minus
- team record W/O

I assign each measure with a weight on importance <br/>
Value = gm + mn + pts + ass + reb + pm + rec + usage <br/>
Value = .05 + .15 + .15 + .15 + .15 + .10 + .2 + .05

### How the program works?
The program will go through each date of the season, compute the value of each player and 
add them to a leaderboard

### Challenges 
Some challenges I've encountered in the data were
- duplicates of players and stats, 
- data types needed to change from string to integer or float


## Resources

## Summary
