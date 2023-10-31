# A* Path Finding Algorithm
Date: 10-31-23 

This Python script implements the A* pathfinding algorithm using the Pygame library to visualize the algorithm's operation. A* is a widely used pathfinding algorithm for finding the shortest path between two points on a grid while avoiding obstacles. The script allows users to define start and end points, draw barriers, and then find the shortest path between the start and end points.

## Usage

1. Ensure you have Python and Pygame installed.
   
2. Clone the repository or copy the code into your project directory.

3. Run the script:

   ```bash
   python your_script_name.py
   ```

4. Follow the on-screen instructions to interact with the program:

   - Left-click to place the start and end points and create barriers.
   - Right-click to remove start, end points, and barriers.
   - Press the spacebar to start the pathfinding algorithm.
   - Press the 'c' key to clear the grid and start over.

## Code Structure

The code is structured as follows:

- **`Spot` Class**: Represents a cell on the grid and its properties.
  
- **`h` Function**: Calculates the heuristic distance between two points (used to estimate the cost of reaching the goal).

- **`make_grid` Function**: Creates the grid of spots.

- **`draw` Function**: Draws the grid, spots, and lines on the screen.

- **`get_clicked_pos` Function**: Converts mouse click coordinates into row and column indices.

- **`algorithm` Function**: Implements the A* pathfinding algorithm to find the shortest path.

- **`reconstruct_path` Function**: Reconstructs and draws the shortest path on the grid.

- **`main` Function**: The main game loop for user interaction and starting the algorithm.

## Visualization

The Pygame library is used for visualization, providing a window where you can draw obstacles, start and end points, and observe the A* algorithm's progress.

## Controls

- **Left Mouse Button**: Place the start and end points, and create barriers.
- **Right Mouse Button**: Remove start and end points, and barriers.
- **Spacebar**: Start the A* algorithm to find the shortest path.
- **'c' Key**: Clear the grid and reset the start and end points.

## Dependencies

- Python (3.x recommended)
- Pygame library

## Note

This code is intended for educational purposes to help understand the A* pathfinding algorithm and is not intended for production use.
