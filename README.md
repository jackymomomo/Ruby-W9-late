# Ruby_W9
Compass work for W9
Task 1: Extract Nouns for Classes
Game
Player
Math Question
Task 2: Write their roles
Game: The Game class will manage the overall flow of the game. It will contain the game loop, which will handle each player's turn and keep track of the current player. It will also keep track of the score and remaining lives for each player.
Player: The Player class will represent each player in the game. It will store the player's name, current score, and remaining lives. It will also have methods to answer math questions and lose lives if the answer is incorrect.
Math Question: The Math Question class will generate new addition questions for each turn by selecting two random numbers between 1 and 20. It will also check whether the player's answer is correct or not.
Public methods for each class:
Game:
start_game(): Initializes the game and starts the game loop.
next_turn(): Handles the logic for the next turn, including generating a new math question and checking the answer.
end_game(): Ends the game and displays the final scores.
Player:
answer_question(answer): Takes a player's answer to the current math question and checks whether it is correct or not. If the answer is correct, the player's score will be increased. If the answer is incorrect, the player will lose a life.
is_alive(): Returns a boolean value indicating whether the player has any lives remaining.
Math Question:
generate_question(): Generates a new addition question by selecting two random numbers between 1 and 20.
check_answer(answer): Takes a player's answer to the current math question and checks whether it is correct or not.
Class responsibilities:
The Game class will contain the game loop and manage the overall flow of the game.
The Player class will represent each player in the game and manage their score and lives.
The Math Question class will generate new questions and check player answers.
Which class will contain the game loop? The Game class will contain the game loop.
Which class should manage who the current player is? The Game class should manage who the current player is.
Which class(es) will contain user I/O and which will not have any? The Game and Player classes will contain user I/O, while the Math Question class will not have any.

