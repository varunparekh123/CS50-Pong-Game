# Pong Game

A classic two-player Pong game built with **Lua** and **LÖVE2D** as part of Harvard’s **CS50 Game Development** course.

This project recreates the original arcade-style Pong experience with real-time paddle movement, ball physics, collision detection, score tracking, sound effects, and win/restart game states.

## Features

- Two-player local gameplay
- Real-time paddle controls
- Ball movement and collision detection
- Score tracking for both players
- Game states for start, serve, play, and game over
- Sound effects for paddle hits, wall hits, and scoring
- Responsive virtual resolution scaling using `push.lua`
- Object-based structure using separate `Ball` and `Paddle` classes

## Tech Stack

- **Lua**
- **LÖVE2D**
- **push.lua** for virtual resolution scaling
- **class.lua** for class-based structure

## Controls

### Player 1

- `W` - Move paddle up
- `S` - Move paddle down

### Player 2

- `Up Arrow` - Move paddle up
- `Down Arrow` - Move paddle down

### Game Controls

- `Enter` / `Return` - Start game, serve ball, or restart after game over
- `Escape` - Quit game

## How to Run

1. Install LÖVE2D from: https://love2d.org/

2. Clone this repository:

```bash
git clone https://github.com/your-username/pong-game.git
Open the project folder with LÖVE2D.

On macOS, you can run:

love pong-game

Or drag the project folder onto the LÖVE2D application.

Project Structure
pong-game/
├── main.lua
├── Ball.lua
├── Paddle.lua
├── class.lua
├── push.lua
├── font.ttf
└── sounds/
    ├── paddle_hit.wav
    ├── score.wav
    └── wall_hit.wav
What I Learned

Through this project, I learned how to build a complete game loop, manage different game states, handle keyboard input, detect collisions, update objects using delta time, and structure a game using separate classes for different objects. I also gained experience working with LÖVE2D’s rendering, audio, and window management systems.

Acknowledgements

This project was developed through Harvard’s CS50 Game Development course.
