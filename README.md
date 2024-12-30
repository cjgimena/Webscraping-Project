# Webscraping-Project
A series of scrapers that retrieve professional and college tennis data with match analytics.

Author: Clajerson Gimena

## Overview
The Webscraping Project is a series of Python tools designed to scrape tennis match data from the proffessional and collegiate level.

## tennislive.net
### Features
#### player_profile.ipynb
- Generalized For All Players: Input the profile url of your desired player and the tool will create a csv file of all the matches said player has played over the course of their profesional career.
- Complete Match History: Retrieve each opponent, including event name, round, date, surface, score, and stats.
- Match Analysis: Extracts match data such as first/second serve percentage, first/secondf serve points won, return points won, total points won, double faults, aces, and break points won for all the matches for a given player.
- Data Cleaning & Formatting:
  - Assigns winner of match to *Player 1* column.
  - Formats score to always be in relation of Player 1.
  - Leaves stat cells as blank if there are no stats available.
 
#### point_by_point.ipynb
- Generalize For All Matches: Input the match url of your desired match and the toll will create a csv file of the point-by-point data for said match.
- Complete Point History/Match Analysis: Extracts mtach data such as point score, game score, server name, set number, and breakpoint events for a given match.
- Data Cleaning & Formatting:
  - Adds columns such as *player1Name*, *player2Name*, *returnerName*, *tiebreakerScore*, and *clientTeam*/*opponentTeam*
  - Adds *Name* Column to be used for UCLA Tennis Consulting Match-Viewer Website

## ioncourt.com
*** COMING SOON ***

## uclabruins.com
*** COMING SOON ***

## Requirements
- Python 3.11+
- Dependencies:
  - requests
  - beautifulsoup4
  - pandas
  - numpy
  - re

You can install dependencies via:
```
pip install requests, beautifylsoup4, pandas, numpy, re
```

