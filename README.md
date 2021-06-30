# Connect4
**Connect4** - AI for 2 player game via Minimax Algorithm and Alpha Beta Pruning

**Minimax Algorithm** is a **recursive backtracking** algorithm used in **decision making** and **Game Theroy**. It calculates all possible outcomes of a particular decision recursively and thereby makes the best decision. This makes it useful in designing AIs for 2 player games like Tic-Tac-Toe, Connect4, Chess, etc.

In this project I have applied this Algorithm to design an AI for the game Connect4. 
Connect4 is a 2 player game where alternate turns are played and the first player occupying 4 consecutive places horizontally, vertically or diagonally wins. 

![Gameplay of Connect4](https://upload.wikimedia.org/wikipedia/commons/thumb/a/ad/Connect_Four.gif/220px-Connect_Four.gif)


The program asks a column number (0-6) as an input in which the user wishes to play its move. The program outputs the state of the board after each move of both the user as well as the AI. The output is in the form of a 2D matrix. And when the game ends (i.e when the AI or User wins or game ends in draw) it displays the appropriate message.

The algorithm has been further **optimised with the application of ALPHA-BETA PRUNING**. This optimisation removes the unnecessary recursions based on the scoring heurestics and improves on the time complexity significantly.


**Instructions to use the code:**

To play using basic pic_best_move() version:

1. Comment out lines 333 and 334, and uncomment line 335
2. Save and simply compile the code in terminal and run the code.
3. To compile enter command: g++ -o Connect4 Connect4.cpp
4. To run enter command: ./Connect4



To play using minimax algorithm(without alpha-beta pruning) version:

1. Uncomment line 333 and 334, and comment out line 335.
2. Comment out lines 260-262 and 280-282
3. Save and simply compile the code in terminal and run the code.
4. To compile enter command: g++ -o Connect4 Connect4.cpp
5. To run enter command: ./Connect4



To play using minimax algorithm(WITH alpha-beta pruning) version:

1. Uncomment line 333 and 334, and comment out line 335.
2. Unomment lines 260-262 and 280-282
3. Save and simply compile the code in terminal and run the code.
4. To compile enter command: g++ -o Connect4 Connect4.cpp
5. To run enter command: ./Connect4

P.S.: You can even view the time taken per move by uncommenting line 347

