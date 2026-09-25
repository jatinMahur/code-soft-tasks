# code-soft-tasks
# 🎮 Tic Tac Toe

A simple and interactive **Tic Tac Toe** game built using **HTML, CSS, and JavaScript**.
The game allows two players to play Tic Tac Toe in a clean and user-friendly interface.

## 📌 Project Overview

Tic Tac Toe is a classic two-player game played on a **3 × 3 grid**.

* Player 1 plays as **X**
* Player 2 plays as **O**
* Players take turns placing their symbol in an empty box.
* The first player to get **three symbols in a row** wins.
* The game can also end in a **draw** when all boxes are filled without a winner.

## ✨ Features

* 🎮 Two-player gameplay
* ❌ X and O turns
* 🏆 Automatic winner detection
* 🤝 Draw detection
* 🔄 Reset game button
* 🎨 Simple and responsive interface
* ✨ Winning-line animation
* 🎉 Winner animation using GIF
* ⚡ Fast and lightweight
* 🌐 Runs directly in a web browser

## 🛠️ Technologies Used

| Technology | Purpose                     |
| ---------- | --------------------------- |
| HTML5      | Creates the game structure  |
| CSS3       | Styling and layout          |
| JavaScript | Game logic and interactions |
| GIF        | Winner/game animation       |

## 📂 Project Structure

```text
Tic-Tac-Toe/
│
├── index.html
├── style.css
├── script.js
├── excited.gif
└── README.md
```

## 🚀 How to Run the Project

### Method 1: Using a Browser

1. Download or clone this project.
2. Open the project folder.
3. Double-click `index.html`.
4. The game will open in your default browser.

### Method 2: Using VS Code

1. Open **Visual Studio Code**.
2. Open the Tic Tac Toe project folder.
3. Make sure these files are present:

```text
index.html
style.css
script.js
excited.gif
```

4. Open `index.html`.
5. Right-click inside the file.
6. Select **Open with Live Server**.

The game will then open in your browser.

## 🎯 How to Play

1. The game starts with **Player X**.
2. Click any empty square.
3. The turn changes to **O**.
4. Players continue taking turns.
5. Get three matching symbols in:

   * Horizontal row
   * Vertical column
   * Diagonal

### Example Winning Pattern

```text
X | X | X
---------
O | O | 
---------
  |   |
```

Here, **X wins** because X has three symbols in a horizontal row.

## 🏆 Winning Conditions

There are 8 possible winning combinations:

```text
0 1 2
3 4 5
6 7 8
```

### Rows

```text
0 1 2
3 4 5
6 7 8
```

### Columns

```text
0 3 6
1 4 7
2 5 8
```

### Diagonals

```text
0 4 8
2 4 6
```

JavaScript checks these combinations to determine whether a player has won.

## 🔄 Reset Button

The **Reset** button allows players to start a new game.

When the reset button is clicked:

* The board becomes empty.
* The current player is reset.
* The winner status is cleared.
* The game starts again.

## 🧠 Game Logic

The JavaScript controls the main functionality of the game.

The basic flow is:

```text
Start Game
    ↓
Player X's Turn
    ↓
Player Clicks a Box
    ↓
Place X
    ↓
Check Winner
    ↓
Winner?
 ┌──┴──┐
Yes    No
 ↓      ↓
Win   Change Turn
        ↓
      Player O
        ↓
   Continue Game
```

If all boxes are filled and nobody wins, the game ends in a **draw**.

## 💡 Future Improvements

The project can be extended with additional features:

* 🤖 Add an AI opponent
* 🧠 Implement Minimax algorithm
* 👤 Add single-player mode
* 🏆 Add score tracking
* 🌙 Add dark mode
* 🔊 Add sound effects
* 📱 Improve mobile responsiveness
* 🎨 Add multiple themes
* 💾 Store scores using Local Storage
* 🌐 Add online multiplayer
* ⏱️ Add a game timer

## 📚 Learning Outcomes

By creating this project, you can practice:

* HTML structure
* CSS Flexbox/Grid
* JavaScript DOM manipulation
* JavaScript event listeners
* Arrays
* Conditional statements
* Functions
* Game logic
* Event handling
* Responsive web design

## 👨‍💻 Author

**Jatin Mahur**

B.Tech Computer Science Engineering Student

### Skills

* Java
* JavaScript
* HTML
* CSS
* React
* Node.js
* AI & Generative AI

## 📄 License

This project is created for **learning and educational purposes**.

You are free to modify and improve the project for your own learning and portfolio.

---

⭐ **If you like this project, consider improving it by adding an AI opponent using the Minimax algorithm!**
