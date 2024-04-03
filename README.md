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
Graph $G_1$: <br/>
Has 4 vertices ($V_1, V_2, V_3, V_4$) <br/>
$G_1$ has these mappings $f(V_1) = N_1, f(V_2) = N_2, f(V_3) = N_3, f(V_4) = N_4$ <br/>
$G_1$ is one-to-one and onto.

Graph $B_2$: <br/>
Has 5 vertices ($N_1, N_2, N_3, N_4, N_5$) <br/>
$G_2$ has these mappings $f(N_1) = V_1, f(N_2) = V_2, f(N_3) = V_3, f(N_3) = V_3$ <br/>
$G_2$ is one-to-one but not onto. In other words it is not isomorphic to $G_1$ <br/>

<br/>

$G_1$ is isomorphic to $G_2$ but $G_2$ is not isomorphic to $G_1$. There is one connection missing from $G_2$ to $G_1$, making them not completely connected.
