---
Last time checked: 2024-02-27
Complete: false
aliases:
---
# Abelian topological group is isomorphic to a direct product of open divisible subgroup and its quotient
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Theorem
>Let $H$ be an open divisible subgroup of an abelian topological group $G$. Then $G$ is topologically isomorphic to $H\times G/H$. And $G/H$ is a discrete topological group.^[[[Sidney A. Morris - Topology without tears.pdf#page=531|Sidney A. Morris - "Topology without tears" p.531]]]

>[!proof]+
>We can consider the identity mapping(which is an isomorphism and thus a homomorphism) $\text{id}_{H}:H\to H$ which can be extended by [[extension of a homomorphism of a subgroup of abelian group to divisible abelian group]] to a homomorphism $\phi:G\to H$ such that $\phi(H)=H$.
>Thus we can form a short exact sequence
>$$1\rightarrow K\rightarrow G\rightarrow H\rightarrow1$$
>with $K=\ker\phi$. We have a section map $id_{H}:H\to G$. Thus
>$$G\cong K\rtimes H$$
>Because $G$ is abelian, $H$ acts trivially on $K$ by conjugations. That is
>$$G\cong K\times H$$
>As projection map $p:K\times H\to K$ is a homomorphism, then it's image, namely $K$, is isomorphic to $G/H$. That is
>$$G\cong G/H\times H$$
>
>By [[quotient topological group is discrete if quotient is open]] $G/H$ is discrete.

>[!example]+ 
>
***
#### Keywords
- [[Open and closed subsets]],
- [[Divisible abelian group]],
- [[Topological group]],
- [[Homeomorphism]],
- [[Isomorphism]],
- [[Direct product of groups]],
- [[Quotient topology on a quotient group]],
- [[Discrete topology]],
- [[Function(mapping)]],
- [[Homomorphism]],
- [[Short exact sequence of groups]],
- [[Kernel and image of a mapping]],
- [[Semidirect product of groups]],
- [[Group acting on a set]],
- [[Conjugation in groups]],
- [[Projection map in product spaces]]
#### Possibly related
- 
***
#### Sources: