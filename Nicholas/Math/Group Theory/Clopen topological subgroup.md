# Clopen topological subgroup
***
###### tags: #Group_theory/Topological 
***
>[!dsn] Direct strict note
>Let $H$ be a subgroup of a topological group $G$. If $H$ contains a neighbourhood of the neutral element in $G$, then $H$ is both open and closed in $G$.^[Alain M. Robert - "A course in p-adic analysis" p.19]

>[!proof]
>Let $V$ be a neighbourhood of the neutral element of $G$ contained in $H$. Then $\forall h\in H$, $hV$ is a neighbourhood of $h$ in $G$ contained in $H$. This proves that $H$ is a neighbourhood of all its elements, and hence is open in $G$. 
>
>Consider now the cosets $gH$ of $H$ in $G$. Since [[Topological group translations are homeomorphisms]] of $G$, these cosets are open in $G$. Any union of such cosets is also open. But $H$ is the complement of the union of all cosets $gH\ne H$. Hence $H$ is closed.

>[!example] 
>The subgroups $p^{n}\mathbb{Z}_{p}$, $(n\ge0)$ are open and closed subgroups of the additive group $\mathbb{Z}_{p}$.
>>[!proof]
>>

>[!example]
>The subgroups $1+p^{n}\mathbb{Z}_{p}$, $(n\ge 1)$ are open and closed subgroups of the multiplicative group $1+p\mathbb{Z}_{p}$.
>>[!proof]
>>

***
#### Keywords
- [[Topological group]],
- [[Neighborhood in topological space]],
- [[Open and closed subsets]],
- [[Group coset]],
- [[Homeomorphism]],
- [[Group of invertible elements in a ring of p-adic integers]],
- [[Ring of p-adic integers]],
#### Possibly related
- 
***
#### Sources: