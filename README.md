# CSE215-CarGame
A 2D car racing game built in Java Swing for CSE 215 (Programming Language II - JAVA) course project.

## Project Structure

```
CSE215-CarGame/
├── CarProject/
│   ├── Main.java          # Entry point of the application
│   ├── CarGame.java       # Main game class with game logic
│   └── ...
├── images/                # Game assets folder
│   ├── car.png            # Player car sprite
│   ├── car1.png           # Enemy car 1 sprite
│   ├── car2.png           # Enemy car 2 sprite
│   ├── car3.png           # Enemy car 3 sprite
│   └── tree.png           # Obstacle/decoration sprite
└── README.md              # This file
```

## Game Features

- 2D car racing game built using Java Swing
- - Keyboard controls for player car movement (A/D keys for left/right, Enter to start)
  - - Enemy cars spawning randomly in different lanes
    - - Collision detection with game over condition
      - - Score tracking system
        - - Road animation with moving center line
          - - Multiple obstacle sprites (trees on road sides)
           
            - ## How to Build & Run
           
            - 1. **Compile the Java files:**
              2.    ```bash
                       javac CarProject/*.java
                       ```

                    2. **Run the game:**
                    3.    ```bash
                             java CarProject.Main
                             ```

                          3. **Game Controls:**
                          4.    - `A` - Move left
                                -    - `D` - Move right
                                     -    - `Enter` - Start game / Restart after game over
                                      
                                          - ## Image Assets Required
                                      
                                          - The `images/` folder must contain the following PNG files:
                                          - - `car.png` - Player's car sprite
                                            - - `car1.png`, `car2.png`, `car3.png` - Enemy car sprites
                                              - - `tree.png` - Tree/obstacle sprites for road sides
                                               
                                                - These image files should be placed in the `images/` directory for the game to render properly.
                                               
                                                - ## Requirements
                                               
                                                - - Java JDK 8 or higher
                                                  - - Java Swing library (included with JDK)
                                                   
                                                    - ## Author
                                                   
                                                    - Created for CSE 215: Programming Language II (JAVA) course
