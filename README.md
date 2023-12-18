### Description:
"Find-My-Neighbouring-States" is a Python project that leverages a depth-first search algorithm to identify and analyze the largest 'country' that can be formed by combining N neighboring states in the United States based on their population. The project is designed to explore the diverse geographical and population landscapes of the United States, providing insights into regional demographics.

### Code Overview:
The code begins by loading information about regions and borders from CSV files. It then utilizes a depth-first search algorithm, implemented through functions like DFS and iterativeDDFS, to traverse through various combinations of neighboring states. The algorithm takes into account the population of each state and systematically identifies the combination of N states that yields the highest total population.

### Functionality:

load_regions(filename): Loads information about regions and their populations from a CSV file.

load_borders(filename): Loads information about state borders from a CSV file.

DFS(currentNode, graph, maxDepth, curList): Implements a depth-first search to explore neighboring states up to a specified depth.

iterativeDDFS(currentNode, graph, maxDepth): Performs an iterative depth-first search to find optimal state combinations.

transform(states, path2, n): Transforms the results to identify the combination with the highest population.

new_nation_n_states(n, reg_filename, border_filename): Main function to execute the project, taking N, region filename, and border filename as inputs.

### Usage:
To use the "Find-My-Neighbouring-States" project, provide the desired number of neighboring states (N), the filename for region information (reg_filename), and the filename for border information (border_filename). The project outputs a tuple containing the optimal combination of states and its total population.

### This project provides a valuable tool for exploring and understanding the population dynamics of the United States through a computational lens.





