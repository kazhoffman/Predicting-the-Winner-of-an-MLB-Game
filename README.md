# Predicting-the-Winner-of-an-MLB-Game
The code provided asks for the user input of two MLB teams and produces a winner of a theoretical game between the two using data from the 2022 and 2021 seasons. 
All of the data needed to run the program is provided within the wrapper, so there is no need to reference an outside database in a different directory. 
To use this program, you will need to start by downloading the R file provide named "PredictingWinner.r".
You should be able to open the file in your R program and call the function "match()" thats held within.
After calling, you should be given a list of the available teams to enter as labeled within the database.
It is important to enter the team name as given or you will be continually prompted to reenter the team.
After entering both the home team and the away team, you will be given your winner!
Winners are produce by picking the higher ranked team from a predictive ranking system for the 2022 season, however 20% of the time the result will be flipped to add some randomness.
The model that I used to predict the teams ranking for 2022 works with 98% accuracy, but be warned that only 11 were exact matches and 19 were not.
The ones that were not exact matches were very close to the exact 2022 rankings being just 1 to 2 spots off high or lower. 
However, predicting the winner of a baseball game involves much more than just saying that the higher ranked team wins in reality.
I would not use this model to aid with betting or any sorts, it is a start but would need much more added like evaluating a teams given lineup.
This project was not meant to be entirely accurate, but it is a fun function to use and starts the base for a larger more accurate program.
