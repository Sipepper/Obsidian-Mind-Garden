---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Union of connected spaces is connected if they have nonempty intersection
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>Let $(X,\tau)$ be a topological space. Let $\{B_{i}\}_{i\in\Lambda}$ be a family of connected sets of $X$. Let $\exists x\in\bigcap\limits_{i\in\Lambda}B_{i}$ is a connected set of $T$.^[https://proofwiki.org/wiki/Union_of_Connected_Sets_with_Common_Point_is_Connected]

>[!proof]+
>Let $B=\bigcup\limits_{i\in\Lambda}B_{i}$. $B$ is connected if and only if $(B,\tau_{B})$ is a connected space. From definition of [[Connected topological space]] $(B,\tau_{B})$ is connected if and only if the only clopen sets in $(B,\tau_{B})$ are $B$ and $\emptyset$.
>Let $U$ be any clopen set of the subspace of $(B,\tau_{B})$.
>Let $V=B\setminus V$. As complement of clopen set is clopen, $V$ is also clopen. Hence $U,V$ are disjoint clopen sets such that $B=U\cup V$.
>Without loss of generality assume $x\in U$. Then
>$$\forall i\in\Lambda:B_{i}\subseteq B=U\cup V$$
>From [[Connected subset of union of disjoint open sets]]
>$$\forall i\in\Lambda:B_{i}\subseteq U$$
>As union is smallest superset
>$$B\subseteq U$$
>Since $U\subseteq B$ then $U=B$, therefore
>$$V=B\setminus U=B\setminus B=\emptyset$$
>Hence the only clopen sets in $(B,\tau_{B})$ are $B$ and $\emptyset$.

>[!example]+ 
>
***
#### Keywords
- [[Topological space]],
- [[Cardinality of a set]],
- [[Connected topological space]],
- [[Open and closed subsets]],
- [[Subspace topology]]
#### Possibly related
- 
***
#### Sources: