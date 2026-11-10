# Maze AI

A Python desktop demo that lets you explore weighted maze search and depth-limited search.

## Run locally

You need Python 3 with Tkinter and NumPy. To check whether Tkinter is available, run `python -m tkinter`.

```bash
python -m pip install numpy
python Maze_Graphic.py
```

In the desktop window, choose a start and goal, select a search method, and click **Find Path**.

## Code map

- [`Maze_Graphic.py`](Maze_Graphic.py) opens the desktop interface.
- [`Maze_Search.py`](Maze_Search.py) implements the search routines.
- [`create_problem.py`](create_problem.py) defines the maze problem.

See also [Maze Search Experiments](https://github.com/Shahin-Ghanbari/AI) for breadth-first search and forward chaining.
