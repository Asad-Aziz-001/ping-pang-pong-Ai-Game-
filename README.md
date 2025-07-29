# **ping-pang-pong-Ai-Game**

# How the Game Works:

**Controls:**

Player 1 (left paddle): W (up), S (down)

Player 2 (right paddle): Up Arrow (up), Down Arrow (down)

Press P to start the game.

Press R to reset the game while playing.

**Gameplay:**

The ball moves and bounces off paddles and walls.

If the ball goes past a player's paddle, the other player scores a point.

The game pauses after a goal is scored, and you need to press P to start again.

**Features:**

Score tracking for both players.

Paddle movement with boundary clamping.

Ball collision detection with walls and paddles.

**How to Run the Game:**

Ensure you have Python installed on your system.

Install the pygame library if you haven't already:

pip install pygame

**Run the file:**

streamlit run pong.py

**Notes:**
The game window will open with a black background and a white dividing line.

The paddles and ball are white.

The game runs at 40 FPS (as set by clock.tick(40)).
