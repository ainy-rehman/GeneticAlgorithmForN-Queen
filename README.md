# GeneticAlgorithmForN-Queen
N-Queens Genetic Algorithm
Problem Statement:
The N-Queens problem involves placing N chess queens on an N×N chessboard in such a way that no two queens threaten each other. The goal is to find a solution where no two queens share the same row, column, or diagonal.

Genetic Algorithm Approach:
This Python code implements a genetic algorithm to solve the N-Queens problem. The algorithm evolves a population of candidate solutions over generations, using selection, crossover, and mutation operations.

Functions:
initial_population: Generates an initial population of candidate queen placements on the chessboard.

population_fitness: Calculates the fitness of each candidate solution based on the number of non-attacking queen pairs.

selectionfunct: Selects individuals from the population for the next generation based on their fitness.

crossover: Performs crossover to create new candidate solutions from selected individuals.

applying_mutation: Applies mutation to introduce variation in the population.

Algorithm Steps:
Initialize a population of random queen placements.
Evaluate the fitness of each placement.
Repeat for a specified number of generations:
Select individuals for the next generation based on fitness.
Create new candidates through crossover.
Introduce mutation in the population.
Update the population with the new generation.
Check for a solution with maximum fitness.
If a solution is found, display the placement of queens; otherwise, terminate the algorithm.
