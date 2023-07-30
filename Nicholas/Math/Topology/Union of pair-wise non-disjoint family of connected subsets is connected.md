# Union of pair-wise non-disjoint family of connected subsets is connected
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Let $\{Y_{i}\}$ be a family of connected subsets of topological space $(X,\tau)$ any two member of which $Y_{i}$ and $Y_{j}$ have non-empty intersection, then $\bigcup_{i}Y_{i}$ is connected subset.^[Glen E. Bredon - "Topology and geometry" p.11]

>[!proof]+
>Let $d:\bigcup_{i}Y_{i}\to D$ be a discrete-valued map. Let $p,q\in\bigcup_{i}Y_{i}$. Suppose that $p\in Y_{i}$ and $q\in Y_{j}$ and that there exist $r$ such that $r\in Y_{i}\cap Y_{j}$. Then as $d$ must be constant on every $Y_{i}$, we obtain that $d(p)=d(r)=d(q)$. But as $p$ and $q$ was chosen arbitrarily we can conclude that $d$ is a constant map. 

>[!example]+ 
>
***
#### Keywords
- [[Connected topological space]],
- [[Topological space]],
- [[Set]],
- [[Discrete valued map]],
- [[Connectedness via discrete-valued function]]
#### Possibly related
- 
***
#### Sources: