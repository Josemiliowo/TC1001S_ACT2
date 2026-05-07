# List of changes for this file:
- The food can move randomly one step at a time and must not leave the window
- Each time the game is run, the snake and the food must have different colors from each other, but randomly, from a series of 5 different colors, except red.

## Change 1
For each tick, a random number is selected, this defines the direction the food will move in that specific tick as long as the boundaries of the screen allows it.

## Change 2
For the second change, a list of 5 possible colors is defined at the top of the code, afterwards, we use the random library to select a color for the snake, then, we cyce in a while until the food has a random color different from the snake.

## Commit tree
```
* 4b68e42 (HEAD -> main, origin/main, origin/HEAD) Added random colors for snake and food
*   63d11ef Merge pull request #1 from GabrielPrzz/main
|\  
| * 929b9de Feature nueva-Comida con movimiento, cada 500ms se mueve en una de las 4 direcciones random
|/  
* 00e78c9 added readme
* cddc19b unploaded game
* 5d4992b Initial commit
```
