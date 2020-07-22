# Path-Finding-Algorithm (Python)

A* (pronounced "A-star") is a graph traversal and path search algorithm, which is often used in many fields of computer science due to its completeness, optimality, and optimal efficiency. One major practical drawback is its {\displaystyle O(b^{d})}O(b^d) space complexity, as it stores all generated nodes in memory. Thus, in practical travel-routing systems, it is generally outperformed by algorithms which can pre-process the graph to attain better performance, as well as memory-bounded approaches; however, A* is still the best solution in many cases.
A* achieves better performance by using heuristics to guide its search.

In 1964 Nils Nilsson invented a heuristic based approach to increase the speed of Dijkstra’s algorithm. This algorithm was called A1.
In 1967 Bertram Raphael made dramatic improvements upon this algorithm, but failed to show optimality. He called this algorithm A2.
Then in 1968 Peter E.Hart introduced an argument that proved A2 was optimal when using a consistent heuristic with only minor changes. His proof of the algorithm also included a section that showed that the new A2 algorithm was the best algorithm possible given the conditions. He thus named the algorithm in kleene star syntax to be the algorithm that
starts with A and includes all possible version number or A* .

Instructions to install pygame:

Install pygame on windows : "pip install pygame"

Install pygame on macOS : "pip3 install pygame"

Instructions to use the application:

Right click mouse for starting point

Left click mouse to delete drawn line

Space : to start the search

C : clear screen
