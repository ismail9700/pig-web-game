# Pig Game

A fun and interactive web-based Pig Game implemented with HTML, CSS, and JavaScript. This classic dice game allows two players to take turns rolling a die, aiming to reach a target score without losing their turn by rolling a 1.

## Table of Contents
- [Description](#description)
- [Features](#features)
- [How to Play](#how-to-play)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Description
The Pig Game is a simple yet engaging two-player dice game where players take turns rolling a single die to accumulate points. The goal is to reach a predetermined score (default is 100) to win. If a player rolls a 1, they lose their current turn score and pass the turn to the other player.

## Features
- Two-player gameplay with turn-based mechanics
- Real-time score tracking for both players
- Option to "hold" current score or continue rolling
- Responsive design for mobile and desktop
- Visual feedback for dice rolls and game state

## How to Play
1. Open the game in your browser.
2. Players take turns rolling the die by clicking the "Roll Dice" button.
3. Each roll adds to the player's current turn score, unless a 1 is rolled.
4. If a 1 is rolled, the current turn score is lost, and the turn switches to the other player.
5. Click "Hold" to add the current turn score to your total score and pass the turn.
6. The first player to reach 100 points (or a custom target score) wins!

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ismail9700/pig-game.git
   ```
2. Navigate to the project directory:
   ```bash
   cd pig-game
   ```
3. Open `index.html` in a web browser to start the game.

## Usage
- No additional dependencies are required; the game runs directly in the browser.
- Ensure an internet connection if external resources (e.g., fonts or icons) are used.
- Customize the game by editing the CSS or JavaScript files to modify styles, target score, or add new features.

## Technologies
- **HTML5**: Structure of the web game
- **CSS3**: Styling and animations
- **JavaScript**: Game logic, dice mechanics, and interactivity

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
