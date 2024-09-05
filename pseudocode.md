## Pseudocode for Space Explorer: Asteroid Avoidance

---

- 1. Initialize Game:
  - Set initial variables: spaceshipPosition, asteroids[], score = 0, gameOver = false.
- 2. Game Start:
  - Begin asteroid spawning with setInterval.
  - Listen for keydown events to control the spaceship (left/right movement).
- 3. Spaceship Movement:
  - On leftArrow/A or rightArrow/D, move the spaceship left or right, ensuring it stays in bounds.
- 4. Asteroid Spawning:
  - Periodically generate new asteroids at random positions.
  - Move asteroids downward, removing them if they exit the screen.
- 5. Collision Detection:
  - Check for collision between the spaceship and any asteroid.
  - If a collision happens, set gameOver = true.
- 6. Score Calculation:
  - Increment the score based on how long the player survives.
- 7. Game Over:
  - If gameOver = true, stop the game and display the final score.
