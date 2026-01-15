# EHO-Amir-Sghaier
This code implements a simple version of the Elephant Herding Optimization (EHO) algorithm to minimize a mathematical function.

The script starts by randomly generating a population of candidate solutions, where each solution represents an elephant in a two-dimensional search space. These elephants are then divided into several clans.

At each iteration, the code evaluates the quality of every elephant using the objective function. Within each clan, the elephant with the best fitness value is selected as the matriarch.

The positions of all elephants in the clan are updated by moving them closer to the matriarch, which improves the solutions locally. After that, the worst-performing elephant in each clan is replaced with a new randomly generated solution to maintain diversity and encourage exploration.

This process is repeated for a fixed number of iterations. During each iteration, the code tracks and prints the best solution found so far.

Finally, the script outputs the best solution obtained, which represents the minimum value of the objective function found by the algorithm.
