# Soccer Match Outcome Analysis

## Overview

This project analyzes soccer match fixture data to compare how often home teams win compared with away teams.

## Dataset

The dataset used is **fixtures.csv**. It contains match-level fixture data, including home and away team IDs, scores, winner indicators, attendance, league information, and match dates.

## Main Question

**Do home teams win more often than away teams?**

## Approach

* Load the local dataset with Pandas
* Count home wins, away wins, and draws
* Calculate home and away win rates
* Visualize goal difference and match outcome counts
* Use a simple linear regression to examine how goal difference relates to home team wins

## Key Tasks

* Data loading and preprocessing with Pandas
* Use of loops and conditionals for analysis
* Custom function for evaluating metrics
* Numpy operations for computation
* Dictionary to store aggregated results
* Two visualizations (histogram + comparison plot)

## Main Finding

Home teams won more often than away teams in this dataset. Home teams won 2,182 matches, while away teams won 1,469 matches.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib

## Notes

This analysis focuses on match-level fixture results and does not include player-level statistics or external context such as injuries, travel, or team rankings.
