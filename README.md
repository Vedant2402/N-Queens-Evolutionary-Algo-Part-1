# N-Queens-Evolutionary-Algo-Part-1

The Eight-Queen Problem ♛: An Evolutionary Algorithm Approach
This is the problem of placing eight queens on a regular 8x8 chessboard so that no two of them can check each other.

It is important to note the problem can be generalised, yielding the N-queen problem.

Representation
To design an EA to search P we need to define a representation of phenotype form P, P is the set of all such board configurations, which specify hte positoons of all eight queens.

A genotype, or chromosome, is a permutation of the numbers 1,…,8, and a given g=<i1,…,i8> denotes the (unique) board configuration, where the nth column contains exactly one queen placed on the in the row.
------------------------------------------------------------------------------------------------------

Overview

The N-Queens problem involves placing N queens on an N×N chessboard such that no two queens threaten each other. This means no two queens share the same row, column, or diagonal.

We'll use a Genetic Algorithm to find a solution:

Import Python Libraries
Initialize Population with Random Candidate Solutions
Evaluate Each Candidate (Fitness Function)
Selection, Recombination, Mutation, and Creating Next Generation
Plot Fitness Over Generations
