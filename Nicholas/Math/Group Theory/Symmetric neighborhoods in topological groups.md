# Symmetric neighborhoods in topological groups
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Direct strict note
>Let $(G,\tau)$ be any topological group and $e$ its identity element. If $U$ is any neighborhood of $e$, then there exists and open neighbourhood $V$ of $e$ such that
>- $V=V^{-1}$ (that is, $V$ is a *symmetric neighbourhood of the identity*)
>- $V^{2}\subseteq U$.
>
>Here $V^{-1}=\set{v^{-1}:v\in V}$ and $V^{2}=\set{v_{1}v_{2}:v_{1},v_{2}\in V}$, *not* the set $\set{v^{2}:v\in V}$.^[Sidney A. Morris - "Topology without tears" p.515]

>[!proof]+
>Take the continuous function $m:G\times G\to G$ where $(x,y)\mapsto xy$ (group multiplication). Then $m^{-1}(U)$ is open and maps to $U$. We can take a neighborhood of $e$, let's say $V$, such that $V\times V\subseteq m^{-1}(U)$ (since $m^{-1}(U)$ is open in the product topology). By replacing $V$ with $V\cap V^{-1}$, we can assume that $V$ is symmetric. Therefore $m(V,V)=VV\subseteq U$ and $V$ is symmetric.^[https://math.stackexchange.com/questions/467832/every-neighborhood-of-identity-in-a-topological-group-contains-the-product-of-a]

>[!example]+ 
>
***
#### Keywords
- [[Topological group]],
- [[Neighborhood in topological space]],
- [[Product topology]],
- [[Continuous mapping]],
- [[Preimage]],
#### Possibly related
- 
***
#### Sources: