# Premier League Match and Standings Analysis

## Overview
This project analyzes English Premier League match data from 2000/01 to 2024/25 to identify patterns in league standings, champions, goals, home advantage, team win rates, and long-term team performance. Built with Python (pandas) in a Jupyter Notebook.

## Dataset used
The dataset used in this project consists of 9,380 Premier League matches across 22 columns, detailing seasons, match dates, teams, full-time and half-time results, goals, shots, corners, fouls, and cards.

Data notes:
- The dataset covers 25 seasons, but 3 of them are incomplete: 2003/04 and 2004/05 have 335 matches each, and 2024/25 has 350 matches (a full season has 380).
- These 3 seasons are excluded from the standings, champions, and team comparisons, leaving 22 complete seasons (8,360 matches).
- The home vs away analysis uses all 25 seasons, since it only needs match results.

## Objective
- Build the final league standings for every complete season
- Identify the Premier League champion of each season and count titles by club
- Identify the highest-scoring teams
- Analyze home advantage by comparing home and away results across seasons
- Compare win rates across teams
- Track the league points of a single team (Manchester United) over time
- Explore the relationship between goal difference and final league position
- Compare average finishing position and points across teams

## Conclusion
This analysis highlights what drives success in the Premier League across 22 complete seasons.

- Titles: Man City won the most titles (8), followed by Man United (7) and Chelsea (4). Arsenal, Liverpool, and Leicester won 1 each within the seasons analyzed.
- Goals: Arsenal scored the most goals in total (1,580), followed by Liverpool (1,570) and Man City (1,566). Man City played only 21 of the 22 seasons, so per season they scored the most among these three (about 74.6 goals per season).
- Home advantage: Home teams won more often than away teams in 24 of 25 seasons. The only exception was 2020/21, when games were played without fans because of COVID-19 and away teams won slightly more often (40.3% vs 37.9%).
- Win rate: Man United has the highest win rate (60.2%), followed by Man City (57.9%) and Liverpool (56.7%).
- Man United over time: They earned 80 or more points in 10 of 11 seasons before Sir Alex Ferguson retired in 2013, but in only 1 of 11 seasons after.
- Goal difference: Goal difference is strongly related to final position (correlation of about -0.92), so teams that score more than they concede tend to finish higher.
- Consistency of the top clubs: The Big Six have the best average finishing positions and points.

Team comparisons are affected by how many seasons each club played in the Premier League, so clubs with few seasons should be compared with caution.
