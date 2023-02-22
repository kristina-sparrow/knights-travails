# Knights Travails

A solution to the 'Knights Travails' problem that finds the shortest path for a knight on a chessboard to get from a starting square to a target square using the breadth-first search algorithm.

### Code Explanation

The program defines a `ChessSquare` function that represents a square on the chessboard. Each `ChessSquare` object has an x and y position, a predecessor (which is used to reconstruct the path), and a `createKnightMoves` method that returns an array of all possible knight moves from that square.

The `knightMoves` function takes in two arrays representing the starting and target squares, creates `ChessSquare` objects for each of them, and performs a breadth-first search to find the shortest path between the two squares. The `squareRegistry` variable is used to keep track of all the `ChessSquare` objects that have been created so far to avoid duplicating squares.

### Result

```javascript
knightMoves([0,0],[1,1])
=> The shortest path was 4 moves! The moves were:
[ 0, 0 ]
[ 1, 2 ]
[ 2, 4 ]
[ 3, 2 ]
[ 1, 1 ]
```
