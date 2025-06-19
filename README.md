# Tic-Tac-Toe

This project is a console-based Tic-Tac-Toe game written in C where a player competes against the computer. 
The game offers two difficulty levels: Human (standard) and God mode (impossible to beat). 
The program uses a simple 3x3 grid to represent the game board and provides a clean and interactive interface, updating the board after each move and displaying real-time scores for wins, losses, and draws.
The game logic randomly selects who plays first, and alternates turns between the player (X) and the computer (O). 
The computer's move logic includes strategies such as winning immediately, blocking the player, occupying the center, taking corners, or choosing the first available move, depending on the selected difficulty. 
The God mode difficulty uses a more advanced decision-making approach to ensure optimal play, making it nearly unbeatable.
The board is displayed in a formatted style using symbols and dividers, and the screen is cleared and redrawn after every turn for a smooth user experience. 
The game also keeps track of wins and draws using a Score struct and prompts the user to play again after each round. 
This project showcases handling 2D arrays, user input validation, control flow, and simple AI logic—all in a well-structured C program that's both fun and challenging to play.
