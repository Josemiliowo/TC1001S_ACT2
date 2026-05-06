# 🐍 Snake Game

A classic Snake arcade game built with Python's `turtle` graphics library and the `freegames` package.

## Description

Guide the snake to eat the green food squares and grow longer. The game ends when the snake hits a wall or runs into itself — the collision square turns red to mark where things went wrong.

## Requirements

- Python 3.x
- [`freegames`](https://pypi.org/project/freegames/) library

Install the dependency with:

```bash
pip install freegames
```

## How to Run

```bash
python snake.py
```

## Controls

| Key | Action |
|-----|--------|
| `→` Right Arrow | Move right |
| `←` Left Arrow  | Move left  |
| `↑` Up Arrow    | Move up    |
| `↓` Down Arrow  | Move down  |

## Gameplay

- The snake starts at the center of the screen moving downward.
- Each time the snake eats the **green** food square, it grows by one segment and the current length is printed to the console.
- Food is randomly repositioned after being eaten.
- The game ends if the snake:
  - Hits the boundary of the play area.
  - Collides with its own body.
- The collision point flashes **red** to indicate where the game ended.

## Project Structure

```
snake.py      # Main game file
```

## Exercises & Customization Ideas

The following challenges are built into the original source as learning exercises:

1. **Speed** — How do you make the snake faster or slower? *(Hint: look at the `ontimer` delay.)*
2. **Wrap-around edges** — How can you make the snake go around the edges instead of dying?
3. **Moving food** — How would you make the food move over time?
4. **Mouse controls** — Change the snake to respond to mouse clicks instead of arrow keys.

## License

This project is based on the [freegames](https://github.com/grantjenks/free-python-games) library by Grant Jenks, released under the Apache 2.0 License.
