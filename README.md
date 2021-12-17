# Team ERA and its Effect on Winning
This Repo is the final project for our Data Science class at Lafayette College. It investigates the effect Team Earned Run Average has on total wins.

# Business Understanding

# Data Understanding
Our data came from Baseball Reference, which is a website that has play-by-play statistics for every game dating back to the 1960s. We utilized their database to access team batting and pitching statistics for the years 1985-2016.

Our Variables:

yearid: Ordinal

teamid: Interval

game_t: Interval

win_t: Interval

era_t: Ratio

teamname: Nominal

teamOPS: ratio

wswin_t: Nominal

run_t: Interval

hit_t: Interval

hr_t: Interval

bb_t: Interval

so_t: Interval

runallow_t: Interval

earnrun_t: Interval

save_t: Interval

errors_t: Interval

Link to Baseball Reference:

https://www.baseball-reference.com
# Data Preperation
To prep for our project, we cleaned that data by dropping variables we didn't need such as some advanced statistics like OPS+ and other irrlevant statistics like CS. All in all we ended up with 918 observations with 17 variables.

# Exploratory Data Analysis

era_t	teamOPS	win_t
count	918.000000	918.000000	918.000000
mean	4.205000	0.738863	79.943355
std	0.556509	0.041072	11.840224
min	2.910000	0.627000	43.000000
25%	3.800000	0.710000	71.250000
50%	4.170000	0.737000	80.000000
75%	4.580000	0.766000	89.000000
max	6.380000	0.851000	116.000000

# Machine Learning Model

# Comclusions

# Run Notebook In Google Collab

# Link to Video


