# Deposit-Mania

Welcome to the Deposit-Mania Game! This is a simple console-based slot machine game where players deposit money, place bets, and spin to win.

Features
Deposit money to start the game.
Choose the number of lines to bet on (1-3).
Place your bet per line.
Spin the slot machine and see if you win!
Continue playing as long as you have money left.
Getting Started
Prerequisites
Node.js installed on your computer.
Installation
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/swapna-WD/deposit-game.git
Navigate to the project directory:
bash
Copy code
cd deposit-mania
Install the required packages:
bash
Copy code
npm install
Running the Game
To start the game, run the following command in your terminal:

bash
Copy code
node index.js
How to Play
Deposit: Enter the amount of money you want to deposit to start playing.
Choose Lines: Select the number of lines you want to bet on (1-3).
Place Bet: Enter your bet per line.
Spin: The reels will spin and display the result.
Check Winnings: If you have matching symbols on a line, you win based on the symbol values.
Continue or Quit: You can choose to play again as long as you have money left.
Symbol Values
Symbol	Count	Value
A	2	5
B	4	4
C	6	3
D	8	2
Code Overview
deposit(): Function to handle the deposit amount input.
getNumberOFLines(): Function to get the number of lines to bet on.
getBet(balance, lines): Function to get the bet amount per line.
spin(): Function to simulate the spinning of the slot machine.
transpose(reels): Function to transpose the reels for easier display.
printRows(rows): Function to print the rows of the slot machine.
getWinnings(rows, bet, lines): Function to calculate the winnings.
game(): Main game function that handles the game loop.
Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
