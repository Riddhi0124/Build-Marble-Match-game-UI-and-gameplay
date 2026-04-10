# Marble Match 🎯

A polished, interactive 2-player marble game inspired by the odd-or-even showdown from Squid Game, featuring modern UI, smooth animations, and real-time gameplay feedback.

Test your intuition, outplay your opponent, and claim all 20 marbles.

## 🚀 Live Demo

[Play Marble Match Live](https://riddhi0124.github.io/Build-Marble-Match-game-UI-and-gameplay/)

## ✨ Features

- Interactive 2-player gameplay with real-time updates
- Smooth animations for marble transfers and score changes
- Visual feedback for correct and incorrect guesses
- Clean, responsive UI with modern design
- Dark mode toggle 🌙
- Round history with clear summaries
- Input validation and edge-case handling
- Winner screen with celebration effects 🎉

## 🎮 Gameplay Rules

Each game starts with:

- Player 1: 10 marbles
- Player 2: 10 marbles

Each round:

1. The holder secretly selects a number of marbles.
2. The guesser chooses Odd or Even.
3. If correct, the holder gives the hidden marbles.
4. If wrong, the guesser gives the hidden marbles.
5. Roles switch.

🏆 The player who collects all 20 marbles wins.

## 🛠 Tech Stack

- HTML
- CSS for animations and responsive design
- JavaScript for state management and game logic

## ⚙️ Run Locally

```bash
python3 -m http.server 4173
```

Open:

```text
http://localhost:4173
```

## 🧠 What I Focused On

- Clean separation of game logic and UI
- Robust input validation and edge-case handling
- Smooth, intuitive user interactions
- Writing maintainable and readable code

## 📁 Project Structure

- `index.html` — full application (UI + logic)
- `README.md` — documentation

## 🔍 Notes

- Game logic is fully symmetric and role-based (holder vs guesser)
- Prevents invalid moves and negative marble states
- Designed to be lightweight and easy to run
