RevELO
======
Author: Rishi Ghosh 

A LiveCode implementation of the ELO Player Rating system. The single function below handles all aspects of calculating the new ELO ratings for both players.




newRatings [function]
-------------
+   Description: Returns an array with keys "Player1" and "Player2" holding corresponding new ELO ratings.
+   Examples: No examples yet.
+   Parmeters: 
    +   pPlayer1Rating: Rating of Player1 right before match.
    +   pPlayer2Rating: Rating of Player2 right before match.
    +   pKVal: The constant K-value used in developers ELO system. Read the wikipedia article on ELO for details.
    +   pResult: The result of the match on a scale of 0 to 1. "0" = Player1 lost, Player 2 won. "0.5" = Draw. "1" = Player 1 won, Player 2 lost.


