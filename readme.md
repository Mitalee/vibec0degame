# JavaScript Games Collection

This repository contains two classic browser games built with pure HTML, CSS, and JavaScript. These games are designed to be simple, fun, and kid-friendly with customizable options.

## 🎮 Games Included

1. **Snake Game** - A classic game where you control a snake to eat food and grow longer without hitting walls or yourself.
2. **Tic Tac Toe** - The timeless X and O game for two players taking turns on a 3×3 grid.

## 🐍 Snake Game

![snake game](image.png)

### Features

- Responsive grid-based play area
- Arrow key controls for snake movement
- Randomly generated food placement
- Gradually increasing difficulty as your score improves
- Game over detection (wall collision and self-collision)
- Score tracking
- Speed customization (Very Slow, Slow, Medium, Fast)
- Background music toggle (when available)
- Spacebar to restart after game over

### How to Play

1. Use the arrow keys to control the snake's direction
2. Eat the red food dots to grow longer and increase your score
3. Avoid hitting the walls or running into your own tail
4. Press spacebar to restart after game over
5. Use the speed controls to adjust difficulty

## ⭕ Tic Tac Toe

![Tic Tac Toe Screenshot](image-1.png)

### Features

- Clean, modern UI design
- Two-player gameplay (X and O)
- Turn indicator showing which player's turn it is
- Automatic win and draw detection
- Visual highlighting of winning combinations
- Confetti celebration effect when a player wins
- Sound effects for player moves and game outcomes
- Sound toggle option
- Spacebar to restart after game is complete

### How to Play

1. Players take turns clicking on empty cells to place their marks (X or O)
2. Player X goes first
3. The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins
4. If all cells are filled without a winner, the game is a draw
5. Press spacebar to restart after a win or draw

## 📋 Requirements

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- For audio: browser with Web Audio API support

## 🚀 Getting Started

1. Clone this repository:
   ```
   git clone https://github.com/mitalee/vibec0degame.git
   ```
2. Navigate to the project directory
3. Open any of the game HTML files in your browser:
   - `index.html` for Snake Game
   - `ttt.html` for Tic Tac Toe

Alternatively, you can simply download the individual HTML files - each game is completely self-contained in a single file.

## 🛠️ Customization

### Snake Game

You can easily customize the Snake Game by editing the `config` object in the JavaScript section:

```javascript
const config = {
    gridSize: 20,        // Number of cells in the grid
    cellSize: 20,        // Size of each cell in pixels
    initialSpeed: 350,   // Starting speed (higher = slower)
    speedIncrease: 1     // How much speed increases with each food
};
```

### Tic Tac Toe

The Tic Tac Toe game can be customized by modifying the CSS styles to match your preferred color scheme or by replacing the sound files with your own audio clips.

## 📱 Mobile Support

Both games support touch devices, but keyboard controls (arrow keys and spacebar) require a physical or on-screen keyboard.

## 🎵 Audio Attribution

The sample sounds used in these games are from various free sound libraries. If you plan to use these games commercially, consider replacing the sounds with your own audio files.

## 📜 License

These games are released under the MIT License. See the LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue if you have ideas for improvements or have found a bug.

## 🙏 Acknowledgements

- Inspiration from classic arcade games
- Built as educational examples for learning JavaScript game development
