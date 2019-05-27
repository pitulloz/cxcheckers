# cxcheckers
Checkers board game for Skycoin, programmed with CX Programming Language: https://www.skycoin.net/cx/

tested using CX version 0.7 beta

CX-Chain test:

```
cx-0.7b checkers-bc.cx 
8 | = | O | = | O | = | O | = | O |
7 | O | = | O | = | O | = | O | = |
6 | = | O | = | O | = | O | = | O |
5 |   | = |   | = |   | = |   | = |
4 | = |   | = |   | = |   | = |   |
3 | X | = | X | = | X | = | X | = |
2 | = | X | = | X | = | X | = | = |
1 | X | = | X | = | X | = | X | = |
    A   B   C   D   E   F   G   H 
Player 1 (X) move (source: a 3, destination: b 4
8 | = | O | = | O | = | O | = | O |
7 | O | = | O | = | O | = | O | = |
6 | = | O | = | O | = | O | = | O |
5 |   | = |   | = |   | = |   | = |
4 | = | X | = |   | = |   | = |   |
3 |   | = | X | = | X | = | X | = |
2 | = | X | = | X | = | X | = | = |
1 | X | = | X | = | X | = | X | = |
    A   B   C   D   E   F   G   H 
Player 2 (O) move (source: d 6, destination: c 5
8 | = | O | = | O | = | O | = | O |
7 | O | = | O | = | O | = | O | = |
6 | = | O | = |   | = | O | = | O |
5 |   | = | O | = |   | = |   | = |
4 | = | X | = |   | = |   | = |   |
3 |   | = | X | = | X | = | X | = |
2 | = | X | = | X | = | X | = | = |
1 | X | = | X | = | X | = | X | = |
    A   B   C   D   E   F   G   H 
Player 1 (X) move (source: b 4, destination: d 6
Captured!
8 | = | O | = | O | = | O | = | O |
7 | O | = | O | = | O | = | O | = |
6 | = | O | = | X | = | O | = | O |
5 |   | = |   | = |   | = |   | = |
4 | = |   | = |   | = |   | = |   |
3 |   | = | X | = | X | = | X | = |
2 | = | X | = | X | = | X | = | = |
1 | X | = | X | = | X | = | X | = |
    A   B   C   D   E   F   G   H 

```

Interactive (Keyboard input) game without bc feature:

```
cx checkers-interactive.cx
Welcome to CX Checkers!

You play by specifying which piece to move, and the position to move it too
You can string captures, the game will let you know if you must take the next capture
You can also 'quit' at anytime

Have fun!

8 | = | O | = | O | = | O | = | O |
7 | O | = | O | = | O | = | O | = |
6 | = | O | = | O | = | O | = | O |
5 |   | = |   | = |   | = |   | = |
4 | = |   | = |   | = |   | = |   |
3 | X | = | X | = | X | = | X | = |
2 | = | X | = | X | = | X | = | X |
1 | X | = | X | = | X | = | X | = |
    A   B   C   D   E   F   G   H 
Player 1 (X) move (ex: a[enter]3[enter]b[enter]4[enter]): 
a
3
b
4
8 | = | O | = | O | = | O | = | O |
7 | O | = | O | = | O | = | O | = |
6 | = | O | = | O | = | O | = | O |
5 |   | = |   | = |   | = |   | = |
4 | = | X | = |   | = |   | = |   |
3 |   | = | X | = | X | = | X | = |
2 | = | X | = | X | = | X | = | X |
1 | X | = | X | = | X | = | X | = |
    A   B   C   D   E   F   G   H 
Player 2 (O) move (ex: a[enter]3[enter]b[enter]4[enter]): 
```

reference:

https://github.com/skycoin/cx/wiki/CX-Chains-Tutorial

https://github.com/cdgriffith/go_checkers


