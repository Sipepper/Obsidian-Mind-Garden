# First axiom of countability
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>A topological space $(X,\tau)$ is said to satisfy the *first axiom of countability* (or to be *first countable*) if for each $x\in N$, there exists a countable family $U_{i}$, $i\in\mathbb{N}$ of open sets containing $x$, such that if $V\in\tau$ and $x\in V$, then $V\supseteq U_{n}$, for some $n$. That is $(X,\tau)$ has a countable neighbourhood basis at every point.^[Sidney A. Morris - "Topology without tears" p.300]

>[!example]+ 
>Every metric space is first-countable.
>
>>[!proof]+
>>Let $(X,d)$ be a metric space. Consider a family $B$ of open balls
>>$$B_{r_{n}}=\{y\in X:d(x,y)=r_{n}=1/n\}$$
>>Let $V$ be some arbitrary open neighborhood of $x$, then by putting
>>$$r_{n}<\frac{1}{2}\inf\limits_{a\in X\setminus V}d(x,a)$$
>>we get that $B_{r_{n}}\subset V$ for any open neighborhood $V$, thus $B$ is a countable neighborhood basis at a point $x$. As $x$ was chosen arbitrary $(X,d)$ is indeed first-countable.
***
#### Keywords
- [[Topological space]],
- [[Cardinality of a set]],
- [[Open and closed subsets]],
- [[Neighborhood basis at point in topological space]],
- [[Metric space]],
- [[Neighborhood in topological space]],
- [[Open ball in metric space]],
- [[Neighborhood in topological space]],
- [[Supremum and infinum]],
#### Possibly related
- 
***
#### Sources: