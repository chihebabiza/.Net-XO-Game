# ❌⭕ XO Game Final – Windows Forms (C#)

A fully functional 2-player **Tic-Tac-Toe (X-O)** game built using **Windows Forms** and **C#**.  
Players alternate turns, trying to align three of their symbols (X or O) horizontally, vertically, or diagonally. The game tracks the winner, highlights winning combinations, and handles draw scenarios.

---

## 🧩 Features

- 🎮 Two-player gameplay (Player 1 and Player 2)
- 🖼️ Uses images for X and O
- 🟨 Highlights winning buttons
- 🔄 Restart button to reset the game
- 📊 Tracks player turns, game progress, and winner
- 🎨 Custom board lines drawn using GDI+

---

## 🖥️ Tech Stack

- **Language:** C#  
- **Framework:** .NET Framework (WinForms)  
- **UI:** Windows Forms Designer  
- **Graphics:** GDI+ (custom board lines)

---

## 🧠 How It Works

- Buttons are assigned a `Tag` of `X`, `O`, or `?`
- Game logic checks for 8 win conditions after each turn
- Background color of winning buttons turns **GreenYellow**
- Displays the winner or shows a **"Draw"** if all cells are filled
- `Restart` button resets board, labels, and player turn

---

## 🚀 How to Run

1. Clone or download the repository:
   ```bash
   git clone https://github.com/chihebabiza/.Net-XO-Game.git

2. Open the solution in **Visual Studio**

3. Press `F5` or click **Start** to run the game

---

## 🔁 To-Do / Future Improvements

* Add sound effects for moves and win
* Add score tracking across games
* Add AI mode for single player
* Improve UI/UX with animations

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).


