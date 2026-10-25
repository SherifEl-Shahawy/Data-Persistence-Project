# Data Persistence Project

A small brick-breaker game made in Unity with C#.
It is the starting point for an exercise on keeping data between scenes and between sessions.

## Gameplay

- Press **Space** to launch the ball.
- Move the paddle with the **left/right arrow keys** (or **A/D**).
- Bricks are worth 1, 2 or 5 points by row.
- If the ball falls past the paddle, the game is over. Press **Space** to restart.

## Status

The game itself works. The data persistence part (a start menu, player name and a saved high score) is not added yet.

## Project

- Unity **2020.3.7f1**, Universal Render Pipeline.
- Scene: `Assets/Scenes/main.unity`.
- Scripts in `Assets/Scripts/`:
  - `MainManager.cs` – builds the brick rows, starts the ball, keeps the score and handles game over.
  - `Ball.cs`, `Paddle.cs`, `Brick.cs`, `DeathZone.cs` – ball physics, paddle movement, brick points and the game-over trigger.

## How to open

Open the folder in Unity Hub with Unity 2020.3.7f1 (or a later 2020.3 LTS), then open `Assets/Scenes/main.unity` and press Play.
