# What Stats Most Accurately Predict UFC Wins?
**By Shane Dugan and Erik Schmidt**

## Introduction

*Written by Erik*

## Getting Started
In this project, we used Python 3, with some imported libraries. The libraries we used were [pandas](https://pandas.pydata.org/pandas-docs/stable/), [numpy](numpy.org), [scikit-learn](https://scikit-learn.org/stable/index.html), [matplotlib](https://matplotlib.org/contents.html), and [seaborn](https://seaborn.pydata.org/).

*Insert code here*

The dataset we found was pulled from [Kaggle](kaggle.com), which is a site that allows its users to upload and share datasets, projects, and compete in data science challenges. The dataset is a CSV (Comma Separated Value) file, which contains almost every fight in the UFC from March 1993 till June 2019.

## Data Pre-processing
The dataset itself had a lot of columns that we did not need and that were duplicates. The dataset is organized with information about the fight coming first, then about each fighter, labeld Red (R) and Blue (B). From the general fight information, we deleted columns referee, location, and title_bout, because they were not useful to our analysis. For each fighter the column types `BODY, CLINCH, DISTANCE, GROUND, HEAD, KD, LEG, PASS, REV, SIG_STR, SIG_STR_pct, SUB_ATT, TD, TD_pct`, and `TOTAL_STR` were not only not needed, but also duplicated. In addition to those, we also deleted the columns `total_rounds_fought, total_time_fought(seconds)`, and `total_title_bouts`, as they were not relevant to the analysis. We went from 145 columns down to 40. 

*Data preprocessing code*

## The Data Itself
In the dataset, each row represents a fight. For each fight, listed is the Red fighter, Blue figther, date, winner, weight class, and number of rounds. For each of the fighters (R, B) is listed their stats at the time of the fight. `R_` represents red corner while `B_` represents blue corner. After the data that was dropped, the columns that were left were those containing general stats about the fighter before the round. These include:
1. `current_lose_streak`: Losing streak of the fighter
2. `current_win_streak`: Winning streak of the fighter
3. `draw`: Number of draws in the fighter's career
4. `longest_win_streak`: Longest win streak of the fighter
5. `losses`: Number of losses overall
6. `win_by_Decision_Majority`: Number of fights won by majority judges decision
7. `win_by_Decision_Split`: Number of fights won by split judges decision
8. `win_by_Decision_Unanimous`: Number of fights won by unanimous judges decision
9. `win_by_KO/TKO`: Wins by knockout
10. `win_by_Submission`: Wins by submission
11. `win_by_TKO_Doctor_Stoppage`: Wins by doctor stoppage
12. `wins`: Total wins of the fighter
13. `Stance`: Stance of the fighter
14. `Height_cms`: Height in centimeters of the fighter
15. `Reach_cms`: Arm span in centimeters of the fighter
16. `Weight_lbs`: Weight in pounds of the fighter
17. `age`: Age of the fighter

*Show code/data*

## Tidying Up
In order to aid in data analysis, we first only used the first 4000 rows, which dropped around 1100 rows that had data that had a lot of missing values. This effectively gives us the data from the past 10 years. Then, we decided to create two separate dataframes, with each fighter from each fight. We split up the data by blue or red corner, and created a new dataframe with all the information for each fighter, plus the name of the fighter, in two dataframes, called B_fights and R_fights. We also went through each row and created an array of booleans for each side, which represented whether or not the fighter on that side one, and appended those arrays to their corresponding dataframes.

We then renamed all the columns in these two fighter dataframes to be the same, by removing the `B_` and `R_` prefixes. Once the column names were the same, we appended them together under a new dataframe, fights2.

*Data tidying code*

# Exploratory Data Analysis

*Note: groupby reach size (160-170, etc.) for reach vs. wins*
