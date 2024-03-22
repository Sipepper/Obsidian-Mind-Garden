---
Last time checked: 2024-03-03
Complete: false
aliases:
---
# Closed bounded subset of real line contains it's supremum
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>Let $S$ be a subset of $\mathbb{R}$ which is bounded above and let $p$ be the supremum of $S$. If $S$ is a closed subset of $\mathbb{R}$, then $p\in S$.^[[[Sidney A. Morris - Topology without tears.pdf#page=85|Sidney A. Morris - "Topology without tears" p.85]]]

>[!proof]+
>Suppose $p\in\mathbb{R}\setminus S$. As $\mathbb{R}\setminus S$ is open there exist real numbers $a$ and $b$ with $a<b$ such that $p\in(a,b)\subseteq\mathbb{R}\setminus S$. As $p$ is the least upper bound for $S$ and $a<p$, it is clear that there exists an $x\in S$ such that $a<x$. Also $x<p<b$, and so $x\in(a,b)\subseteq\mathbb{R}\setminus S$. But this is a contradiction, since $x\in S$. Hence our supposition is false and $p\in S$.

>[!example]+
>
***
#### Keywords
- [[Set]],
- [[Real line]],
- [[Bounded set]],
- [[Supremum and infinum]],
- [[Open and closed subsets]],
- [[Interval]],
#### Possibly related
- 
***
#### Sources: