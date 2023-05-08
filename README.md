# Find-My-Neighbouring-States

- The following code uses a depth-first search algorithm to find the largest 'country' in the United States that can be formed by combining N neighboring states based on their population.

- The depth-first search algorithm starts at a particular state and explores its neighbors one by one, keeping track of which states have already been visited. This process is repeated recursively for each unvisited neighbor until there are no more unvisited neighbors. The algorithm then backtracks to the previous state and repeats the process for its unvisited neighbors until all possible paths have been explored.

- In this implementation, the algorithm starts with each state as a starting point and explores all possible combinations of N neighboring states, keeping track of the population of each combination. The algorithm then returns the combination with the highest population.
