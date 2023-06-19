# Compact subset of Hausdorff space is closed
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>Let $(X,\tau)$ be a Hausdorff topological space, then any compact subset $A$ will also be closed in $(X,\tau)$.^[Fabio Silva Botelho - "Functional analysis and applied optimization in banach spaces" p.9]

>[!proof]
>Let $U$ be a Hausdorff space and $A$ be a compact subset of $U$. Let $x\in A$ and $y\in A^{c}$, then there exists open subsets $O_{x}$ and $O_{y}^{x}$ such that $x\in O_{x}$, $y\in O_{y}^{x}$ and $O_{x}\cap O_{y}^{x}=\emptyset$. It's clear that $A\subset\bigcup\limits_{x\in A}O_{x}$, and because $A$ is compact we can extract a sequence $\set{x_{1},x_{2},\dots,x_{n}}$ such that $A\subset\bigcup\limits_{i=1}^{n}O_{x_{i}}$, i.e. finite subcover. For a chosen $y\in A^{c}$ we have that $y\in\bigcap\limits_{i=1}^{n}O_{y}^{x_{i}}$ and $\left(\bigcap\limits_{i=1}^{n}O_{y}^{x_{i}}\right)\cap\left(\bigcup\limits_{i=1}^{n}O_{x_{i}}\right)=\emptyset$. Because $\bigcup\limits_{i=1}^{n}O_{y}^{x_{i}}$ is open and $y$ is an arbitrary point from $A^{c}$ we obtained that $A^{c}$ is an open set, therefore $A$ is closed.

>[!proof]+
>https://math.stackexchange.com/questions/83355/how-to-prove-that-a-compact-set-in-a-hausdorff-topological-space-is-closed
***
#### Keywords
- [[Hausdorff space]],
- [[Topological space]],
- [[Compact set]],
- [[Open and closed subsets]],
- [[Covering of a set]],
- [[Cardinality of a set]],
- [[Sequence]],
- [[Set]]
#### Possibly related
- 
***
#### Sources: