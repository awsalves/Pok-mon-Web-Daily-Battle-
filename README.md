# Pokémon Web Daily Battle
[![Ask DeepWiki](https://devin.ai/assets/askdeepwiki.png)](https://deepwiki.com/awsalves/Pok-mon-Web-Daily-Battle-)

Step into the arena and test your luck in this nostalgic, web-based Pokémon battle simulator. This project is a self-contained game built with pure HTML, CSS, and vanilla JavaScript that lets you participate in a daily Pokémon tournament directly in your browser.

## Features

- **Daily Tournament:** Engage in a daily tournament where you must win three consecutive battles to be crowned the champion. Your progress is tracked for the day.
- **Randomized Encounters:** Each battle is a new surprise! Both your Pokémon and your opponent are randomly selected from the original 151 Pokémon.
- **Dynamic Movesets:** Your Pokémon is assigned four random moves for each battle, forcing you to adapt your strategy on the fly.
- **Authentic Battle Logic:** Experience a turn-based combat system inspired by the classic games. The system includes:
    - Speed-based turn order.
    - Same-Type Attack Bonus (STAB).
    - Type effectiveness calculations.
    - Move accuracy.
- **Local Progress Tracking:** Your daily tournament win count is saved in your browser's `localStorage`.
- **Retro Aesthetics:** Enjoy a classic battle interface with animated sprites and sound effects sourced from Pokémon Showdown, bringing the duels to life.

## How to Play

1.  Clone or download this repository.
2.  Open the `index.html` file in any modern web browser.
3.  A battle will load automatically, assigning you and an opponent a random Pokémon.
4.  Select a move from the four options to attack.
5.  Defeat three opponents in a row to win the daily tournament. If you lose a single battle, your run is over for the day!

## Technical Implementation

This project is a standalone application contained within a single `index.html` file. It leverages client-side JavaScript to manage all game logic.

It dynamically fetches all necessary data at runtime from public APIs:
-   **PokéAPI:** Used to retrieve Pokémon stats, types, and move data.
-   **Pokémon Showdown:** Used for animated sprites and audio cries to enhance the visual and auditory experience.
