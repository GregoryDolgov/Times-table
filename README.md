# Times-table
Inspired by [mathologer](https://www.youtube.com/channel/UC1_uAIS3r8Vu6JjXWvastJg), flexible times table implementation.

Creates a circumference and highlights specific nodes. Each node given an index from [0, Modulo). Random node **N** connects with a line with a node **N*M**, where **M** is a multiplier. This simple algorithm can give you very beatiful patterns.

#### Control shortcuts
* **Space** - Play/Stop simulation.
* __*__ - Round up the multiplier.
* **/** - Round down the multiplier.
* **+** - Step forward.
* **-** - Step back.
* **Left arrow** - Rotate projection counterclockwise.
* **Right arrow** - Rotate projection clockwise.
* **Up arrow** - Rotate projection clockwise faster.
* **Down arrow** - Set projection's angle to 0.
* **j** - Modify multiplier.
* **s** - Modify step value.
* **n** - Modify modulo(nodes count).
* **esc** - press to cancel, double press to exit.

#### Cool patterns
1. n = 1500, j = 125
2. n = 100, j = 359
3. n = 1000, j = 3590
4. n = 1500, j = 1235, s = 0.0001
5. n = 1000, j = 1751
6. n = 1000, j = 1801
7. n = 1000, j = 1826
8. n = 1000, j = 1833
9. n = 1000, j = 1857
10. n = 1000, j = 1997-1999, s = 0.01
