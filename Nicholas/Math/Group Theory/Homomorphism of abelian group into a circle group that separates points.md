---
Last time checked: 2024-02-27
Complete: false
aliases:
---
# Homomorphism of abelian group into a circle group that separates points
***
###### tags: #Group_theory
***
>[!dsn]+ Proposition
>If $G$ is an abelian group, then for any $g$ and $h$ in $G$, with $g\ne h$, there exists a homomorphism $\phi:G\to\mathbb{T}$ such that $\phi(g)\ne\phi(h)$; that is, $\phi$ separates points of $G$.^[[[Sidney A. Morris - Topology without tears.pdf#page=531|Sidney A. Morris - "Topology without tears" p.531]]]

>[!proof]+
>It suffices to show that for each $g\ne e$ in $G$, there exists a homomorphism $\phi:G\to\mathbb{T}$ such that $\phi(g)\ne e$.
>
>Case $(i)$. Assume $g^{n}=e$, and $g^{k}\ne e$ for $0<k<n$. Let $H=\{g^{m}:m\in\mathbb{Z}\}$. Define $\phi:H\to\mathbb{T}$ by $\phi(g)=$ an $n^{th}$ root of unity $=r$, say, $(r\ne e)$, and $\phi(g^{m})=r^{m}$, for each $m$. Now extend $\phi$ to $G$ by [[extension of a homomorphism of a subgroup of abelian group to divisible abelian group]].
>
>Case $(ii)$. Assume $g^{n}\ne e$, for all $n>0$. Define $\phi(g)=z$, for any $z\ne e$ in $\mathbb{T}$. Extend $\phi$ to $H$ and then, by [[extension of a homomorphism of a subgroup of abelian group to divisible abelian group]], to $G$.

>[!example]+ 
>
***
#### Keywords
- [[Abelian group]],
- [[Homomorphism]],
- [[Circle group]],
- [[Order of element in group]],
- [[Set of integers]],
- [[Roots of unity]]
#### Possibly related
- [[Cyclic group]],
***
#### Sources: