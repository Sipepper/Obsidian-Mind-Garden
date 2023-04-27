# Properties of balanced and convex neighbourhoods of zeros in topological vector spaces
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>In a topological vector space $U$ we have:
>1. every neighbourhood of zero contains a balanced neighbourhood of zero
>2. every convex neighbourhood of zero contains a balanced convex neighbourhood of zero.^[Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.8]

>[!proof]
>1. Suppose $\mathcal{U}$ is a neighbourhood of zero. From the continuity of scalar multiplication, there exist $\mathcal{V}$(neighbourhood of zero) and $\delta>0$, such that $\alpha\mathcal{V}\subset\mathcal{U}$ whenever $|\alpha|<\delta$. Define $\mathcal{W}=\bigcup_{|\alpha|<\delta}\alpha\mathcal{V}$; thus $\mathcal{W}\subset\mathcal{U}$ is a balanced neighbourhood of zero.
>2. Suppose $\mathcal{U}$ is a convex neighbourhood of zero in $U$. Define
>   $$A=\left\{\bigcap\alpha\mathcal{U}:\alpha\in\mathbb{C},|\alpha|=1 \right\}$$
>   As $0\cdot\theta=\theta$ (where $\theta\in U$ denotes the zero vector) from the continuity of scalar multiplication there exists $\delta>0$ and there is a neighbourhood of zero $\mathcal{V}$ such that if $|\beta|<\delta$, then $\beta\mathcal{V}\subset\mathcal{U}$. Define $\mathcal{W}$ as the union of all such $\beta\mathcal{V}$. Thus $\mathcal{W}$ is balanced and $\alpha^{-1}\mathcal{W}=\mathcal{W}$ as $|\alpha|=1$, so that $\mathcal{W}=\alpha\mathcal{W}\subset\alpha\mathcal{U}$, and hence $\mathcal{W}\subset A$, which implies that the interior $A^{\circ}$ is a neighbourhood of zero. Also $A^{\circ}\subset\mathcal{U}$. Since $A$ is an intersection of convex sets, it is convex and so is $A^{\circ}$. Now we will show that $A^{\circ}$ is balanced and complete the proof. For this, it suffices to prove that $A$ is balanced. Choose $r$ and $\beta$ such that $0\le r\le1$ and $|\beta|=1$. Then
>   $$r\beta A=\bigcap_{|\alpha|=1}r\beta\alpha\mathcal{U}=\bigcap_{|\alpha|=1}r\alpha\mathcal{U}$$
>   Since $\alpha\mathcal{U}$ is a convex set that contains zero, we obtain that $r\alpha\mathcal{U}\subset\alpha\mathcal{U}$, so that $r\beta A\subset A$, which completes the proof.

***
#### Keywords
- [[Topological vector space]],
- [[Neighborhood in topological space]],
- [[Balanced subsets of topological vector spaces]],
- [[Convex set]],
- [[Interior, Exterior and boundary of a set in topological space]],
#### Possibly related
- 
***
#### Sources: