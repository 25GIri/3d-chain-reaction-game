# Chain Reaction (2D Grid)

A classic Chain Reaction game implemented as a web application.

## Game Rules
- **Grid Setup**: Played on a 2D grid of cells.
- **Turns**: Players take turns placing an atom of their color on an empty cell or a cell they already own.
- **Capacity**: 
  - **Corner cells**: Maximum capacity of 1 atom.
  - **Side/Edge cells**: Maximum capacity of 2 atoms.
  - **Internal cells**: Maximum capacity of 3 atoms.
- **Explosion (Chain Reaction)**: When a cell exceeds its maximum capacity, it explodes! The excess atoms distribute to neighboring cells (up, down, left, right), converting those cells to the current player's color. This can trigger secondary explosions.
- **Winning**: The last player remaining with atoms on the board wins.
