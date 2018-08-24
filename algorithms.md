# Span intersection (e.g. for drawing z-ordered polygons)
- http://www.gripho.it/sbuffer.en.html

# Line drawing and error correction style algorithms (e.g. bresenham)
#### bresenham algorithm
- http://members.chello.at/~easyfilter/bresenham.html

#### run-length sliced bresenham
- http://www.phatcode.net/res/224/files/html/ch36/36-01.html

#### something even faster than bresenham?
- https://hbfs.wordpress.com/2009/07/28/faster-than-bresenhams-algorithm/


# Hexagon algorithms
-  https://www.redblobgames.com/grids/hexagons/


# Game of Life

#### List Life
- http://dotat.at/prog/life/life.html
> notes: uses a sparse dynamic array, single scan over universe for each generation, calculate multiple cells in parallel


# Regular Expressions

#### Regular Expression Search Algorithm - Ken Thompson
- https://www.fing.edu.uy/inco/cursos/intropln/material/p419-thompson.pdf
> notes: compiles regular expressions to machine code which evaluates a NFA breadth-first, by maintaining a list of current states (which are machine code, that when evaluated, will add a new state (which is more machine code!) to the list of next states)

> each state only adds the next state if it passes, however some states modify the current list of states (which is the running machine code!)
