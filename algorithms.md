# Span intersection (e.g. for drawing z-ordered polygons)
- http://www.gripho.it/sbuffer.en.html

# Line drawing and error correction style algorithms (e.g. bresenham)
#### bresenham algorithm
- http://members.chello.at/~easyfilter/bresenham.html
- https://www.romanblack.com/one_sec.htm

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

#### Hash Life
- https://en.wikipedia.org/wiki/Hashlife
- http://www.drdobbs.com/jvm/an-algorithm-for-compressing-space-and-t/184406478

> notes: The final word on game of life algorithms (and 2d cellular automata in general?)  Uses a hash-consed quadtree to calculate ever increasing numbers of generations each step.
> Drawbacks:  Doesn't handle dynamic or non-repetitive patterns well.

# Regular Expressions

#### Regular Expression Search Algorithm - Ken Thompson
- https://www.fing.edu.uy/inco/cursos/intropln/material/p419-thompson.pdf
> notes: compiles regular expressions to machine code which evaluates a NFA breadth-first, by maintaining a list of current states (which are machine code, that when evaluated, will add a new state (which is more machine code!) to the list of next states)

> each state only adds the next state if it passes, however some states modify the current list of states (which is the running machine code!)

> https://swtch.com/~rsc/regexp/ibm7094.html  (useful for reading the above paper)

- https://swtch.com/~rsc/regexp/regexp-bytecode.c.txt
> conversion of the above to C w/ bytecode vm 

- https://swtch.com/~rsc/regexp/regexp-x86.c.txt
> conversion of the above to C w/ runtime generated x86 code


#### Regular Expression Matching Can Be Simple And Fast
- https://swtch.com/~rsc/regexp/regexp1.html


# Hashing

#### Hash Consing
- https://en.wikipedia.org/wiki/Hash_consing

#### Pearson Hashing
- https://en.wikipedia.org/wiki/Pearson_hashing

# Collision Detection
#### Spatial grid/hashing
- https://web.archive.org/web/20160418004153/http://freespace.virgin.net/hugo.elias/models/m_colide.htm
- https://conkerjo.wordpress.com/2009/06/13/spatial-hashing-implementation-for-fast-2d-collisions/

