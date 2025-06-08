# Knights and Portals

Knights and Portals is a web-based tool to find the shortest path in a grid-based maze. The grid consists of empty cells, obstacles, and portals. Players can teleport to any empty cell once during the traversal. The tool visualizes this unique maze-solving approach, making it ideal for learning and experimentation.

## Features

- **Grid Input**: Users can input a grid where `0` represents an empty cell, and `1` represents an obstacle.
- **Shortest Path Finder**: Uses Breadth-First Search (BFS) to find the shortest path from the top-left corner to the bottom-right corner.
- **Teleportation**: Includes a unique feature to teleport between empty cells once during traversal.
- **Interactive Interface**: A simple and elegant UI with real-time feedback.

## Technologies Used

- **HTML5**: Markup for structuring the interface.
- **CSS3**: Styling for an immersive visual experience.
- **JavaScript**: Core logic for parsing the grid, implementing BFS, and teleportation mechanics.

## Usage

1. **Input the Grid**:
   - Enter the grid in the `textarea` provided.
   - Use `0` for empty cells and `1` for obstacles.
   - Separate rows with new lines. For example:
     ```
     0 1 0 0
     0 1 0 1
     0 0 0 0
     1 1 1 0
     ```

2. **Run the Algorithm**:
   - Click the **Find Shortest Path** button.
   - The shortest path is displayed below, including the number of steps.

3. **Error Handling**:
   - Proper messages are shown for invalid grids or when no path exists.

## How It Works

1. **Grid Parsing**:
   - The input grid is validated for proper formatting.
   - Converts the input into a 2D array for processing.

2. **Pathfinding**:
   - Uses BFS for shortest-path computation.
   - Teleportation is considered as part of the traversal logic.

3. **Output**:
   - Displays the total number of steps if a path is found.
   - Highlights errors or informs the user if no path exists.
