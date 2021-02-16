# @mamud's Maze in RDF

## Start server

$ nodejs app.js


## Invoke user agent

The beginner's maze:

$ ldfu.sh -p beginner-maze.n3 -q exit.rq -

The expert's maze:

$ ldfu.sh -p expert-maze.n3 -q exit.rq -

## Query for the path to exit

$ ldfu.sh -p beginner-maze.n3 -q path-to-exit.rq -

Prints out the sequence of rooms to the exit:

```
?x ?start ?r1 ?r2 ?r3 ?r4 ?r5 ?r6 ?r7 ?r8 ?r9 ?r10 ?exit .
<http://localhost:1337/01-a-beginner-maze#it> <http://localhost:1337/01-a-beginner-maze/0#it> <http://localhost:1337/01-a-beginner-maze/5#it> <http://localhost:1337/01-a-beginner-maze/10#it> <http://localhost:1337/01-a-beginner-maze/11#it> <http://localhost:1337/01-a-beginner-maze/16#it> <http://localhost:1337/01-a-beginner-maze/21#it> <http://localhost:1337/01-a-beginner-maze/22#it> <http://localhost:1337/01-a-beginner-maze/17#it> <http://localhost:1337/01-a-beginner-maze/18#it> <http://localhost:1337/01-a-beginner-maze/19#it> <http://localhost:1337/01-a-beginner-maze/24#it> <http://localhost:1337/01-a-beginner-maze/999#it> .
```