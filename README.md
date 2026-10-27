# Asteroids

A small Asteroids-style game built with Python and Pygame as part of [Boot.dev](https://www.boot.dev/). A learning project focused on object-oriented programming, game loops, sprite groups, and collision detection.

Pilot your ship, shoot incoming asteroids, and avoid collisions. Larger asteroids split into smaller, faster pieces when hit. Hitting an asteroid ends the game.

## Run

Requires Python 3.13+ and [uv](https://docs.astral.sh/uv/).

```sh
uv sync
uv run main.py
```

## Controls

| Key | Action |
| --- | --- |
| W / S | Move forward / backward |
| A / D | Rotate left / right |
| Space | Shoot |

Close the window to quit. To play again after a collision, rerun the command.
