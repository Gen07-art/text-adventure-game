# Text Adventure Game

A text-based adventure game built in Python, where the player navigates a series of connected locations, makes choices that affect their score, and ultimately wins or loses based on points earned and decisions made along the way.

## Gameplay Overview

- Navigate through 13 connected locations using directional commands (North, South, East, West)
- Make choices at key points in the story that award or cost points
- Solve a three-part riddle challenge to earn a major point bonus
- Face a final dice-guessing challenge with up to three guesses and high/low hints
- Win or lose based on total points accumulated by the end of the journey

## How to Play

```bash
python text_based_game.py
```

Follow the on-screen prompts. At each location, you'll be shown available directions — type one to move, or type `Exit` to quit at any time.

## Project Origin

Originally built as a group project (team of 3) in Google Colab, converted here into a standalone Python script.

## Tech Stack

Python (standard library only — uses the `random` module for the dice-roll finale)
