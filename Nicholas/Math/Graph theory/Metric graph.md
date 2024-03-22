---
Last time checked: 2024-02-17
Complete: false
aliases:
---
# Metric graph
***
###### tags: #Geometry #Graph_theory  
***
#### Metric on quotient space of a graph
>[!dsn]+ Definition
>Let $X$ be a quotient space of combinatorial graph $\mathcal{G}$. To define a metric on $X$, first we specify a map $$\lambda:\mathcal{E}\to(0,\infty)$$ associating a *length* $\lambda(e)$ to each edge $e$.^[[[Martin R. Bridson, Andrea Haefliger - Metric spaces of non-positive curvature.pdf#page=26|Martin R. Bridson, Andrea Haefliger - "Metric spaces of non-positive curvature" p.7]]]
>
>*Piecewise linear path* is a map $c:[0,1]\to X$ for which there is a partition $0=t_{0}\le t_{1}\le\dots\le t_{n}=1$ such that each $c|_{[t_{i},t_{i+1}]}$ is of the form $f_{e_{i}}\circ c_{i}$, where $e_{i}\in\mathcal{E}$ and $c_{i}$ is an affine(linear + translation) map from $[t_{i},t_{i+1}]$ into $[0,1]$.
>We say that $c$ joins $x$ to $y$ if $c(0)=x$ and $c(1)=y$. The *length of* $c$ is defined to be $$l(c)=\sum\limits_{i=0}^{n-1}l(c_{i})$$ where $l(c_{i})=\lambda(e_{i})|c_{i}(t_{i})-c_{i+1}|$. We assuming that $X$ is connected, i.e. any two points are joined by such a path.

#### Pseudometric and metric graph
>[!dsn]+ Definition
>We define a pseudometric $d:X\times X\to[0,\infty]$ by setting $d(x,y)$ equal to the infimum of the length of piecewise linear paths joining $x$ to $y$. 
>
>>The space $X$ with its pseudometric $d$ is called a *metric graph*.
>
>For any edge $e$, the distance between $p(e,1/2)$ and $\partial_{i}(e)$ is $\lambda(e)/2$.

>If the graph has only one edge $e$ and this is a loop, then the corresponding metric graph is isometric to a circle of length $\lambda(e)$.

>[!example]
>Suppose that the set of vertices $\mathcal{V}=\{v_{n}\}_{n}$ is indexed by $\mathbb{N}\cup\{0\}$ and that the set of edges $\{e_{n}\}_{n}$ is indexed by the positive integers. Suppose $\partial_{0}(e_{n})=v_{n-1}$ and $\partial_{1}(e_{n})=v_{n}$. In this case, if $\lambda(e_{n})=1$ for each $n$, then $X$ is isometric to $[0,\infty)$; if $\lambda(e_{n})=1/2^{n}$, then $X$ is isometric to the interval $[0,2)$; 
>>In general $X$ is isometric to $[0,b)$ where $b=\sum\lambda(e_{n})$.

>[!example]
>Suppose that $\mathcal{V}$ has two elements $v_{0}$ and $v_{1}$, and the set of edges $\mathcal{E}=\{e_{n}\}_{n}$ is indexed by natural numbers, and that $\partial_{i}(e_{n})=v_{i}$.
>>If $\lambda(e_{n})=1/n$, then $d$ is not a metric, because $d(v_{0},v_{1})=0$.
>
>>If $\lambda(e_{n})=1+1/n$, then $d$ is a metric, $d(v_{0},v_{1})=1$, the metric space $X$ is complete, but there is no geodesic joining $v_{0}$ to $v_{1}$. 
#### Keywords
- [[Quotient space of combinatorial graph]],
- [[Metric space]],
- [[Function(mapping)]],
- [[Linear map]],
- [[Curve in metric space]],
- [[Restriction and extension of a mapping]],
- [[Affine map]],
- [[Connected topological space]],
- [[Absolute value]],
- [[Pseudometric]],
- [[Cartesian product of sets]],
- [[Supremum and infinum]],
- [[Graph or 1-dimensional complex]],
- [[Isometry]],
- [[Set]],
- [[Set of integers]],
- [[Complete metric space]],
- [[Geodesic path in metric space]]
#### Possibly related
- 
***
#### Sources:
