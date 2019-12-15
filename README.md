# What Stats Most Accurately Predict UFC Wins?
**By Shane Dugan and Erik Schmidt**

## Introduction

*Written by Erik*

## Getting Started
In this project, we used Python 3, with some imported libraries. The libraries we used were [pandas](https://pandas.pydata.org/pandas-docs/stable/), [numpy](numpy.org), [scikit-learn](https://scikit-learn.org/stable/index.html), [matplotlib](https://matplotlib.org/contents.html), and [seaborn](https://seaborn.pydata.org/).

*Insert code here*

The dataset we found was pulled from [Kaggle](kaggle.com), which is a site that allows its users to upload and share datasets, projects, and compete in data science challenges. The dataset is a CSV (Comma Separated Value) file, which contains almost every fight in the UFC from March 1993 till June 2019.

## Data Pre-processing
The dataset itself had a lot of columns that we did not need and that were duplicates. The dataset is organized with information about the fight coming first, then about each fighter, labeld Red (R) and Blue (B). From the general fight information, we deleted columns referee, location, and title_bout, because they were not useful to our analysis. For each fighter the column types `BODY, CLINCH, DISTANCE, GROUND, HEAD, KD, LEG, PASS, REV, SIG_STR, SUB_ATT, TD, TD_pct`, and `TOTAL_STR` were not only not needed, but also duplicated in the `avg_opp_` columns. In addition to those, we also deleted the columns `total_rounds_fought, total_time_fought(seconds)`, and `total_title_bouts`, as they were not relevant to the analysis. We went from 145 columns down to 42. 

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
18. `avg_SIG_STR_pct`: Percentage of significant strikes by the figther

*Show code/data*

## Tidying Up
In order to aid in data analysis, we first only used the first 4000 rows, which dropped around 1100 rows that had data that had a lot of missing values. This effectively gives us the data from the past 10 years. Then, we decided to create two separate dataframes, with each fighter from each fight. We split up the data by blue or red corner, and created a new dataframe with all the information for each fighter, plus the name of the fighter, in two dataframes, called B_fights and R_fights. We also went through each row and created an array of booleans for each side, which represented whether or not the fighter on that side one, and appended those arrays to their corresponding dataframes.

We then renamed all the columns in these two fighter dataframes to be the same, by removing the `B_` and `R_` prefixes. Once the column names were the same, we appended them together under a new dataframe, fights2. We also noticed that there were a few columns with the Stance "Open Stance", and decided to delete those as they were skewing some of the data. We also created a new dataframe that contains no fighters with 0% win rate, as these were likely the stats for fighters who had just started out, therefore skewing the data. 

*Data tidying code*

# Exploratory Data Analysis

Before we did any EDA (Exploratory Data Analysis), we had to add a few more columns for ease of plotting data. The first column we added was wins/# of fights. We found number of fights by adding the draw, wins, and losses columns, then divided wins by that number. 
*code*

We then plotted age vs. win ratio on a bar plot. This plot shows that the younger the fighter, the higher their win ratio. This would make sense, as the younger the fighter, the better they are able to perform.
*code*

Then a bar plot for stance vs. win ratio. This plot shows that the `Switch` stance often have a higher win ratio than the other two stances.
*code*

Then a bar plot for longest win streak vs. win ratio. This shows that the higher the current win streak of the fighter, the higher their win ratio usually is. This doesn't really reveal anything groundbreaking (someone who is currently on a high win streak has clearly won a lot of games, duh.), but it is interesting to see the distribution. 
*code*

In order to compare things like weight or height and significant strike percentage, we need to analyze based on weight class. This is due to the fact that in each weight class, the fighters are going to be more similar, which will amplify the differences in things like weight and height. We then split up the dataframe of data from all fighters into a few dataframes that represented fighters in the same weight class. We chose welterweight, middleweight, light heavyweight, and heavyweight to see how the win ratio of these fighters varied based on things like height and weight, which are somewhat indicative of their weight class.

For each weight class we plotted the fighters reach in centimeters vs. their significant strike percentage. Some of the classes (such as light heavyweights) show a definite trend upwards as reach increases, while others (such as welterweights) show no trend.

*codes and plots*

The last thing we plotted was a histogram of the win ratios. There is a spike in the range from .5 to .6. 
*code and plot*

# Predictions Based On Fighter Statistics

In this section, we will analyze the potential to predict both win ratio and outcome of a fight. Using linear regression, we will try to predict winning ratio, and analyze which stats best predict this. Then, using logistic regression, we will try to predict the outcome of a fight based on certain stats of the two fighters, and analyze which stats best predict this. 

## Linear Regression: Can We Predict Winning Ratio?
Before doing any linear regression, we needed to transform the stance of the fighters into an encoded variable, in order to be able to use it in linear regression. After doing so, we chose a few statistics to try to predict with: stance (encoded), height, reach, and age. 
### Null Hypothesis for Winning Ratio:
The set of four stats: stance, height, reach, and age, do not affect the winning ratio. 

*code*

We fit the model to the data and found that this model has an R-square value of .04, which means this model does not describe the variance for winning ratio. This means we accept the null hypothesis.

*code*

Here is the coefficients for each of the statistics. We cannot draw any conclusions from this, as this model does not predict the values at all. 

## Logistic Regression: Can We Predict the Outcome of a Fight?
Before we were able to do logistic regression, we had to do a bit of manipulation on the original dataframe of all fights. We first dropped all rows that had some value of NaN (not a number), as the stance columns had a couple of rows that had NaN in them. We then removed all rows with the stance Open Stance, as these entries were so few that they skewed the data. 
We then encoded the stances as we did in linear regression, except for both the Red and Blue fighters. We also encoded the winner of the fight as Red -> 0, Blue -> 1, and dropped any Draws. Lastly, we computed the win ratio for both the Red and Blue fighters, and dropped any rows where the win ratio was 0.

*code and df*

We chose the stats stance (encoded), height, reach, age, and win ratio for both fighters as the independent variables of the regression, and the encoded winner as the dependend variable.

### Null Hypothesis for Outcome:
The set of 5 stats for each fighter in a fight do not affect the outcome of a fight: stance, height, reach, age, and win ratio.

We fit the model to the data and found that this model has an R-squared of .61, which means this model predics the outcome of a fight fairly well. This means we reject the null hypothesis. 

*code*

Here is listed the statistics and their coefficients. It appears that for both corners, win ratio has the greatest effect on the outcome of the fight. 

# Conclusion
## On Predictions of Win Ratio and Fight Outcome
We found that we can predict the fight outcome with some accuracy. There is room for improvement, however, so there are likely some interaction terms that would help with prediction.
We found that the model for predicting win ratio does not seem to predict the win ratio at all. There are likely other factors that could be used, or interaction terms that would likely predict much better. 
