# Flappy Bird Clone in Pygame

This is a simple clone of the popular Flappy Bird game developed using Python and the Pygame library. The game features a bird that the player controls by pressing the UP and DOWN arrow keys, navigating through an endless series of pipes. The goal is to keep the bird alive by avoiding collisions with the pipes while collecting points.

## Features:
- **Bird Movement**: Controlled by pressing the UP and DOWN arrow keys, simulating the classic "flap" and gravity mechanics.
- **Dynamic Pipe Generation**: The pipes move from right to left and are randomly generated with varying gaps.
- **Score System**: The player earns points by successfully passing through pairs of pipes.
- **Difficulty Scaling**: As the player’s score increases, the game becomes progressively harder with faster-moving pipes.
- **Game Over Condition**: The game ends when the bird collides with a pipe or falls off the screen.

## How to Play:
- Press the **UP arrow key** to make the bird fly upwards.
- Press the **DOWN arrow key** to make the bird fall faster.
- Avoid hitting the pipes and try to achieve the highest score possible!

## Requirements:
- Python 3.x
- Pygame library (can be installed via `pip install pygame`)

## Installation:
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/flappy-bird-clone.git
   ```
2. Navigate into the project directory:
   ```
   cd flappy-bird-clone
   ```
3. Install the required dependencies:
   ```
   pip install pygame
   ```
4. Run the game:
   ```
   python flappy_bird.py
   ```
