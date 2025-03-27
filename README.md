# Flappy Bird Inspired Game - Java Implementation

## Overview
This is a 2D inspired Flappy Bird game implemented in Java using Swing for rendering and AWT for event handling. The game features a bird that moves through pipes, avoiding collisions while scoring points.

## Game Mechanics

### Bird Class:
- The bird is represented as an object with properties like position `(x, y)`, size `(width, height)`, and an image.
- It is controlled using the `spacebar` to "flap" and move upward (modifying `velocityY`).

### Pipe Class:
- Pipes are created as objects with properties such as position, size, and an image.
- They spawn at regular intervals using a `Timer` and have an opening for the bird to pass through.

### Game Logic:
- `placePipesTimer` adds new pipes at intervals by calling the `placePipes` method.
- `gameLoop` controls bird and pipe movement and checks for collisions.
- The bird's velocity is affected by gravity, and if it hits a pipe or the ground, the game ends.

### Graphics Rendering:
- The `paintComponent` method renders the background, bird, pipes, and score.
- The score updates as the bird successfully passes through pipes.
- If the bird collides with a pipe or falls out of the screen, "Game Over" is displayed.

## Learning Outcomes
Through this project, I improved my understanding of:
- **Java Swing Framework**: Implementing graphics rendering and user input handling.
- **Game Logic and Physics**: Managing movement, collision detection, and dynamic object behavior.
- **Event-Driven Programming**: Using timers and animations for real-time updates.

## How to Run
1. Compile the Java file using `javac FlappyBird.java`.
2. Run the program with `java FlappyBird`.
3. Press `SPACEBAR` to make the bird flap and navigate through the pipes.

Enjoy playing! 🚀
