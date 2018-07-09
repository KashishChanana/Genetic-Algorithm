# Genetic-Algorithm

Outline of the Basic Genetic Algorithm

[Start] Generate random population of n chromosomes (suitable solutions for the problem)

[Fitness] Evaluate the fitness f(x) of each chromosome x in the population

[New population] Create a new population by repeating following steps until the new population is complete

[Selection] Select two parent chromosomes from a population according to their fitness (the better fitness, the bigger chance to be selected)

[Crossover] With a crossover probability cross over the parents to form a new offspring (children). If no crossover was performed, offspring is an exact copy of parents.

[Mutation] With a mutation probability mutate new offspring at each locus (position in chromosome).

[Accepting] Place new offspring in a new population

[Replace] Use new generated population for a further run of algorithm

[Test] If the end condition is satisfied, stop, and return the best solution in current population

[Loop] Go to step 2


