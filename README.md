# Tetris Game

This project is a simple Tetris game implemented in Python using the Pygame library. The game includes basic functionality such as block rotation, line clearing, scoring, and a game-over state.

---

## Features
- **Classic Tetris gameplay**
  - Rotate and move blocks left, right, or down.
  - Drop blocks instantly to fill rows.
- **Scoring system**
  - Earn points by clearing rows.
  - Accumulate more points by clearing multiple rows simultaneously.
- **Game state management**
  - "Game Over" screen with a restart option.
- **Adjustable difficulty**
  - The game level determines the speed of the falling blocks.

---

## How to Run
### Prerequisites
- Python 3.6+
- Pygame library

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project-directory>
   ```
3. Install dependencies:
   ```bash
   pip install pygame
   ```
4. Run the game:
   ```bash
   python tetris.py
   ```

---

## Controls
- **Arrow keys**
  - `UP`: Rotate the block
  - `DOWN`: Move the block faster
  - `LEFT`: Move the block left
  - `RIGHT`: Move the block right
- **Spacebar**: Instantly drop the block
- **ESC**: Restart the game

---

## Gameplay
- The goal is to arrange the falling blocks to form complete horizontal rows.
- When a row is completed, it clears, and you earn points.
- The game ends when the blocks stack up to the top of the screen.

---

## Files
- **tetris.py**: The main game file containing the entire implementation.

---

## Customization
- **Colors**: You can modify the block colors by editing the `colors` list in the `tetris.py` file.
- **Grid size**: Adjust the height and width of the grid by modifying the `Tetris` class initialization in `tetris.py`.
- **Zoom level**: Change the size of blocks by altering the `zoom` variable in the `Tetris` class.

---

## Future Improvements
- Add a pause/resume functionality.
- Include a high score leaderboard.
- Implement sound effects and background music.

---

## License
This project is open-source and available under the MIT License.

---

## Acknowledgments
- Thanks to the Pygame community for their helpful documentation and resources.

---

Enjoy the game!

