# Closure of certain subgroups in topological groups
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Direct strict note
>Let $H$ be a subgroup of a topological group $G$. Then
>1. the closure $\overline{H}$ of $H$ is a subgroup of $G$.
>2. if $H$ is a normal subgroup of $G$, then $\overline{H}$ is a normal subgroup of $G$.
>3. if $G$ is Hausdorff and $H$ is abelian, then $\overline{H}$ is abelian.^[Sidney A. Morris - "Topology without tears" p.520]

>[!proof]+
>1. If $H$ is closed, then $\overline{H}=H\le G$. Thus suppose that $H$ is not closed, then let $a\in\overline{H}$. Let $U$ be a neighborhood of $a$, then $n^{-1}(U\cap H)\ne\emptyset$ and $n^{-1}(U\cap H)=n^{-1}(U)\cap n^{-1}(H)=n^{-1}(U)\cap H$. Because $n^{-1}(U)$ is a neighborhood of $a^{-1}$, then every neighborhood of $a^{-1}$ intersects $H$, i.e. $a^{-1}\in\overline{H}$.
>   Next, let $a,b\in\overline{H}$, then let $W$ be a neighborhood of $ab^{-1}$. Now take preimage $m^{-1}(W)=A\times B$, where $A$ and $B$ is a neighborhoods of $a$ and $b^{-1}$ respectively. Because $a,b^{-1}\in\overline{H}$, $A\cap H\ne\emptyset$ and $B\cap H\ne\emptyset$. Then
>   $$ab^{-1}\in m(A\cap H,B\cap H)=m(A,B)\cap m(H,H) =U\cap H$$
>   because $U$ was chosen arbitrarily, then $ab^{-1}\in\overline{H}$
>   
>2. Let $H$ be a normal subgroup of topological group $G$, then $gH=Hg$, $\forall g\in G$. Then because [[Topological group translations are homeomorphisms]] and [[Homeomorphism of closure is a closure of homeomorphism image]] we get that $g\overline{H}=\overline{gH}=\overline{Hg}=\overline{H}g$. Therefore because $\overline{H}$ is a subgroup of $G$, $\overline{H}$ be a normal subgroup of $G$.
>3. Let $G$ be a topological group and $H$ be it's abelian subgroup. Then consider the following mapping
>   $$k:G\times G\to G\qquad k(a,b)=aba^{-1}b^{-1}$$
>   $k$ is continuous as composition of continuous mappings (multiplication and inversion). Then $k(H,H)=e$ because $H$ is abelian subgroup. Now take the preimage of neutral element $e$, because $\set{e}$ is a closed set (by Hausdorffness of $G$), the preimage $k^{-1}(e)$ is also closed thus
>   $$H\subseteq\overline{H}\subseteq k^{-1}(e)$$
>   from which we obtain that
>   $$k(\overline{H})=e$$
>   Therefore $\overline{H}$ is an abelian group.

>Let $G$ be a topological group. Then
>1. $\overline{\set{e}}$ is a closed normal subgroup of $G$; indeed, it is the smallest closed subgroup of $G$;
>2. If $g\in G$, then $\overline{\set{g}}$ is the coset $g\overline{\set{e}}=\overline{\set{e}}g$;
>3. If $G$ is Hausdorff then $\overline{\set{e}}=\set{e}$.
>
>>[!proof]+
>>This follows immediately from proposition above by noting that $\set{e}$ is a normal subgroup of $G$.

>[!example]+ 
>
***
#### Keywords
- [[Group#Subgroup]],
- [[Topological group]],
- [[Closure of a set]],
- [[Normal subgroup]]
- [[Hausdorff space]],
- [[Abelian group]],
- [[Open and closed subsets]],
- [[Neighborhood in topological space]],
- [[Preimage]],
- [[Function(mapping)]],
- [[Group coset]],
#### Possibly related
- 
***
#### Sources:

# Closure of a topological group
***
###### tags: #Group_theory/Topological 
***
>[!dsn] Direct strict note
>Let $G$ be a topological group, $H\le G$, then
>1. Closure $\overline{H}$ of $H$ will also be a subgroup of $G$.
>2. $G$ is a Hausdorff space if and only if it's neutral element is a closed subset($\{e\}$).^[Alain M. Robert - "Course in p-adic analysis" p.19]

>[!proof]
>1. Let $\phi:G\times G\to G$ denotes the continuous mapping $(x,y)\mapsto xy^{-1}$. Because $H$ is a subgroup, we have that $\phi(H\times H)\subset H$ and thus
>   $$\phi(\overline{H}\times\overline{H})=\phi(\overline{H\times H})\subset\overline{\phi(H\times H)}\subset\overline{H}$$
>   Which proves that $\overline{H}$ is a subgroup of $G$.
>
>2. From the [[Hausdorffness by a diagonal]] we know that space $X$ will be Hausdorff precisely when it's diagonal $\Delta_{X}$ is closed in $X\times X$. Also in any Hausdorff space every point is a closed set, therefore
>   $$\begin{align}G-\text{Hausdorff}&\Rightarrow\{e\}-\text{closed}\\ &\rightarrow\Delta_{G}=\phi^{-1}(e)\;\text{closed in}\;G\times G\\ &\Rightarrow G-\text{Hausdorff} \end{align}$$
>   Which completes the proof.
***
#### Keywords
- [[Closure of a set]],
- [[Topological group]],
- [[Open and closed subsets]],
- [[Continuous mapping]],
- [[Diagonal of topological product space]],
#### Possibly related
- 
***
#### Sources: