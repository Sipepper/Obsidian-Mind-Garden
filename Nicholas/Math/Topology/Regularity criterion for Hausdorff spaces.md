---
Last time checked: 2024-03-12
Complete: false
aliases:
---
# Regularity criterion for Hausdorff spaces
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>A Hausdorff topological space $(X,\tau)$ is regular if and only if closed neighbourhood of every point form a neighbourhood basis for that point.^[[[Glen E. Bredon - Geometry and Topology.pdf#page=26|Glen E. Bredon - "Geometry and Topology" p.13]]]

>[!proof]+
>$\Rightarrow$
>Suppose that $X$ is regular, let $x\in V$, where $V$ is an open neighbourhood of $x$, and put $C=X\setminus V$. By regularity there exists open sets $U,W$ such that $x\in U$, $C\subset W$ and $U\cap W=\emptyset$. Then $X\setminus W$ be a closed set and we have that $X\setminus W\subset X\setminus C=V$, and thus every neighbourhood $V$ of $x$ contains a closed neighbourhood $X\setminus W$ of $x$, as required.
>
>$\Leftarrow$
>Conversely, suppose that every point has a closed neighbourhood basis. Let $x\notin C$ where $C$ is a closed set, put $V=X\setminus C$. By supposition there exist an open set $U$ such that $\overline{U}\subset V=X\setminus C$ and $x\in U$. Then $C\subset X\setminus\overline{U}$, and $U\cap(X\setminus\overline{U})=\emptyset$. And thus $X$ is regular.

>[!example]+ 
>
***
#### Keywords
- [[Hausdorff space]],
- [[Topological space]],
- [[Regular and T3 space]],
- [[Open and closed subsets]],
- [[Neighborhood basis at point in topological space]],
- [[Neighborhood in topological space]],
- [[Set]],
- [[Closure of a set]]
#### Possibly related
- 
***
#### Sources: