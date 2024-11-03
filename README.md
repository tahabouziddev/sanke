# sanke
# Advanced C Game Project

## Overview
This project is a **multiplayer game** developed in C, incorporating challenging features such as **dynamic obstacles**, a **two-player mode**, and an **advanced scoring system**. These elements were designed to create an engaging, competitive experience, while also pushing the limits of C programming with regards to memory management, input handling, and efficient code optimization.

---

## Features

### 1. Dynamic Obstacles
   - **Adaptive Gameplay**: Obstacles move or change over time, providing a continuous challenge for players and adding an element of unpredictability.
   - **Randomized Patterns**: Obstacles appear in varied patterns and intervals, ensuring each game session feels unique and engaging.

### 2. Two-Player Mode
   - **Simultaneous Play**: Supports two players competing in real-time, with separate controls for each player.
   - **Competitive Dynamics**: Players can interact within the game environment, adding a layer of strategy as they navigate around each other and the obstacles.
   - **Individual Scoring**: Scores are tracked separately for each player, adding a competitive edge.

### 3. Advanced Scoring System
   - **Dynamic Scoring**: Points are awarded based on actions taken, including avoiding obstacles, reaching specific milestones, and time survived.
   - **Combo Bonuses**: Special achievements, like consecutive successful dodges, trigger bonus points, rewarding players for skillful gameplay.
   - **Leaderboard**: Displays high scores at the end of each session, motivating players to improve.

---

## Technical Implementation

### Algorithmic Design
   - **Obstacle Generation**: An algorithm generates random obstacle patterns and movements, keeping track of each obstacle's position and adjusting their behaviors dynamically.
   - **Collision Detection**: Developed efficient collision-detection routines to ensure smooth gameplay without lag, even with multiple dynamic elements on screen.
   - **Score Calculation**: The scoring system evaluates actions in real-time, factoring in combos, distance covered, and successful avoidance of obstacles.

### Efficient Memory Management
   - **Dynamic Allocation**: Used dynamic memory allocation to manage game objects such as obstacles and players in real-time, allowing for scalable gameplay.
   - **Memory Optimization**: Carefully managed pointers and memory allocation to prevent leaks and reduce overhead, ensuring smooth performance across extended play sessions.
   - **Cleanup Functions**: Implemented cleanup routines that free all allocated memory after each game session, maintaining optimal memory usage.

### Responsive Input Handling
   - **Real-Time Controls**: Designed input-handling functions that allow each player to respond immediately to obstacles, collisions, and other in-game events.
   - **Keyboard Mapping**: Each player has their own key bindings for actions, enabling seamless two-player control and avoiding input conflicts.
   - **Debounce Mechanisms**: Implemented input debouncing to prevent accidental multiple keypresses and ensure precise control.

### Debugging and Optimization
   - **Iterative Debugging**: Conducted extensive debugging sessions, using both manual testing and debugging tools to identify and resolve bugs.
   - **Optimization Techniques**: Applied various optimizations, such as minimizing function calls and reducing the complexity of key algorithms, to enhance performance.
   - **Code Profiling**: Used profiling tools to identify bottlenecks in the code, particularly in the obstacle generation and collision detection routines, and optimized them for better performance.

---

## Skills Developed

### C Programming
This project significantly enriched my skills in C, requiring advanced knowledge and hands-on application in the following areas:

- **Algorithmic Thinking**: Designed and implemented efficient algorithms for dynamic obstacle generation, collision detection, and scoring.
- **Memory Management**: Improved memory handling techniques, including dynamic allocation, pointer manipulation, and memory cleanup.
- **Responsive Input Handling**: Developed robust input-handling routines that provide an immediate response, essential for real-time multiplayer gameplay.
- **Debugging and Optimization**: Gained experience with debugging tools and techniques for identifying issues and optimizing C code for performance.

### Conclusion
This project was a challenging and rewarding experience that deepened my understanding of **C programming** and **game development principles**. Implementing dynamic obstacles, two-player mode, and an advanced scoring system allowed me to enhance my programming abilities and apply best practices in memory management, input handling, and code optimization. The project was both a test of my technical skills and an opportunity to create an enjoyable gaming experience.

---

## How to Run
1. **Compile the Code**: Use a C compiler (e.g., `gcc`) to compile the code. Example:
   ```bash
   gcc -o game main.c -Wall
