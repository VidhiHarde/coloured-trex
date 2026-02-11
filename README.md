# T-Rex Endless Runner - JavaScript Game

### Project Overview
A 2D endless runner game inspired by the classic Chrome Dino game. This project demonstrates the implementation of game physics, collision detection, and state management using the **p5.js** library.

### Key Features
* **Game State Management:** Utilizes logic to switch between `PLAY` and `END` states, handling game resets and "Game Over" sequences.
* **Physics & Collisions:** Implemented gravity simulations, jumping mechanics (velocity/acceleration), and pixel-perfect collision detection between the player and obstacles.
* **Dynamic Difficulty:** Includes an algorithm that increases the game speed (`velocityX`) as the player’s score increases, providing a progressive challenge.
* **Procedural Spawning:** Randomly generates obstacles and decorative clouds using frame-count intervals to ensure every playthrough is unique.
* **Local Storage Integration:** Saves and displays the user's "Highest Score" using browser `localStorage`.

### Technologies Used
* **JavaScript (p5.js & p5.play):** Core game logic and sprite manipulation.
* **HTML5/CSS3:** Used for the game canvas container and basic page styling.

### What I Learned
* **Asynchronous Preloading:** Understood the importance of loading assets (images/animations) before the game setup begins.
* **Logic Design:** Developed a deeper understanding of the "draw loop" and how to manage object lifetimes to optimize performance.
* **Coordinate Geometry:** Applied mathematical concepts to handle sprite positioning and movement across the 600x200 canvas.

### How to Play
1. Open `index.html` in a web browser.
2. Press the **Spacebar** to jump over obstacles.
3. If you hit an obstacle, click the **Restart** button to try again!
