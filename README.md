# Red_Blue_Nim_Game

The code defines the minimax algorithm for playing the red-blue marble game. The minimax algorithm is a decision-making algorithm that evaluates all possible moves and their outcomes, and selects the move that leads to the best outcome for the player.

The max_value() function determines the best possible outcome for the maximizing player (in this case, the computer player), and the min_value() function determines the best possible outcome for the minimizing player (in this case, the human player).

Both functions take as input the current state of the game, the alpha and beta values for pruning the search tree, the depth limit for the search (if any), and the current depth of the search tree.

The functions perform a recursive search of the game tree, evaluating each possible move and outcome until the maximum depth is reached or a terminal state is reached (i.e. the game is over).

The evaluate_state() function is used to assign a score to each terminal state. If the red player wins, the function returns 1. If the blue player wins, the function returns -1. If the game is a tie, the function returns 0.
