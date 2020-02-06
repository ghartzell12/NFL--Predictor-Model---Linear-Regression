# NFL--Predictor-Model---Linear-Regression
This is my first Python project used to teach me how to work with Regression, Python, and sklearn. It incorporates statistics from the last 20 years of NFL games, including team attributes which are used to forecast the total points in that game. Rather simple, this Linear Regression model utilizes simple Machine Learning strategies to produce output based on past statistics. 

# Data Collection
The data that was collected above can be seen in the two csv files "historical_teams" and "game_data". Historical data is read as a dictionary of teams, with each key being defined as the Concatenation of both the team name and year, example "ARI2002". Each key's definition resembles a list of its attributes, such as yards/passing attempt. One each of these keys are processed, we load in the game data. Each game calls one of these keys for both teams as well as passes in individual weather data for the game, such as wind speed. Each value of the key's definition is pssed in as a training input alongside the individualied wether data.

# Regression
Since it was simply a starter regression model, I decided it was best to utilize the simplest method of regression: Linear Regression. I pass each value for each team as a training input and the total points scored by each team as the training output. I trained the model utilizing regression algorithms. 

# Conclusion
After completing this project, I feel that I am beggining to develop a more complex understanding of Python and Sklearn. I lan to utilize this ideas in a more complex model for algorithmic swing trading through the zipline API.


