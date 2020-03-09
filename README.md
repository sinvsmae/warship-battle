# warship-battle
## Feature
### View
1. map: 7*7(row: 0-6; column: A-G)
2. input: right bottom
3. msg: left top
4. warning: prompt window

### Input
#### Wrong Input
1. If wrong format, warning: Oops, please enter a letter and a number on the board.
2. If off the board, warning: Oops, that's off the board!
3. If else, warning: Oops, that isn't on the board.

#### Result
1.If hit, show: HIT! and ship icon in cell.
2.If miss, show: You missed. and MISS icon in cell.
3.If hit 3 times, show:You sank my battleship!
4.If hit same place, show: Oops, you already hit that location!
5.If 3 ships sink, show: You sank all my battleships, in <num> guesses

### Gameover
When 3 ships sink, game over.

## Design
### View
