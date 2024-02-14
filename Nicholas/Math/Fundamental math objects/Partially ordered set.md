---
Last time checked: 2024-02-07
Complete: true
aliases:
---
# Partially ordered set
***
###### tags: #Fundamental_math_objects 
***
>[!dsn]+ Definition
>A *partial order* on a set $X$ is a binary relation, denoted by $\le$, which has the properties:
>1. $x\le x$, for all $x\in X$ *reflexive*
>2. if $x\le y$ and $y\le x$, then $x=y$, for $x,y\in X$ *antisymmetric*
>3. if $x\le y$ and $y\le z$, then $x\le z$, for $x,y,z\in X$ *transitive*
>
>The set $X$ equipped with the partial order $\le$ is called a *partially ordered set* or a *poset* and is denoted by $(X,\le)$. If $x\le y$ and $x\ne y$, then we write $x<y$.^[[[Sidney A. Morris - Topology without tears.pdf#page=265|Sidney A. Morris - "Topology without tears" p.265]]]

>Two elements $x$ and $y$ of a partially ordered set $(X,\le)$ are said to be *comparable* if either $x\le y$ or $y\le x$.^[[[Sidney A. Morris - Topology without tears.pdf#page=268|Sidney A. Morris - "Topology without tears" p.268]]] Non comparable elements can be seen in example of [[order diagram]].

>[!example]+ 
>- The sets $\mathbb{Z}$, $\mathbb{Q}$ and $\mathbb{R}$ with their usual orderings form partially ordered sets.
>- Let $\mathbb{N}$ be the set of natural numbers and let $\le$ be defined as follows:
>  $$n\le m\quad\text{if}\quad n|m$$
>  So $3\le6$ but $3\not\le5$.
>- Let $X$ be the class of all subsets of a set $U$. We can define a partial ordering on $X$ by putting
>  $$A\le B\quad\text{if}\quad A\subseteq B$$
>  where $A$ and $B$ are in $X$.
>- Let $(X,\le)$ be a partially ordered set. We can define a new partial order $\le^{*}$ on $X$ by defining
>  $$x\le^{*}y\quad\text{if}\quad y\le x$$
***
#### Keywords
- [[Set]],
- [[Binary relation]],
- [[Set of integers]],
- [[Rational numbers]],
- [[Real line]],
- [[Set of natural numbers]],
- [[Divisibility]],
- [[Order diagram]]
#### Possibly related
- 
***
#### Sources: