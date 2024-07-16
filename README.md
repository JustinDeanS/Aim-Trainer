# Aim Trainer

Aim Trainer is a Python game developed using the Pygame library. This game helps users improve their mouse accuracy and speed by clicking on targets that appear on the screen.

## Features

- Targets appear at random positions on the screen.
- The size of the targets increases and decreases over time.
- The game tracks the number of targets hit, the number of clicks, and the elapsed time.
- The game ends after a certain number of missed targets.
- Displays performance metrics such as accuracy and speed at the end of the game.

## Installation

To run this project, you need to have Python and Pygame installed on your machine.

1. **Clone the repository:**

    ```sh
    git clone https://github.com/your-username/aim-trainer.git
    cd aim-trainer
    ```

2. **Install Pygame:**

    ```sh
    pip install pygame
    ```

## How to Play

1. **Run the game:**

    ```sh
    python aim_trainer.py
    ```

2. **Gameplay Instructions:**
    - Targets will appear on the screen at random intervals.
    - Use your mouse to click on the targets as quickly as possible.
    - Avoid missing targets, as you only have a limited number of lives.
    - The game will display your performance metrics at the end.

## Code Overview

### Main Components

- `Target`: Class representing the targets that appear on the screen. It handles the target's position, size, and drawing logic.
- `draw(win, targets)`: Function to draw all targets on the screen.
- `format_time(secs)`: Function to format the elapsed time.
- `draw_top_bar(win, elapsed_time, targets_pressed, misses)`: Function to draw the top bar displaying time, speed, hits, and lives.
- `end_screen(win, elapsed_time, targets_pressed, clicks)`: Function to display the end screen with performance metrics.
- `main()`: Main game loop handling game logic, events, and updates.


