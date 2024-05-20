# Chess Scheduler

## Introduction
This project is a simple implementation of a chess scheduler in Haskell. It provides functionalities for visualizing the chessboard and suggesting legal moves for different pieces.

## Usage
To visualize the chessboard, you can use the `visualizeBoard` function. For example:
```haskell
putStrLn(visualizeBoard setBoard)
```
To suggest legal moves for a piece, you can use the suggestMove function, providing the piece and the current board as arguments. For example:
```haskell
suggestMove (P ('e', 2)), setBoard)
```

## Data Structures
The following data structures are used in the project:

- **Location:** Represents the location of a piece on the chessboard.
- **Player:** Represents a player (either White or Black).
- **Piece:** Represents a chess piece with its location.
- **Board:** Represents the current state of the chessboard, including the player, white pieces, and black pieces.

## Functions
The project includes various functions for manipulating the chessboard and pieces:

- **insertAt:** Inserts an element at a specified location in a 2D array.
- **setBoard:** Initializes the chessboard with pieces placed in their starting positions.
- **suggestMove:** Suggests legal moves for a given piece on the board.
 - Other helper functions for move validation, piece manipulation, and board visualization.

## How to Run
To run the project, you need to have Haskell installed on your system. You can compile and execute the code using GHCi or any Haskell compiler.

## License
This project is licensed under the MIT License.
