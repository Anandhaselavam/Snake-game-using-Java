## Overview
This is a classic Snake Game implemented in Java using Object-Oriented Programming (OOP) principles. The game involves controlling a snake to eat food and grow in size while avoiding collisions with the walls and itself. The game becomes progressively harder as the snake grows longer.

## Features
- **Object-Oriented Design**: The game is designed using OOP principles for modularity and easy maintenance.
- **Graphical User Interface (GUI)**: The game uses Java Swing for the GUI.
- **Game Mechanics**: The snake grows in length as it eats food, and the game ends if the snake collides with itself or the game boundaries.
- **Keyboard Controls**: Use the arrow keys to control the direction of the snake.

## Requirements
- Java Development Kit (JDK) 8 or higher
- An IDE or text editor for Java development

## Installation
1. **Clone the Repository**:
   git clone https://github.com/your-username/snake-game-java.git
   cd snake-game-java

2. **Compile the Source Code**:
   javac -d bin src/com/snakegame/*.java

3. **Run the Game**:
   java -cp bin com.snakegame.Main

## Classes and Design
### 1. Main
The entry point of the game. It initializes the game window and starts the game.

### 2. GameFrame
The main frame for the game window. It sets up the window properties such as size, title, and closing behavior.

### 3. GamePanel
The panel where the game is rendered. It handles the game loop, user inputs, and game updates.

### 4. Snake
Represents the snake in the game. It handles the movement, growth, and collision detection.

### 5. Food
Represents the food the snake eats. It randomly positions the food within the game boundaries.

### 6. GameEngine
The core engine that drives the game logic, including updating the game state and handling collisions.

## Controls
- **Arrow Keys**: Use the arrow keys to change the direction of the snake.
  - **Up Arrow**: Move up
  - **Down Arrow**: Move down
  - **Left Arrow**: Move left
  - **Right Arrow**: Move right

## How to Play
1. Run the game using the provided commands.
2. Use the arrow keys to control the snake.
3. Eat the food to grow longer.
4. Avoid colliding with the walls and the snake's own body.
5. The game ends if the snake collides with itself or the boundaries.

## Future Enhancements
- Add different levels with increasing difficulty.
- Implement a scoring system.
- Add sound effects and music.
- Create a high score leaderboard.
- Improve the GUI with better graphics.

## Contribution
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## Acknowledgements
- Inspired by the classic Snake game.
- Thanks to open-source projects and the Java community for resources and support.
