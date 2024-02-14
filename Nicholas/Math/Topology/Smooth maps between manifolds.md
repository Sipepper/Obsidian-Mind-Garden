---
Last time checked: 2023-10-19
Complete: false
aliases:
---
# Smooth maps between manifolds
***
###### tags: #Topology/Differential 
***
>[!dsn]+ Definition
>A map $f:M\to N$ between smooth manifolds $(M,\Phi)$ and $(N,\Psi)$ is called *smooth* if for every chart $\phi\in\Phi$ and any chart $\psi\in\Psi$, the composition $\phi\circ f\circ\phi^{-1}$ is smooth.^[[[Stefan Friedl - Algebraic topology.pdf#page=279|Stefan Friedl - "Algebraic topology" p.279 ]]]

>Given two smooth manifolds $M$ and $N$ the set $C^{\infty}(M,N)$ denotes the set of all smooth maps from $M$ to $N$.

>[!example]+ 
>

#### Properties 
>[!dsn]+ Lemma
>Let $f:M\to N$ be  amap between two smooth manifolds.
>1. If ther eexists an open cover $\{U_{i}\}_{i\in\Lambda}$ of $M$ such that each restriction $f|_{U_{i}}:U_{i}\to N$ is smooth, then $f$ itself is smooth.
>2. If $f:M\to N$ is smooth it is also continuous.
>3. If $f:M\to N$ is a bijection (e.g. if it is a homeomorphism) and if it is a local diffeomorphism, then it is in fact a diffeomorphism.

>[!proof]+
>

***
#### Keywords
- [[Function(mapping)]],
- [[Smooth manifold]],
- [[n-dimensional chart]],
- [[Covering of a set]],
- [[Open and closed subsets]],
- [[Restriction and extension of a mapping]],
- [[Homeomorphism]],
- [[Diffeomorphism]],
- [[Local diffeomorphism]]
#### Possibly related
- 
***
#### Sources: