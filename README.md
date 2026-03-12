solution needs to meet the requirements listed below:

- You limit the depth of the search based on the difficulty of the player doing the searching.

- You implement a reasonable heuristic evaluation function to score non-leaf nodes. The method implementing the function needs to describe (in the comments) your motivation for each of the rules you're using to calculate the score. You should have at least two scenarios you check for plus a default score if the configuration doesn't match any of your scenarios.

- In each game, the number of bins and the number of teddy bears per bin are selected randomly using the appropriate game constants.

- The first player making a move alternates for each game. In other words, Player 1 makes the first move in the first game, Player 2 makes the first move in the second game, and so on.

- You collect and display data for 100 games each of easy vs easy, medium vs medium, hard vs hard, easy vs medium, easy vs hard, and medium vs hard. Display the total wins for each player for each of those combinations in a separate scene you move to once all the games are done. Make the GameConstants.AiThinkSeconds equal to 0.01f to make that data collection go quickly so you can see the results quickly. My "between game delay" was so short that I didn't see the game over message at the end of each game until the last game; that's fine.    
