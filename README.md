# Svelte Matching Game

This project is a fun and interactive memory matching game built using Svelte. It's designed to challenge your memory and attention to detail through a grid of emoji cards that you must match in pairs. The game includes features like a countdown timer, game states (start, playing, paused, won, lost), and dynamic interaction based on user inputs.

## Credits

This game was inspired by a tutorial from [Joy Of Code](https://joyofcode.xyz/svelte-matching-game). A big thanks to them for their clear and informative guide on building interactive games with Svelte.

## Getting Started

To set up and run this project locally, follow these steps:

```bash
# Clone the project
git clone <repository-url>

# Navigate to the project directory
cd path-to-your-project

# Install dependencies
npm install

# Start the development server
npm run dev -- --open
```

Game Mechanics
Start Game: Press the 'Play' button to start the game.
Gameplay: Click on cards to turn them over and try to find matching pairs.
Pause/Resume: Press the 'Escape' key to pause the game. Press it again to resume.
Win/Lose Conditions: Match all pairs before the time runs out to win. The game ends if the timer reaches zero.
Development
This project is set up using create-svelte. Here are some commands you might find useful:

```bash
# Start the development server and open the app in a new browser tab
npm run dev -- --open

# Build the app for production
npm run build

# Preview the production build
npm run preview
```

Feel free to modify, extend, and improve the game to your liking. Enjoy coding and playing your Svelte-based matching game!