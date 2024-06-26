# Minesweeper ![GitHub Tag](https://img.shields.io/github/v/tag/karinasantosfelippe/Minesweeper?label=version&color=rgb(0%2C%20150%2C%200))


![GitHub Created At](https://img.shields.io/github/created-at/karinasantosfelippe/minesweeper?label=Created%20at%20&color=rgb(221%2C%200%2C%20255))

![Static Badge](https://img.shields.io/badge/Author-Karina_Santos_Felippe-purple?color=rgb(221%2C%200%2C%20255))



## About
The Minesweeper game is played on a grid of button cells, where each cell can either be empty or contain a hidden mine. The player's objective is to uncover all the empty cells on the grid without detonating any mines. The player selects a cell to reveal its content. If the revealed cell contains a mine, the game ends immediately, and the player loses. However, if the revealed cell is empty, it will display a number indicating the number of mines in adjacent cells. Using this information, the player must strategically reveal cells to deduce the locations of the mines. The game is won when all non-mine cells are revealed.

## Usage
To play the game, simply run the Python script. A graphical interface will open displaying a grid of buttons. Click on the buttons to reveal their content. The game will automatically detect if you win or lose and display a message accordingly.

## Instructions
1. Left-click on a cell to reveal its content.
2. If a cell contains a mine, the game ends, and you lose.
3. If a cell is empty, a number will indicate the number of mines in adjacent cells.
4. Use the numbers strategically to deduce the locations of the mines.
5. Reveal all non-mine cells to win the game.

## How to Run
Ensure you have Python installed on your system. Then run the script using the following command:

```bash
python minesweeper.py
```

or

```bash
py minesweeper.py
```

## Dependencies
- Python 3.x
- tkinter module (should be included in standard Python distributions)

Enjoy playing Minesweeper! 🚩