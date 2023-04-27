# Mutliplication of different subsets of topological groups
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Direct strict note
>Let $(G,\tau)$ be a topological group, $A$ and $B$ subsets of $G$ and $g$ any element of $G$. Then
>1. If $A$ is open, then $gA$ is open.
>2. If $A$ is open and $B$ is arbitrary, then $AB$ is open.
>3. If $A$ and $B$ are compact, then $AB$ is compact.
>4. If $A$ is compact and $B$ is closed, then $AB$ is closed.
>5. If $A$ and $B$ are closed, then $AB$ need not be closed.^[Sidney A. Morris - "Topology without tears" p.517]

>[!proof]+
>1. Because multiplication by an element of topological group is a homeomorphism by [[Topological group translations are homeomorphisms]], if $A$ is open then $gA$ will also be open because homeomorphisms are open maps.
>2. Let $A$ be open set, and $B$ arbitrary. Then $AB$ can be viewed as union $\bigcup\limits_{b\in B}Ab$, then from proven above we know that $Ab$ is an open set thus as union of arbitrary number of open sets is open, $AB=\bigcup\limits_{b\in B}Ab$ is an open set.
>3. Let $A$ and $B$ be a compact subsets of topological group $G$. Let $\bigcup A_{i}$ and $\bigcup B_{j}$ be an open coverings of $A$ and $B$ respectively, with finite open subcoverings $A_{i_{1}}\cup A_{i_{2}}\cup\dots\cup A_{i_{n}}$ and $B_{j_{1}}\cup B_{j_{2}}\cup\dots\cup B_{j_{p}}$. Then 
>   $$AB=m(A,B)\subseteq m\left(\bigcup_{k=1}^{n}A_{i_{k}} ,\bigcup_{l=1}^{p}B_{j_{l}}\right)=\bigcup_{k=1}^{n}\bigcup_{l=1}^{p}m(A_{i_{k}},B_{j_{l}})$$
>   Therefore, because multiplication of open set and arbitrary set is open $\bigcup_{k=1}^{n}\bigcup_{l=1}^{p}m(A_{i_{k}},B_{j_{l}})$ is an open finite covering of $AB$. Because coverings $A_{i}$ and $B_{j}$ were chosen arbitrarily, then $AB$ is compact set indeed.
>4. Let $x\in G\setminus(AB)$. For every $a\in A$ we have that $a^{-1}x\notin B$. Consider the map $m':G\times G\to G$ defined by $m'(g,h)=g^{-1}h$. Then $m'$ is continuous as composition of multiplication and inversion. Since $B$ is closed, $G\setminus B$ is open, and therefore $m'^{-1}(G\setminus B)$ is open. Since for every $a\in A$, we have $m'(a,x)=a^{-1}x\notin B$, we have $(a,x)\in m'^{-1}(G\setminus B)$ and since the latter is open, there exists open subsets of $G$ with $a\in U_{a}$, $x\in V_{a}$ such that $m'(U_{a}\times V_{a})\subseteq G\setminus B$.
>   ${}$
>   Consider the following open cover of $A$: $A\subseteq\bigcup_{a\in A}U_{a}$. Since $A$ is compact, this cover admits a finite sub-cover $A\subseteq\bigcup_{i=1}^{N}U_{a_{i}}$. Define $V=\bigcap_{i=1}^{N}V_{a_{i}}$. Then $V$ is open with $x\in V$. We claim that $V\subseteq G\setminus(AB)$: otherwise there exists $a\in A$, $b\in B$ with $ab\in V$. Since $a\in A$, we have that $a\in U_{a_{i}}$ for some $i$. Then $ab\in V\subseteq V_{a_{i}}$ and $m(a,ab)=a^{-1}(ab)=b\in B$, which is a contradiction since $U_{a_{i}}\times V_{a_{i}}\subseteq m^{-1}(G\setminus B)$.
>   
>   5. Let $G=\mathbb{R}^{2}$ with pointwise addition. Then let $A=\left\{\left(t,\frac{1}{t} \right):t>0\right\}$ and $B=\left\{\left(t,-\frac{1}{t} \right):t>0\right\}$. So because set is closed if and only if it contains all it's limit points, and sequence $(1/n,0)\in A+B$, but $(0,0)\notin A+B$.
***
#### Keywords
- [[Topological group]],
- [[Set]],
- [[Open and closed subsets]],
- [[Compact set]],
- [[Homeomorphism]],
- [[Open and closed mappings]],
- [[Covering of a set]],
- [[Continuous mapping]],
- [[Closed set contains all it's limit points]],
- [[Sequence]]
#### Possibly related
- 
***
#### Sources: