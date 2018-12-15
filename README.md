# magic-recursion
The repository contains mini-projects which uses visualisation tools to show the simplicity, power and beauty of recursion.
They are implemented using **Pyhton** and **Turtle** module is used for visualisation.

## Mini-projects are as follows:
1. **Exploring a Maze - `exploring_maze.py`** 
- Each square of the maze is either open or occupied by a section of wall. The turtle can only pass through the open squares of the maze. If the turtle bumps into a wall it must try a different direction. The turtle will require a systematic procedure to find its way out of the maze. We use file named `maze2.txt` with contains the structure of the maze and the startig point.
- Here is the procedure:
  - From our starting position we will first try going North one square and then recursively try our procedure from there.
  - If we are not successful by trying a Northern path as the first step then we will take a step to the South and recursively repeat our procedure.
  - If South does not work then we will try a step to the West as our first step and recursively apply our procedure.
  - If North, South, and West have not been successful then apply the procedure recursively from a position one step to our East.
  - If none of these directions works then there is no way to get out of the maze and we fail.

2. **Sierpinski Triangle - `turtle_visualisation_triangle.py`**
- Fractals exhibit the property of self-similarity. One such fractal is the Sierpinski triangle. The Sierpinski triangle illustrates a three-way recursive algorithm. The procedure for drawing a Sierpinski triangle by hand is simple.
- Here is the procedure:
  - Start with a single large triangle. 
  - Divide this large triangle into four new triangles by connecting the midpoint of each side. 
  - Ignoring the middle triangle that you just created, apply the same procedure to each of the three corner triangles. 
  - Each time you create a new set of triangles, you recursively apply this procedure to the three smaller corner triangles.
  
3. **Recursive Tree - `turtle_visualization_tree.py`**
- A fractal is something that looks the same at all different levels of magnification. If we translate this to trees and shrubs we might say that even a small twig has the same shape and characteristics as a whole tree. Using this idea we could say that a tree is a trunk, with a smaller tree going off to the right and another smaller tree going off to the left. If you think of this definition recursively it means that we will apply the recursive definition of a tree to both of the smaller left and right trees.
