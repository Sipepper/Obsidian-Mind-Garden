---
Last time checked: 2024-02-19
Complete: false
aliases:
---
# Normal subgroup
***
###### tags: #Group_Theory 
***
>[!dsn]+ Definition
>Let $H$ be a subgroup of $G$. If left and right cosets of $H$ are equal; i.e. $Hx=xH$,$\forall x\in G$. Then such subgroup is said to be *normal* in $G$, denoted as $H\trianglelefteq G$. 

>Let $K$ be another, not necessarily normal subgroup of $G$ such that $G=\langle H,K\rangle=HK$. Then for every $g\in G$
>$$g=hk\quad h\in H,k\in K$$
>such representation is *unique*. That is we have bijection between $H\times K$ and $G$.
>>[!proof]+
>>If $G=\langle H,K\rangle$, then every element of $G$ has the following form
>>$$g=h_{1}k_{1}h_{2}k_{2}\dots h_{n}k_{n}\qquad h_{i}\in H,k_{i}\in K$$
>>then, as $H$ is normal, $h'_{2}=k_{1}h_{2}k_{1}^{-1}\in H$, thus
>>$$\begin{align}g&=h_{1}h'_{2}h_{3}k_{3}\dots h_{n}k_{n}\\ &=h''_{2}k_{3}h_{4}k_{4}\dots h_{n}k_{n} \end{align}$$
>>that is we obtained a word with $2$-less letters, continuing in similar manner element $g$ will have form $h'k'$.

>[!example]+
>


#### Relation to conjugacy classes
>[!dsn]+ Proposition
>Group is normal if an only if it can be partitioned to several conjugacy classes. 

>[!proof]+
>
#### Relation to inner automorphisms
>[!dsn]+ Proposition
>Normal subgroup can be defined as a subgroup invariant to all inner automorphisms.

>[!proof]+
>
***
#### Keywords
- [[Group coset]],
- [[Group]],
- [[Group generated by a set]],
- [[Function(mapping)]],
- [[Direct product of groups]],
- [[Group automorphism]],
- [[Partition of a set]]
- [[Conjugacy class]],
#### Possibly related
- 
***
#### Sources: