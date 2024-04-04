# Shakashaka

This program is designed to solve Shakashaka puzzles. Shakashaka is a logic puzzle where the objective is to shade some cells in a grid according to the rules:

1. No two shaded cells may share an edge.
2. All unshaded cells must be connected.
3. Shaded cells cannot form a 2x2 square.
4. The unshaded cells must form a single continuous area (like a maze).

## Getting Started

### Prerequisites

- Python 3.x
- Tkinter
- NumPy
- Gurobi Optimization (if you want to modify or run the linear programming solver)

### Installing

1. Clone the repository to your local machine.
2. Make sure you have all the dependencies installed.
3. Run the `Shakashaka.py` file.

## How to Use

1. Run the program.
2. Enter the dimensions of the puzzle grid and the initial configuration of shaded and unshaded cells.
3. Click the "Solve" button to find a solution.
4. The program will display the solved puzzle.

## Features

- Graphical user interface for easy puzzle input and visualization.
- Utilizes linear programming (with Gurobi) to find solutions.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
