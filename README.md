# Rock-Paper-Scissor-game

getPlayerChoice(): This function prompts the user to choose between "rock", "paper", or "scissors". If the user enters an invalid choice, the function will automatically choose "rock" for them.
getComputerChoice(): This function randomly generates a choice of "rock", "paper", or "scissors" for the computer.
getWinner(): This function takes the computer's choice and the user's choice as input and returns the winner of the round. The winner is determined by the following rules:
If the computer's choice and the user's choice are the same, the game is a draw.
If the computer's choice beats the user's choice (rock beats scissors, scissors beats paper, paper beats rock), the computer wins.
If the user's choice beats the computer's choice, the user wins.
startGameBtn.addEventListener(): This function listens for a click event on the start-game-btn element. When the button is clicked, the function calls the getPlayerChoice(), getComputerChoice(), and getWinner() functions to start a new round of the game.
