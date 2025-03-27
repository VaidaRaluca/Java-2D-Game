This implementation of this 2D game in Java uses Swing for rendering the game and AWT for event handling. 
Bird Class:
The bird is represented by an object with properties like position (x, y), size (width, height), and an image. The bird is controlled using the spacebar to make it "flap" and move upward (change in velocityY).
Pipe Class:
Pipes are represented by objects with properties like position, size, and an image. Pipes are created at regular intervals using a Timer and have an opening between them to allow the bird to pass through.
The logic of the game is based on placePipesTimer which adds new pipes at intervals by calling the placePipes method, gameLoop controlls the movement of the bird and pipes and check for collisons. The bird's velocity is affected by gravity, and if it hits a pipe or the ground, the game ends. The paintComponent method renders the background, bird, pipes, and score. The score is updated as the bird passes through pipes, and the game displays "Game Over" if the bird collides with any pipe or falls out of the screen.
This structure allows the bird to move freely, pipes to spawn and move across the screen, and collision detection for gameplay functionality.
Through this application, I improved my understanding of Java's Swing framework by implementing graphics rendering and user input handling. I enhanced my problem-solving skills by managing game logic, collision detection, and dynamic object movement. Additionally, I gained experience in real-time event-driven programming using timers and animations.
