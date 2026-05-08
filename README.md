# 🎮 Rock Paper Scissors Game

![HTML5](https://img.shields.io/badge/HTML5-Markup-orange?style=flat-square&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-Styling-blue?style=flat-square&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-GameLogic-yellow?style=flat-square&logo=javascript)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=flat-square)

An interactive and beginner-friendly **Rock Paper Scissors** web game developed using **HTML, CSS, and JavaScript**.

This project demonstrates core frontend development concepts such as:

- DOM Manipulation
- Event Handling
- Conditional Logic
- Random Number Generation
- Dynamic UI Updates

The player competes against the computer, and the game instantly displays the winner while updating the score dynamically.

---

# 📌 Project Overview

The objective of this project is to build a fully functional browser-based game that allows users to play Rock Paper Scissors against the computer.

The game logic follows traditional rules:

- 🪨 Rock beats Scissors
- 📄 Paper beats Rock
- ✂️ Scissors beats Paper

The project also focuses on creating a responsive and visually appealing UI using CSS.

---

# 🚀 Features

## 🎯 Gameplay Features

- Play against computer AI
- Real-time score tracking
- Random computer move generation
- Dynamic result messages
- Win/Lose/Draw detection

---

## 🎨 UI Features

- Clean and modern interface
- Hover effects on choices
- Responsive layout
- Circular game icons
- Color-changing result messages

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure of the game |
| CSS3 | Styling and layout |
| JavaScript | Game logic and interactivity |

---

# 📂 Project Structure

```bash
rock-paper-scissors-game/
│
├── index.html
├── style.css
├── app.js
└── images/
    ├── rock.png
    ├── paper.png
    └── scissors.png
```

---

# 📄 File Description

## 1️⃣ index.html

Contains:
- Game layout
- Scoreboard
- Choice buttons
- Message container

Main sections:
- Header
- Choices section
- Scoreboard
- Result message

---

## 2️⃣ style.css

Handles:
- Page styling
- Layout positioning
- Flexbox alignment
- Hover animations
- Typography
- Responsive design

Key concepts used:
- Flexbox
- Border Radius
- Hover Effects
- Background Colors

---

## 3️⃣ app.js

Contains the complete game logic.

### Major Functions

| Function | Purpose |
|---|---|
| `genCompChoice()` | Generates random computer choice |
| `drawGame()` | Handles draw situations |
| `showWinner()` | Displays game result |
| `playGame()` | Main game logic |

---

# ⚙️ Working Process

## Step 1 — User Selects Move

The player clicks:
- Rock
- Paper
- Scissors

Using:
```javascript
choice.addEventListener("click", () => {})
```

---

## Step 2 — Computer Generates Random Choice

JavaScript randomly selects:

```javascript
const options = ["rock", "paper", "scissors"];
```

---

## Step 3 — Winner Logic Executes

The game compares:
- user choice
- computer choice

Using conditional statements.

---

## Step 4 — Result Displayed

The game displays:
- Winner
- Loser
- Draw

And updates:
- User Score
- Computer Score

---

# 🧠 JavaScript Concepts Used

- Variables
- Arrays
- Functions
- Arrow Functions
- Event Listeners
- DOM Manipulation
- Conditional Statements
- Ternary Operators
- Random Number Generation

---

# 🎮 Game Rules

| User Choice | Beats |
|---|---|
| Rock | Scissors |
| Paper | Rock |
| Scissors | Paper |

---

# 📸 UI Preview

```text
--------------------------------
|      ROCK PAPER SCISSORS     |
--------------------------------

     [Rock] [Paper] [Scissors]

         You: 0   Computer: 0

         Play Your Move
```

---

# 🔥 Core JavaScript Logic

## Random Computer Choice

```javascript
const genCompChoice = () => {
    const options = ["rock", "paper", "scissors"];
    const randomIdx = Math.floor(Math.random() * 3);
    return options[randomIdx];
};
```

---

## Winner Determination Logic

```javascript
if (userChoice === "rock") {
    userWin = compChoice === "paper" ? false : true;
}
```

---

# ⚙️ Installation & Setup

## Clone Repository

```bash
git clone https://github.com/your-username/rock-paper-scissors-game.git
```

---

## Open Project

Open `index.html` in any browser.

---

# 🌐 Browser Compatibility

- Google Chrome
- Microsoft Edge
- Firefox
- Brave

---

# 📈 Future Enhancements

- 🔊 Sound effects
- 🌙 Dark mode
- 🎞️ Smooth animations
- 📱 Mobile responsiveness improvements
- 🧑‍🤝‍🧑 Multiplayer support
- 🏆 Match history tracking
- ⏱️ Timer mode

---

# 🎯 Learning Outcomes

Through this project, you can learn:

- Frontend web development basics
- DOM manipulation
- JavaScript event handling
- Building interactive UI
- Game logic implementation

---

# 👩‍💻 Author

## Anuradha Vishwakarma

### Skills
- Java Development
- Frontend Development
- SQL & Data Analysis
- Python Programming

---

# ⭐ Support

If you like this project:

- ⭐ Star the repository
- 🍴 Fork the project
- 🛠️ Contribute improvements

---

# 📜 License

This project is open-source and available for learning purposes.
