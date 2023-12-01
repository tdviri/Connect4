# Connect Four Game

Connect Four is a classic two-player connection game in which the players take turns dropping colored discs from the top into a vertically suspended grid. The objective of the game is to connect four of one's own discs of the same color consecutively vertically, horizontally, or diagonally before your opponent. This implementation is a console-based version in Java.

## How to Play:

- The game is played on a 7x8 grid.
- Players take turns dropping their colored discs into a column of their choice.
- The first player to connect four discs in a row (vertically, horizontally, or diagonally) wins.
- The game ends in a tie if the grid is filled with no winner.

## Running the Game:

1. Compile the Java program: `javac ConnectFour.java`
2. Run the compiled program: `java ConnectFour`
3. Follow the on-screen prompts to input column numbers and make moves.

## Rules:

- The input column number should be in the range of 0 to 6.
- Players cannot drop discs into a column that is already full.

## Implementation Details:

- The game utilizes a simple text-based representation for the game board.
- The `Game` class handles the game logic, including checking for a winning condition.
- The `handleInvalidInput` method ensures valid user inputs for column selection.

Enjoy playing Connect Four!
