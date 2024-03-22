---
Last time checked: 2024-02-27
Complete: false
aliases:
---
# Infinite abelian group admits a non-discrete Hausdorff group topology
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Theorem
>If $G$ is any infinite abelian group, then $G$ admits a non-discrete Hausdorff group topology.^[[[Sidney A. Morris - Topology without tears.pdf#page=531|Sidney A. Morris - "Topology without tears" p.531]]]

>[!proof]+
>Let $\{\phi_{i}:i\in\Lambda\}$ be the family of distinct homomorphisms of $G$ into $\mathbb{T}$. Put $H=\prod\limits_{i\in\Lambda}T_{i}$, where each $T_{i}=\mathbb{T}$. Define a map $f:G\to H=\prod\limits_{i\in\Lambda}T_{i}$ by putting $f(g)=\prod\limits_{i\in\Lambda}\phi_{i}(g)$. Since each $\phi_{i}$ is a homomorphism, $f$ is also a homomorphism. By [[homomorphism of abelian group into a circle group that separates points]], $f$ is also injective; that is, $G$ is isomorphic to the subgroup $f(G)$ of $H$.
>As $H$ is a Hausdorff topological group, $f(G)$, with the topology induced from $H$, is also a Hausdorff topological group. It only remains to show that $f(G)$ is not discrete.
>Suppose $f(G)$ is discrete. Then, by [[locally compact subgroup of the Hausdorff topological group is closed]], $f(G)$ would be a closed subgroup of $H$. But by [[Tychonoff's theorem]], $H$ is compact and so $f(G)$ would be compact; that is, $f(G)$ would be an infinite discrete compact space which is *impossible*. So we have a contradiction, and thus $f(G)$ is not discrete.

>[!example]+ 
>
***
#### Keywords
- [[Cardinality of a set]],
- [[Abelian group]],
- [[Discrete topology]],
- [[Hausdorff space]],
- [[Topological group]],
- [[Homomorphism]],
- [[Circle group]],
- [[Product topology]],
- [[Direct product of groups]],
- [[Function(mapping)]],
- [[Isomorphism]],
- [[Subspace topology]],
- [[Open and closed subsets]],
- [[Kernel and image of a mapping]]
#### Possibly related
- 
***
#### Sources: