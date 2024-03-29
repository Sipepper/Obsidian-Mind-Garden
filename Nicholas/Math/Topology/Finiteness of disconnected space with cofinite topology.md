---
Last time checked: 2024-03-13
Complete: true
aliases:
---
# Finiteness of disconnected space with cofinite topology
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>Let $\tau$ be a cofinite topology on a set $X$. If $X$ has at least $3$ distinct clopen subsets, then $X$ is a finite set.^[[[Sidney A. Morris - Topology without tears.pdf#page=40|Sidney A. Morris - "Topology without tears" p.40]]]

>[!proof]+
>As our space $(X,\tau)$ has $3$ distinct clopen subsets, we know that there is a clopen subset $S$ of $X$ such that $S\ne X$ and $S\ne\emptyset$. As $S$ is open in $(X,\tau)$. Then it's complement $X\setminus S$ is a closed set.
>
>Thus $S$ and $X\setminus S$ are closed in the finite-closed topology $\tau$. Therefore $S$
 and $X\setminus S$ are both finite, since neither equals $X$. But $X=S\cup(X\setminus S)$ and so $X$ is the union of two finite sets. Thus $X$ is a finite set, as required.
***
#### Keywords
- [[Cofinite topology]],
- [[Set]],
- [[Open and closed subsets]],
- [[Cardinality of a set]],
- [[Topological space]],
#### Possibly related
- [[Connected topological space]],
***
#### Sources: