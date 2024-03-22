---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Uniformly convergent sequence of continuous functions is continuous
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>Let $f_{1},f_{2},\dots$ be a sequence of continuous functions from topological space $(X,\tau)$ into the metric space $(Y,d)$ which converges uniformly to a function $f:X\to Y$, then $f$ is a continuous function.^[[[Glen E. Bredon - Geometry and Topology.pdf#page=19|Glen E. Bredon - "Geometry and Topology" p.6]]]

>[!proof]+
>For a given $\varepsilon>0$ let $n_{0}$ be some number for which
>$$n\ge n_{0}\quad\Rightarrow\quad d(f(x),f_{n}(x))<\varepsilon\quad\forall x\in X$$
>Let $x_{0}$ be some point from $(X,\tau)$, by continuity of $f_{n_{0}}$ there exists some neighbourhood $N$ of $x_{0}$ such that $x\in N\Rightarrow d(f_{n_{0}}(x),f_{n_{0}}(x_{0}))<\varepsilon/3$. And therefore, for any $x\in N$ we have that
>$$\begin{align}d(f(x),f(x_{0}))&\le d(f(x),f_{n_{0}}(x))+d(f_{n_{0}}(x),f_{n_{0}}(x_{0}))+d(f_{n_{0}}(x_{0}),f(x_{0}))\\&<\varepsilon/3+\varepsilon/3+\varepsilon/3=\varepsilon \end{align}$$
>

>[!example]+
>
***
#### Keywords
- [[Sequence]],
- [[Continuous mapping]],
- [[Topological space]],
- [[Metric space]],
- [[Uniform convergence]],
- [[Function(mapping)]],
- [[Neighborhood in topological space]],
#### Possibly related
- 
***
#### Sources: