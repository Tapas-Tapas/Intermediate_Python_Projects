# Snake Game README

A classic Snake game implemented in Python using the Turtle graphics library. Control the snake to eat food and grow while avoiding walls and your own tail!

## Features

- **Snake Movement**: Navigate using arrow keys (Up, Down, Left, Right).
- **Food Collision**: Snake grows longer when eating food.
- **Score Tracking**: Real-time score updates with a scoreboard.
- **Collision Detection**:
  - Game ends if snake hits the wall.
  - Game ends if snake collides with its own tail.
- **Visual Feedback**: Colorful snake segments, food, and clear game-over message.

## Requirements

- Python 3.x
- Turtle module (included in Python's standard library)

## Installation

1. **Clone the repository** or download the following files to a folder:
   - `main.py`
   - `snake.py`
   - `food.py`
   - `scoreboard.py`

2. Ensure all files are in the same directory.

## How to Play

1. **Run the game**:
   ```bash
   python main.py
   ```

2. **Controls**:
   - `↑` Arrow Up: Move snake upward
   - `↓` Arrow Down: Move snake downward
   - `←` Arrow Left: Move snake left
   - `→` Arrow Right: Move snake right

3. **Objective**:
   - Eat the red food dots to grow the snake and increase your score.
   - Avoid hitting the walls or the snake's own tail.

## Game Over Conditions

- The game ends if:
  - The snake head touches the screen boundaries (walls).
  - The snake head collides with any part of its tail.

A "GAME OVER" message will appear when the game ends. Click the screen to exit.

## Project Structure

- `main.py`: Main game loop and setup.
- `snake.py`: Handles snake creation, movement, and growth.
- `food.py`: Manages food spawning and collision detection.
- `scoreboard.py`: Tracks and displays the score and game-over message.

---

Enjoy the game! 🐍
