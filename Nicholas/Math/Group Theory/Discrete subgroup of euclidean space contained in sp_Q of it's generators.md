# Discrete subgroup of euclidean space contained in sp_Q of it's generators
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Direct strict note
>Let $G$ be a discrete subgroup of $\mathbb{R}^{n}$ of rank $p$, and $a_{1},\dots,a_{p}\in G$ a basis for $\text{gp}_{\mathbb{R}}(G)$. Let $P$ be the closed parallelotope with centre $0$ and basis vectors $a_{1},\dots,a_{p}$; that is,
>$$P=\left\{\sum\limits_{i=1}^{p}r_{i}a_{i}:-1\le r_{i}\le1,i=1,\dots,p \right\}$$
>then $G\cap P$ is finite and $\text{gp}(G\cap P)=G$. Further, every point in $G$ is a linear combination of $\{a_{1},\dots,a_{p}\}$ with rational coefficients; that is, $G\subseteq\text{sp}_{\mathbb{Q}}\{a_{1},\dots,a_{p}\}$.^[Sidney A. Morris - "Topology without tears" p.540]

>[!proof]+
>As $P$ is compact and $G$ is discrete (and closed in $\mathbb{R}^{n}$), $G\cap P$ is discrete and compact, and hence finite.
>
>Now $G\subseteq\text{sp}_{\mathbb{R}}\{a_{1},\dots,a_{p}\}$ implies that each $x\in G$ can be written as $x=\sum\limits_{i=1}^{p}t_{i}a_{i}$, $t_{i}\in \mathbb{R}$. For each positive integer $m$, the point
>$$z_{m}=mx-\sum\limits_{i=1}^{p}\lfloor mt_{i}\rfloor a_{i}=\sum\limits_{i=1}^{p}(mt_{i}-\lfloor mt_{i}\rfloor)a_{i}$$
>where $\lfloor\cdot\rfloor$ denotes the integer part of a number, belongs to $G$. As
>$$0\le mt_{i}-\lfloor mt_{i}\rfloor<1,\quad z_{m}\in P$$
>hence $x=z_{1}+\sum\limits_{i=1}^{p}\lfloor t_{i} \rfloor a_{i}$, which says that $\text{gp}(G\cap P)=G$.
>
>Further, as $G\cap P$ is finite there exist integers $h$ and $k$ such that $z_{h}=z_{k}$. So 
>$$(h-k)t_{i}=\lfloor ht_{i} \rfloor-\lfloor kt_{i} \rfloor\qquad x\in\text{sp}_{\mathbb{Q}}\{a_{1},\dots,a_{p}\}$$

>[!example]+ 
>
***
#### Keywords
- [[Discrete group]],
- [[Euclidean space]],
- [[Basis of a free abelian group]],
- [[sp_Q and sp_R subgroups of Rn]],
- [[Open and closed subsets]],
- [[Basis of vector space]],
- [[Cardinality of a set]],
- [[Linear span]]
#### Possibly related
- 
***
#### Sources: