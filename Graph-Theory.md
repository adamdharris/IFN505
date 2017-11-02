# Graph Theory

## Shortest Path Algorithms
### Floyd's Algorithm
1. Efficiency is O(|V|<sup>3</sup>) for simplist implementation.
2. Efficiency is O(|V|<sup>3</sup>) starting at all possible start nodes, find shortest path to all possible pairs.

[Floyd's Algorithm Example](https://www.youtube.com/watch?v=t3mf2Vu9wA4)

### Dikjstra's Algorithm
1. Tells you the shortest path from one node to all other node in the graph.
2. Positive weights only, does not work for negative weighted graphs.
3. Greedy algorithm

Efficiency is `O(|V|<sup>2</sup>)` simplist implementation.  
Efficiency is `O(|E|+|V|log|V|)` to reach all possible nodes in the graph.  


[Dikjstra's Algorithm - Example 1](https://www.youtube.com/watch?v=_lHSawdgXpI)   
[Dikjstra's Algorithm - Example 2](https://www.youtube.com/watch?v=WN3Rb9wVYDY)   

### Bellman-Ford Algorithm
1. At most runs |V|-1 times to find shortest path
2. Compute all outgoing edges
3. Works on graphs negative edge wieghts
5. Not a greedy algorithm

**Efficiency is O{|E|.|V|)**

[Bellman-Ford: Theory](https://www.youtube.com/watch?v=9PHkk0UavIM)
[Bellman-Ford: Step by Step Example]](https://www.youtube.com/watch?v=obWXjtg0L64)

