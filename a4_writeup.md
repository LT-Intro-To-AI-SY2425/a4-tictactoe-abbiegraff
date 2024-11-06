# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
        
        The most difficult part to tic-tac-toe was the has_won method because it required a logical thinking about a board and the patterns needed to check the correct spots. Ultimately it makes sense, and I feel that this was a good way to get familiar with ways to slice the list. 
        
2. Explain how you would add a computer player to the game.
        
        To add a computer player to the game, I would have a method that has the computer picks spots adjacent to its original selection. It would make sure that there was enough space in that chosen direction to get three in a row. 

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
        
        To get the computer player to play the best move every time, I think I would have it make sure that the next move was always adjacent to a previous one or blocking the three in a row from the opponent. To check this, there could be a method that every turn checks if the opponent has two aligned slots with space for a third in a row. If so, the computer would make its move there. If not, the computer would select a slot to add its next move, checking that this move was productive to gaining three in a certain direction. 