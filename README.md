[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/QM7QGF1q)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Proof By Contradiction

I recieved help from the lab TA. <br/>
For a graph to be completely connected every node has an edge to every other node. To be isomorphic the mapping of one graphs nodes to the others nodes must be one-to-one and unto. So for A to be isomorphic to B it's mappings must be one-to-one and onto. To be one-to-one, A's nodes map to distinct nodes of B. And to be onto, A's nodes must have a map to every node in B. <br/>
<br/>
A has 4 nodes: $V_1, V_2, V_3, V_4$ and B has 4 nodes: $N_1, N_2, N_3, N_4. in both graphs each node is connected to two other nodes, forming a square (just the perimeter). The mappings are: $f(V_1) = N_1, f(V_2) = N_2, f(V_3) = N_3, f(V_4) = N_4$. Niether of the graphs are completely connected (there are 4 nodes, each node only connects to two other), and the mappings are one-to-one (each node in A maps to a distinct/ different node in B) and onto (one of A's nodes map to every node in B). This is an example of two graphs that are isomorphic but not completely connected.


