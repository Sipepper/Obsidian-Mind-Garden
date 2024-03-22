---
Last time checked: 2024-02-23
Complete: false
aliases:
---
# Any open subgroup of topological group is also closed
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Proposition
>Any open subgroup $H$ of a topological group $G$ is (also) closed.^[[[Sidney A. Morris - Topology without tears.pdf#page=520|Sidney A. Morris - "Topology without tears" p.520]]]

>[!proof]+
>Let $x_{i}$, $i\in I$ be a set of right coset representatives of $H$ in $G$. So $G=\bigcup_{i\in I}Hx_{i}$, where $Hx_{i}\cap Hx_{J}=\emptyset$, for any distinct $i$ and $j$ in the index set $I$. Since $H$ is open, so is $Hx_{i}$ open, for each $i\in I$.
>Of course for some $i_{0}\in I$, $Hx_{i_{0}}=H$, that is, we have $G=H\cup\left(\bigcup_{i\in J}Hx_{i}\right)$, where $J=I\setminus\set{i_{0}}$.
>These two terms are disjoint and the second term, being the union of open sets, is open. So $H$ is the complement (in $G$) of an open set, and is therefore closed in $G$.

>The converse is *false*, for example: $\mathbb{Z}$ is a closed subgroup of $\mathbb{R}$, but it is not an open subgroup of $\mathbb{R}$.

>[!example]+
>

***
#### Keywords
- [[Open and closed subsets]],
- [[Topological group]],
- [[Set]],
- [[Group coset]],
- [[Set of integers]],
- [[Real line]],
#### Possibly related
- [[Topological group translations are homeomorphisms]],
***
#### Sources: