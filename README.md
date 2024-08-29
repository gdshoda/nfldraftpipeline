# Nfl Draft Data Pipeline

Greg Shoda

Info I535

Course Project

## Introduction

The NFL Draft is one of the most anticipated events of the NFL offseason, where all 32 NFL teams get the chance to improve their roster by adding the most talented eligible College Football players to their teams via a selection process outlined by the NFL (1). The draft process from a high level is simple, the NFL team with the worst win-loss record receives the first pick in the NFL draft who, in theory, is the best college football player. Then the second worst team will select a player, then the third worst team, etc. (1)

Teams begin to evaluate potential draft prospects years in advance, sending team scouts to watch College Football players all throughout the country to get a good understanding of who are the best College Football players (2). Once the NFL Season is over by one team winning the Super Bowl, the NFL offseason begins with a scheduled outline of when offseason events will take place. Two months before the NFL Draft, the NFL will invite 300 College Football players who have declared their intent to end their College Football career to play in the NFL to showcase their abilities at the NFL combine. The NFL Combine allows all NFL team scouts and coaches to meet in a single location with the new college prospects where the prospects go through interviews, drills, and physical tests (like the 40-yard dash) (1).
This all leads up to the NFL Draft event in late April where teams finally select the college players which will be joining their team in the upcoming season. The draft consists of 7 different rounds across three days. Each team has at least one selection in each of the 7 rounds, however some teams can have multiple selections in each round due to different NFL transactions (trades, compensatory draft selections, etc.).

## Background

While the logistics of the NFL Draft are understood by the teams and fans across the league, we are still with the question: how do you determine who the best player is when it is your team’s turn to select a player in the NFL Draft? Of course, different teams have different approaches, and each team’s roster of current players will also help a team determine what players they will target in the draft. Throughout the history of the NFL teams used to rely more heavily on scouts and personal analysis of a player, however in the 21st century we have seen a modernization of the NFL to rely more heavily on statistics and data analytics. As of 2023, each NFL team has at least two full time staff dedicated to analytics, and 21 of the 32 NFL teams have at least three full-time analytics employees (6).

The NFL draft has multiple facets where Data Analytics can be utilized to gain an advantage and help an NFL team create the best roster of players possible to help them win a Super Bowl. One of the most significant ways Data Analytics can be used is to help evaluate NFL draft prospects. Data Analytics can also help teams better evaluate draft strategies by establishing team needs and positional value to help teams maneuver their position in the draft to maximize the value in the player’s they are able to draft. Finally, data analytics can be used to help teams evaluate the trades that take place during the draft (7).

Due to the rise in data analytics being used to help teams evaluate draft prospects, I have decided to base my project on building a data pipeline to extract various sources of data that could be used to help teams evaluate players for the NFL Draft, transform the data to an actionable analytics format, and store the data to be used for analysis.

### Data Architecture Approach

(![pipeline](https://github.com/user-attachments/assets/1d111ac3-1a7b-430e-a584-dab8b26feaf8)

