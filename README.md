# AtV : Anneal-ize the Vertex
### Simulated Annealing applied to the Minimum Vertex Cover Problem

by Hugues Esc_ & OGrondin

## Introduction
Anneal-ize the Vertex is a version of an efficient simulated annealing algorithm applied to the Minimum Vertex Cover Problem. 

### Formalisation of the Minimum Vertex Cover Problem

Given an undirected graph G(V, E), where V is the set of vertices and E is the set of edges, the Minimum Vertex Cover Problem (MVCP) involves finding the smallest subset V' ⊆ V such that for every edge (a, b) in E, either vertex a or vertex b, or both, belong to V'. In our implementation, the generated graphs do not contain self-loops, i.e., edges of the form (a, a). 

### Simulated Annealing 

Simulated Annealing is a global optimization algorithm that is inspired by the process of annealing in metallurgy, where a material is heated to a high temperature and then cooled slowly to reduce defects and increase its structural stability. The algorithm is used to solve optimization problems by simulating the physical process of annealing. The basic idea of the algorithm is to start with a random solution to a problem and then repeatedly make small random changes to the solution while gradually decreasing the "temperature" of the system. The probability of accepting a new solution increases as the temperature decreases, which allows the algorithm to explore a wider range of solutions and escape local optima. The algorithm terminates when the temperature reaches a low enough value, or the best solution is not improving anymore.

## Installation
To run this program, run the following commands in a terminal prompt:
```
git clone https://github.com/h-escoffier/Anneal-ize_the_Vertex
cd Anneal-ize_the_Vertex
pip install -r requirements.txt 
```

## Running AtV
Running AtV under its basic parameters:
```
./run.py 
```

## Visualisation of AtV 

<p align="center">
  <img src="ressources/example.gif" alt="Example"/>
</p>


## References

Xinshun Xu, Jun Ma, An efficient simulated annealing algorithm for the minimum vertex cover problem, Neurocomputing, Volume 69, Issues 7–9, 2006, Pages 913-916, ISSN 0925-2312, https://doi.org/10.1016/j.neucom.2005.12.016.
