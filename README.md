# Dataset

## First inning ball to ball coverage of:

* 1188 ODI matches -> data/odi.csv
* 1474 T-20 matches -> data/t20.csv
* 617 IPL matches -> data/ipl.csv

## Each dataset consists of the following columns:

* mid -> Each match is given a unique number
* date -> When the match happened
* venue -> Stadium where match is being played
* bat_team -> Batting team name
* bowl_team -> Bowling team name
* batsman -> Batsman name who faced that ball
* bowler -> Bowler who bowled that ball
* runs -> Total runs scored by team at that instance
* wickets -> Total wickets fallen at that instance
* overs -> Total overs bowled at that instance
* runs_last_5 -> Total runs scored in last 5 overs
* wickets_last_5 -> Total wickets that fell in last 5 overs
* striker -> max(runs scored by striker, runs scored by non-striker)
* non-striker -> min(runs scored by striker, runs scored by non-striker)
* total -> Total runs scored by batting team after first innings


* Note Incomplete below
# Prediction Algorithm and Accuracy

## Algorithms Used

1. Linear Regression
2. Random Forest Regression

## Features and Label Used

* Features: [runs,wickets,overs,striker,non-striker]
* Label: [total]

