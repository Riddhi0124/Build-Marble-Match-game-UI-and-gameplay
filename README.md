# Marble Match

A polished 2-player marble game inspired by the odd-or-even showdown from *Squid Game*.

Players take turns hiding marbles and guessing parity. One correct read can swing the match, and the game ends only when one player owns all 20 marbles.

## Live Concept

- Modern single-file build with HTML, CSS, and JavaScript
- Responsive layout for desktop and laptop screens
- Animated marble transfers, score feedback, and win celebration
- Dark mode toggle
- Round history with clear payer/receiver summaries

## Gameplay Rules

Each game starts with:

- Player 1: 10 marbles
- Player 2: 10 marbles
- Total marbles in play: 20

Every round:

1. One player is the **holder** and secretly chooses how many marbles to hide.
2. The other player is the **guesser** and guesses whether that number is **Odd** or **Even**.
3. If the guess is correct:
   the **holder** gives that many marbles to the **guesser**.
4. If the guess is wrong:
   the **guesser** gives that many marbles to the **holder**.
5. Roles switch for the next round.

The winner is the player who ends up with all 20 marbles.

## Features

- Clean separation between game logic and UI rendering
- Input validation for illegal hidden-marble amounts
- Prevents transfers a player cannot afford
- Round counter
- Restart flow
- Styled game log/history
- Winner screen with confetti
- Micro-interactions, hover states, and processing feedback

## Run Locally

If you already have Python installed:

```bash
python3 -m http.server 4173
```

Then open:

```text
http://localhost:4173
```

## Project Structure

This project is intentionally lightweight:

- `index.html` — the full app, including layout, styles, animations, state, and game logic
- `README.md` — project overview and setup notes

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript

## Notes

- The marble transfer logic is symmetric and depends only on the current **holder**, **guesser**, hidden amount, and guess result.
- The UI is built in a single file to keep the project easy to run and review.
