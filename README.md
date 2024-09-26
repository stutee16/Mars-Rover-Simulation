# Mars Rover Simulation

This project simulates the movement of a Mars Rover on a grid, following user commands. The rover navigates the grid based on user input and avoids predefined obstacles. It provides real-time feedback on its position, direction, and interactions with obstacles.

## Features

- **User-Interactive Input**: Allows users to set the rover's initial position, direction, and issue movement commands.
- **Obstacle Avoidance**: The rover can detect and navigate around predefined obstacles on the grid.
- **Real-Time Updates**: Provides immediate feedback on the rover's current position and direction after executing commands.
- **Predefined Obstacles**: Simulates real-life conditions by including obstacles in the grid.
- **Flexible Grid Size**: Users can define the size of the grid for rover movement.

## Project Structure

```bash
mars_rover/
├── commands/
│   ├── Command.java            # Interface for defining commands
│   ├── MoveForwardCommand.java  # Command for moving the rover forward
│   ├── TurnLeftCommand.java     # Command for turning the rover left
│   ├── TurnRightCommand.java    # Command for turning the rover right
├── grid/
│   ├── Grid.java                # Class representing the grid environment
│   ├── Obstacle.java            # Class representing obstacles on the grid
├── rover/
│   ├── Rover.java               # Class defining the rover's properties and behaviors
├── mars_rover/
│   ├── Main.java                # Entry point for running the simulation
