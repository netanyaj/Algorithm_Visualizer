# A* Path Finding Visualizer

This is a Python program that visualizes the A* pathfinding algorithm using the Pygame library. The program allows you to create obstacles, define a start and end point, and find the shortest path between them using the A* algorithm.

## Requirements

- Python 3.x
- Pygame library

## Installation

1. Make sure you have Python 3.x installed on your system. If not, you can download it from the official Python website: https://www.python.org/downloads/

2. Install the Pygame library by running the following command:

   ```
   pip install pygame
   ```

## Usage

To run the A* pathfinding visualizer, follow these steps:

1. Open a Python IDE or a command prompt.

2. Copy and paste the code into a Python file (e.g., `astar.py`).

3. Save the file and run it using the Python interpreter:

   ```
   python astar.py
   ```

4. The Pygame window will open, displaying a grid.

5. **Left-click** on the grid to set the start point (green cell). You can only set one start point.

6. **Left-click** on the grid to set the end point (red cell). You can only set one end point.

7. **Left-click** on the grid to create obstacles. Obstacles are represented by black cells.

8. **Right-click** on the grid to remove obstacles.

9. Press the **Space** key to start the A* algorithm and visualize the shortest path between the start and end points. The algorithm will be visualized on the grid.

10. Press the **C** key to clear the grid and start over.

11. Close the Pygame window or press **Ctrl + C** in the command prompt to exit the program.

Note: The program uses a grid size of 80x80 cells by default. You can modify the `ROWS` constant in the code to change the grid size.

## Customization

You can customize the program by modifying the following variables:

- `WIDTH`: The width of the Pygame window in pixels.
- `WHITE`, `BLACK`, `GREY`, `PEAR`, `BLUE`, `CYAN`, `GREEN`, `RED`: RGB color values used for different cells in the grid.
- `ROWS`: The number of rows and columns in the grid. Changing this value will affect the grid size.

