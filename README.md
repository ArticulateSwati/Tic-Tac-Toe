# Tic-Tac-Toe
🎮 Tic Tac Toe Game

A simple, interactive, and visually attractive Tic Tac Toe game built using HTML, CSS, and JavaScript.

The game features a beautiful pink-themed interface, animated heart decorations, winner detection, draw detection, and options to start a new game or reset the current game.

🌐 Live Demo

🚀 Coming Soon

The live version of this project will be available here after deployment.

✨ Features
🎯 Classic 3×3 Tic Tac Toe gameplay
❌ Two-player game using O and X
🏆 Automatic winner detection
🤝 Draw detection when no player wins
🎉 Winner announcement message
🔄 New Game functionality
🔁 Reset Game functionality
💗 Attractive pink gradient theme
❤️ Animated floating heart background
✨ Smooth hover effects
📱 Responsive design
🛠️ Technologies Used
Technology	Purpose
HTML5	Structure of the game
CSS3	Styling, animations, and responsive design
JavaScript	Game logic and functionality
📁 Project Structure
TicTacToe/
│
├── index.html
├── style.css
├── basic.js
└── README.md
🎮 How to Play
1 The game starts with O.
2 Player 1 selects an empty box to place O.
3 Player 2 selects an empty box to place X.
4 Players take turns placing their symbols.
5 The first player to get three matching symbols in a row wins.
6 A player can win horizontally, vertically, or diagonally.
7 If all boxes are filled and no player wins, the game is declared a draw.
8 Click New Game or Reset Game to play again.

🏆 Winning Patterns

The game checks all possible winning combinations:

0 | 1 | 2
--|---|--
3 | 4 | 5
--|---|--
6 | 7 | 8
Possible Winning Combinations
const winPatterns = [
  [0, 1, 2],
  [0, 3, 6],
  [0, 4, 8],
  [2, 4, 6],
  [1, 4, 7],
  [2, 5, 8],
  [3, 4, 5],
  [6, 7, 8],
];
🎬 Demo
Game Flow
        TIC TAC TOE

        O | X | O
       ---|---|---
        X | O | X
       ---|---|---
        X | O | O

     🎉 Winner is O!

The game automatically checks for a winner after every move.

If all nine boxes are filled and no winning pattern is found:

🤝 Game is Draw!
🚀 How to Run the Project
Option 1: Run Locally
Download or clone this repository.
Open the project folder.
Open index.html in any modern web browser.
Start playing! 🎮
Option 2: Using VS Code
Open the project folder in Visual Studio Code.
Install the Live Server extension.
Right-click on index.html.
Select Open with Live Server.
Enjoy the game in your browser.
💡 Future Improvements

Some features that can be added in the future:

🤖 Single-player mode with AI
🔊 Sound effects
📊 Score tracking
👤 Player name input
🌙 Dark mode
🎨 Multiple color themes
📱 Enhanced mobile support
🏅 Game history
👩‍💻 Author

Swati

GitHub: @ArticulateSwati

⭐ Support

If you like this project, please consider giving the repository a star ⭐.

Made with ❤️ using HTML, CSS, and JavaScript
