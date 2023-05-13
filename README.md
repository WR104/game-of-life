# Game of Life

[Live Demo](https://mikej.site/game-of-life/)

The Game of Life is a fascinating example of a cellular automaton, which was created by mathematician John Conway in 1970. Despite its name, it is not a board game, but a simulation of the behavior of cells in a grid, where the cells can be either "alive" or "dead" based on certain rules.

The game is played on a two-dimensional grid of cells, each of which can be in one of two states: alive or dead. The grid can be any size, but for simplicity, let's say it's a 10x10 grid. Each cell has eight neighbors, which are the cells adjacent to it (diagonally, horizontally or vertically).

At the beginning of the game, some cells are randomly assigned to be alive, and the others are dead. The rules for the game are as follows:

1. Any live cell with fewer than two live neighbors dies, as if by underpopulation.

2. Any live cell with two or three live neighbors lives on to the next generation.

3. Any live cell with more than three live neighbors dies, as if by overpopulation.

4. Any dead cell with exactly three live neighbors becomes a live cell, as if by reproduction.

The game then proceeds in generations, with each generation being determined by the state of the previous generation according to these rules. So if a cell is alive in the current generation, it will stay alive if it has two or three live neighbors, and die otherwise. If a cell is dead in the current generation, it will become alive if it has exactly three live neighbors, and stay dead otherwise.

One interesting thing about the Game of Life is that it is Turing-complete, which means that it can simulate any computer program. This means that it is theoretically possible to create a Game of Life "computer" that can run any program, although in practice it would be extremely slow and impractical.

The Game of Life has been studied extensively by mathematicians and computer scientists, and has led to many interesting discoveries and applications. It has been used to model everything from biological systems to traffic flow, and has even been used to create art and music.

In conclusion, the Game of Life is a fascinating example of a cellular automaton that has captured the imaginations of mathematicians, computer scientists, and enthusiasts alike. Its simplicity and elegance have made it a classic example of emergent complexity, and its ability to simulate a wide variety of phenomena has made it a powerful tool for research and exploration. Whether you are a casual player or a serious researcher, the Game of Life is a game worth exploring.
