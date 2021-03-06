# An Implementation of the Domino Shuffling Algorithm on Aztec Diamond Graphs.

## What is domino shuffling algorithm

Domino shuffling comes from combinatorics (a branch of mathematics). It firstly appeared as the fourth method in [a paper](https://arxiv.org/abs/math/9201305) proposed by Elkies, Kuperberg, Larsen and Propp to enumerate the number of domino tilings of aztec diamond graphs. In our project, it's used to sample a random tiling among all tilings with equal probability. Compare this with the Wilson algorithm animation in this repo, basically they are both devised to do the same thing: sample with uniform probability from a very very large set (in fact they can be generalized to sample under any given probability distribution). There are two reasons one should love it:

1. It's quite dedicate, just watch the gif animation in the front page. In fact until today it's still the most beautiful solution to the enumeration of domino tilings of aztec graphs.

2. It lies at the crossroad of combinatorics, probability theory, representation theory, and statistical mechanics. Many many beautiful theories are linked together and many intriguing things still need to be explained.

Well I think I should stop preaching here. If you want to learn more about this subject, besides the original paper above, Propp's paper [generalized domino shuffling](https://arxiv.org/abs/math/0111034) also serves as a good starting point.


## About the code

I haven't much to say about the code. You must understand the algorithm before you can understand the code, and you get understanding of the code soonly after you understand the algorithm (so please turn to the papers first).
