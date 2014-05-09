Random Number on Normal Distribution
==================

Random integer with a range following normal distribution.

Inspired by [Galton Board](http://mathworld.wolfram.com/GaltonBoard.html), by which could apporximate a normal distribution.

>![Galton Board](http://mathworld.wolfram.com/images/eps-gif/GaltonBoard_1000.gif)

>Each time a ball hits one of the nails, it can bounce right (or left) with some probability p (and q=1-p). For symmetrically placed nails, balls will bounce left or right with equal probability, so p=q=1/2. If the rows are numbered from 0 to N-1, the path of each falling ball is a Bernoulli trial consisting of N steps. Each ball crosses the bottom row hitting the nth peg from the left (where 0<=n<=N-1) iff it has taken exactly n right turns, which occurs with probability

>![equation](http://mathworld.wolfram.com/images/equations/GaltonBoard/NumberedEquation1.gif) 

This program could be used for drawing prizes, simulating real problems and statistic tasks.

The function takes the start and end of a range, and return a random number within the range.

TODO:
=========================

1. ~~Check the validation of start and end parameters~~
2. Optimization
3. Calculate the complexity
