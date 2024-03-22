---
Last time checked: 2024-03-04
Complete: true
aliases:
---
# Connected subspaces of real line
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>A subspace $S$ of $\mathbb{R}$ is connected if and only if it is an interval.^[[[Sidney A. Morris - Topology without tears.pdf#page=104|Sidney A. Morris - "Topology without tears" p.104]]]

>[!proof]+
>As all intervals are connected, which can be proven adapting proof of [[clopen subsets of the set of real numbers]].
>
>Suppose $T\ne\mathbb{R}$ and $T\ne\emptyset$. Then there exists an element $x\in T$ and an element $z\in\mathbb{R}\setminus T$. Without loss of generality, assume $x<z$. put $S=T\cap[x,z]$. Then $S$, begin the intersection of two closed sets, is closed. It is also bounded above, since $z$ is obviously an upper bound. Let $p$ be the supremum of $S$. By [[closed bounded subset of real line contains it's supremum]], $p\in S$. Since $p\in[x,z]$, $p\le z$. As $z\in\mathbb{R}\setminus S$, $p\ne z$ and so $p<z$.
>
>Now $T$ is also an open set and $p\in T$. So there exist $a$ and $b$ in $\mathbb{R}$ with $a<b$ such that $p\in(a,b)\subseteq T$. Let $t$ be such that $p<t<\min\{b,z\}$. So $t\in T$ and $t\in[p,z]$. Thus $t\in T\cap[x,z]=S$. This is a contradiction since $t>p$ and $p$ is the supremum of $S$. Hence our supposition is false and consequently $T=\mathbb{R}$ or $T=\emptyset$.

>[!example]+ 
>Let $(2,4)\subset\mathbb{R}$ be some interval. Then it's connected topological space with topology induced from euclidean topology on $\mathbb{R}$.
***
#### Keywords
- [[Real line]],
- [[Connected topological space]],
- [[Interval]],
- [[Set]],
- [[Open and closed subsets]],
- [[Bounded set]],
- [[Greatest element, upper bound and maximal element of a partially ordered set]],
- [[Supremum and infinum]],
- [[Euclidean topology]]
#### Possibly related
- 
***
#### Sources: