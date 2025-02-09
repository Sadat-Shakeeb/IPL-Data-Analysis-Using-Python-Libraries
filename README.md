# IPL Data Analysis Project
Welcome to the IPL Data Analysis Project! This project delves into the depths of the Indian Premier League (IPL) dataset using powerful Python libraries like NumPy and Pandas. We've embarked on a journey from basic to advanced analytical questions to uncover intriguing insights about teams, players, and matches over the years.

![](https://github.com/Sadat-Shakeeb/IPL-Data-Analysis-Using-Python-Libraries/blob/main/155-1559535_ipl-logo-png-2018.png?raw=true)

# Introduction
The Indian Premier League has revolutionized the game of cricket, blending sports and entertainment to create a captivating spectacle. This project aims to analyze the IPL's rich dataset to answer compelling questions, providing valuable insights into team dynamics, player performances, and the intricacies of the game.

# Dataset
We utilized comprehensive IPL datasets that include detailed information on matches, players, teams, and seasons. The data encompasses everything from ball-by-ball actions to overall team statistics.

Matches Dataset: Contains detailed records of each match played.

Deliveries Dataset : Provides ball-by-ball details for granular analysis.

# Note: Ensure compliance with data usage policies when handling and sharing the datasets.
# Note: Dataset links is provided in respective .ipynb file accordingly

# Sample Analytical Questions On IPL Matches Dataset
1. Player with Most Appearances in Final Matches
Identified the player who has featured in the most IPL final matches, highlighting consistent performers who have made significant impacts in crucial games.

2. Team Performance DataFrame
Created a comprehensive DataFrame for each team, detailing:

   Team Name

   Matches Played

   Win Percentage

   Home Win Percentage

   Away Win Percentage

This allows us to compare team performances across different conditions and identify strengths and weaknesses.

3. Team vs Team Dashboard
Developed a function to analyze the head-to-head records between any two given teams:

Overall Win-Loss Record

Player with Most 'Player of the Match' Awards in these encounters

This interactive dashboard provides insights into team rivalries and key players who influence outcomes.

4. Last Match Played by Virat Kohli in Delhi
Analyzed the dataset to find the most recent match played by Virat Kohli in Delhi, offering a glimpse into his performance at specific venues.

5. IPL Points Table Function
Implemented the point_table function which generates the points table for any specified season, featuring:

   Team Name

   Matches Played

   Matches Won

   No Result

   Points

6. Toss Winner as Match Winner Percentage
Calculated the percentage of matches where the toss winner also won the match, providing insights into the potential impact of winning the toss.

7. Player with Most Player of the Match Awards in Finals and Qualifiers
Identified the player with the most "Player of the Match" awards in finals and qualifier matches, highlighting clutch performers in high-stakes games.

8. CSK Wins in Kolkata
Determined the number of matches won by Chennai Super Kings (CSK) in Kolkata, offering insights into the team's performance at specific venues.

The table is sorted in non-ascending order of points and ascending order of team names for clarity.


# Sample Analysis On Deliveries Dataset

# Analysis and Questions
The project aims to answer several key questions about IPL performance.  Below are some of the questions explored in the analysis:

# Batsman Performance
Highest Score While Chasing: Identify the batsman with the highest individual score in a successful chase.
Best Strike Rate While Chasing: Find the batsman with the best strike rate while chasing, having faced at least 100 balls.
Batsman Record Season Wise: Create a function that takes a batsman's name as input and returns a DataFrame with their season-wise performance. The DataFrame includes columns like Season, Innings, TotalRuns, Avg, HighestScore, and StrikeRate. The Season column is set as the index. The average is calculated as total_runs / number of times dismissed, and the strike rate as (total_runs / balls faced) * 100. Special attention is given to handling extras like wides and no-balls.

# Bowler Performance
Most Successful Bowler Against Any Batsman: Determine the bowler-batsman pair with the most dismissals or other relevant metric indicating success.
Purple Cap Holder Each Season: Identify the Purple Cap holder (most wickets) for each IPL season. In case of a tie in wickets, the bowler with the best economy rate wins the Purple Cap.
Best Bowler in Death Overs: Find the best bowler in the death overs (16-20). The criteria are most wickets taken, and in case of a tie, the bowler with the lowest economy rate in death overs is preferred.


# Partnerships and Match Data
Most Successful Batting Pair: Identify the batting pair that has scored the most runs together in IPL history.
Batting Pairs DataFrame: Create a DataFrame listing all batting pairs, along with their combined runs, average, and strike rate. The columns are Batsman1, Batsman2, Runs, Avg, and StrikeRate.
Match Performance Summary: Create a DataFrame summarizing each match with PlayerOfThematch, BattingFigure, and BowlingFigure. BattingFigure is in the format <runs>/<balls>, and BowlingFigure is in the format <wickets>/<runs-conceded>. If a player didn't bat or bowl, the corresponding figure is NaN.
