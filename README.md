# Knights Travails

This project will show the shortest possible way to get from one square to another by outputting all squares the knight will stop on along the way using BFS.

The function `knightMoves` will take the start and end squares and return the number of moves and the path. For example:
\
`knightMoves([3,3],[4,3])` will return `You made it in 3 moves! Here's your path: 3,3 -> 1,2 -> 2,4 -> 4,3`