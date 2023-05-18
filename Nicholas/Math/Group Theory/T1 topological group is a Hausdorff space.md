# T1 topological group is a Hausdorff space
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Direct strict note
>Any topological group $(G,\tau)$ which is a $T_{1}$-space is also a Hausdorff space.^[Sidney A. Morris - "Topology without tears" p.516]

>[!proof]+
>Let $x$ and $y$ be disticnt points of $G$. Then $x^{-1}y\ne e$. The set $G\setminus\set{x^{-1}y}$ is an open neighbourhood of $e$ and so, by [[Symmetric neighborhoods in topological groups]], there exists an open symmetric neighbourhood $V$ of $e$ such that $V^{2}\subseteq G\setminus\set{x^{-1}y}$. Thus $x^{-1}y\notin V^{2}$.
>
>Now $xV$ and $yV$ are open neighbourhoods of $x$ and $y$, respectively. Suppose $xV\cap yV\ne\emptyset$. Then $xv_{1}=yv_{2}$, where $v_{1}$ and $v_{2}$ are in $V$; that is, $x^{-1}y=v_{1}v_{2}^{-1}\in VV^{-1}=V^{2}$, which is a contradiction. Hence $xV\cap yV=\emptyset$ and so $(G,\tau)$ is Hausdorff. 

>So to check that a topological group is Hausdorff it is only necessary to verify that $\set{e}$ is a closed set.(i.e. every other point is also a closed set)
***
#### Keywords
- [[Topological group]],
- [[Set]],
- [[T1 space]],
- [[Hausdorff space]],
- [[Neighborhood in topological space]],
- [[Symmetric neighborhoods in topological groups]],
- [[Group coset]],
- [[Open and closed subsets]]
#### Possibly related
- 
***
#### Sources: