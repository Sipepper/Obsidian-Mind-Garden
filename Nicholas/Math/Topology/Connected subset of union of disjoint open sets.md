# Connected subset of union of disjoint open sets
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Let $(X,\tau)$ be a topological space. Let $A$ be a connected subset of $T$. Let $U,V$ be disjoint open sets and $A\subseteq U\cup V$, then either $A\subseteq U$ or $A\subseteq V$.^[https://proofwiki.org/wiki/Connected_Subset_of_Union_of_Disjoint_Open_Sets]

>[!proof]+
>Let $U'=A\cap U$ and $V'=A\cap V$. By definition $U'$ and $V'$ are open sets in the subspace $(A,\tau_{A})$. Then
>$$\begin{align}U'\cap V'&=(A\cap U)\cap(B\cap V)\\ &=A\cap U\cap V\\ &=A\cap\emptyset\\ &=\emptyset  \end{align}$$
>Hence $U'$ and $V'$ are separated sets.
>Now
>$$\begin{align}A&=A\cap(U\cup V)\\ &=(A\cap U)\cup(A\cap V)\\ &=U'\cup V' \end{align}$$
>Since $A$ is connected then one of $U'$ or $V'$ is empty. Thus
>$$\begin{align}A&=U'\cup V'\\ &=U'\cup\emptyset\\ &=U'\\ &=A\cap U \end{align}$$
>from which $A\subseteq U$. 

>[!example]+ 
>
***
#### Keywords
- [[Topological space]],
- [[Connected topological space]],
- [[Open and closed subsets]],
- [[Set]],
- [[Subspace topology]]
#### Possibly related
- 
***
#### Sources: