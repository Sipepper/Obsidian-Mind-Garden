# Hausdorffness by a diagonal
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Let $(X,\tau)$ be a topological space, then $(X,\tau)$ is Hausdorff space if and only if it's *diagonal* of product $X\times X$ is closed in $X\times X$.

>[!proof]+
>Let $(X,\tau)$ be a Hausdorff space. Then for any pair of points $x,y\in(X,\tau)$ there exists neighborhoods $O_{x},O_{y}\in\tau$, such that $O_{x}\cap O_{y}=\emptyset$. $D=\{(x,x)\in X\times X:x\in(X,\tau)\}$. Now we show that set $(X\times X)\setminus D$ is open. As basic open set in $X\times X$ has a form $O_{1}\times O_{2}$, where $O_{i}\in\tau$ then $O_{x}\cap O_{y}=\emptyset$ imply $(O_{x}\times O_{y})\cap D=\emptyset$, else element $x$ will lie in intersection $O_{x}\cap O_{y}$ which is a contradiction. Therefore, we obtain an open neighborhood $U$ of $(x,y)$. As point $(x,y)\in(X\times X)\setminus D$ was chosen arbitrarily, $(X\times X)\setminus D$ is open.
>
>Let $D$ is a closed set in $X\times X$, then $(X\times X)\setminus D$ is open. As $(X\times X)\setminus D$ is open, then for any point $(x,y)\in(X\times X)\setminus D$ there exists an open neighborhood $U\subseteq(X\times X)\setminus D$. Let $\mathcal{B}$ be a topologi basis in $(X,\tau)$, $B\in\mathcal{B}$, then from definition of [[Product topology]] we know that $B_{i}\times B_{j}\in\tau'$, where $\tau'$ is a product topology on $X\times X$, is a basic open subsets. Thus $B_{1}\times B_{2}\subseteq U$. If intersection $B_{1}\cap B_{2}$ was not empty, a point $(a,a)$ will lie in $D$, which contradicts to way the neighborhood $B_{1}\times B_{2}$ was chosen.
>
>Therefore we obtained that for an arbitrary point $(x,y)\in(X\times X)\setminus D$ there exists an open neighborhood $B_{1}\times B_{2}$, such that $B_{1}\cap B_{2}=\emptyset$, that is $(X,\tau)$ is Hausdorff.

>[!example]+ 
>
***
#### Keywords
- [[Topological space]],
- [[Hausdorff space]],
- [[Diagonal of topological product space]],
- [[Product topology]],
- [[Neighborhood in topological space]],
- [[Set]],
- [[Topology basis]],
- [[Open and closed subsets]]
#### Possibly related
- 
***
#### Sources: