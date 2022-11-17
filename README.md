# mlb-predictions
Using data from the 2022 MLB season, train and test a machine learning model that predicts whether or not a team will win or lose a game


Baseball Statistic Glossary:
Home_Away: Location of the game. 0 = Home Game, 1 = Away Game
Opp: Opposing Team
W/L: 1 = Win, 0 = Loss
W-L: Cumulative Win Loss Record
R: Runs Scored by a teams offense
RA: Runs Allowed by a teams defense
Rank: Ranking in a 5 team division. (1 is highest, 5 is lowest)
D/N: 0 = Day, 1 = Night
Streak: Teams current streak, positive is wins in a row, negative is losses in a row
Runs_Scored: Cumulative Runs Scored 
Runs_Allowed: Cumulative Runs Allowed
RD: Run Differential
Win_Total: Cumulative Wins


# Cleaning and Processing PyBaseball Data
Mariners data was acquired using the schedule_and_record module from pybaseball.
This dataset offers historical data from the Mariners 2022, however not all of the data was relevent. 
The following columns were dropped from the dataset due to irrelevancy:
    Inn (# of innings)
    W-L (Cumulative Record)
    GB (Games behind first place)
    Time (Length of Game)
    Attendance (Number of fans in attendance)
    CLi (Championship Leverage Index)
    Orig Schedule (Original Schedule)
The following columns were dropped due to providing too much predictive value:
    R (Number of runs scored by the Mariners)
    RA (Number of runs scored by the Mariners opponents)
    These two numbers togethor provide the final score of the game.
Cleaning:
Due to the nature of the dataset we needed to convert some strings into integers:
    W (Win) was converted to 1, L (Loss) was converted to 0. W-wo (Walk off win) converted to 1, L-wo (Walk off loss) converted to 0
    D (Day) was converted to 0, N (Night) was converted to 0. 
    @ (Away) was converted to 1, Home was converted to 0.
OneHotEncoder was used on the dataset to convert text fields into useable numerical data. (Opp/Win/Loss/Save)
