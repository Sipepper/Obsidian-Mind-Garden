# Baire Category theorem
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Let $(X,d)$ be a complete metric space. If $X_{1},X_{2},\dots,X_{n},\dots$ is a sequence of open dense subsets of $X$, then the set $\bigcap_{n=1}^{\infty}X_{n}$ is also dense in $X$.^[Sidney A. Morris - "Topology without tears" p.164]

>In other words, by [[At least one element from countable partition of complete metric space has a non empty interior]] follows that we can restate the theorem as: *Complete metric space is never can be a countable union of nowhere dense subsets*.^[Fabio Silva Botelho - "Functional analysis and applied optimisation in banach spaces" p.25]

>[!proof]+
>It suffices to show that if $U$ is any non-empty open subset of $(X,d)$, then $U\cap\bigcap_{n=1}^{\infty}\ne\emptyset$.
>As $X_{1}$ is open and dense in $X$, the set $U\cap X_{1}$ is a non-empty open subset of $(X,d)$. Let $U_{1}$ be an open ball of radius at most $1$, such that $\overline{U_{1}}\subset U\cap X_{1}$.
>Inductively define for each positive integer $n>1$, an open ball $U_{n}$ of radius at most $1/n$ such that $\overline{U_{n}}\subset U_{n-1}\cap X_{n}$.
>For each positive integer $n$, let $x_{n}$ be any point in $U_{n}$. Clearly the sequence $\{x_{n}\}$ is a Cauchy sequence. As $(X,d)$ is a complete metric space, this sequence converges to a point $x\in X$.
>Observe that for every positive integer $m$ and each $n>m$, the point $x_{n}$ is in the closed set $\overline{U_{m}}$, and so the limit point $x$ is also in the set $\overline{U_{m}}$.
>Then $x\in\overline{U_{m}}$, for all $n\in\mathbb{N}$. Thus $x\in\bigcap_{n=1}^{\infty}\overline{U_{n}}$.
>But as $U\cap\bigcap_{n=1}^{\infty}X_{n}\supset\bigcap_{n=1}^{\infty}\overline{U_{n}}\ni x$, this implies that $U\cap\bigcap_{n=1}^{\infty}X_{n}\ne\emptyset$, which completes the proof of the theorem.

>[!example]+ 
>
***
#### Keywords
- [[Complete metric space]],
- [[Sequence]],
- [[Open and closed subsets]],
- [[Dense subset]],
- [[Cardinality of a set]],
- [[Nowhere dense set]],
- [[Open ball in metric space]],
- [[Closure of a set]],
- [[Cauchy sequence]],
- [[Convergence in metric spaces]],
- [[Limit point in topological space]],
- [[Set of integers]],
- [[Mathematical induction]],
#### Possibly related
- 
***
#### Sources: