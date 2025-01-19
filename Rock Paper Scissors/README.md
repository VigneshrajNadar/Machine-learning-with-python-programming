### Assignment

For this challenge, we will create a program to play Rock, Paper, Scissors. A program that picks at random will usually win 50% of the time. To pass this challenge our program must play matches against four different bots, winning at least 60% of the games in each match.

In the file `RPS.py` we have to  provided with a function called `player`. The function takes an argument that is a string describing the last move of the opponent ("R", "P", or "S"). The function should return a string representing the next move for it to play ("R", "P", or "S").

A player function will receive an empty string as an argument for the first game in a match since there is no previous play.

The file `RPS.py` shows an example function that we will need to update. The example function is defined with two arguments (`player(prev_play, opponent_history = [])`). The function is never called with a second argument so that one is completely optional. The reason why the example function contains a second argument (`opponent_history = []`) is because that is the only way to save state between consecutive calls of the `player` function. You only need the `opponent_history` argument if you want to keep track of the opponent_history.

    
