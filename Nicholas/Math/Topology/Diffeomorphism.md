---
Last time checked: 2023-10-19
Complete: false
aliases:
---
# Diffeomorphism
***
###### tags: #Topology/Differential 
***
>[!dsn]+ Definition
>We say that a map $f:M\to N$ between smooth manifolds is a *diffeomorphism* if $f$ is smooth and if $f$ is a bijection and $f^{-1}:N\to M$ is also smooth.^[[[Algebraic topology - Stefan Friedl.pdf#page=278 |Stefan Friedl - "Algebraic topology" p.278 ]]]

>If such a diffeomorphism exists, then we say that $M$ and $N$ are *diffeomorphic*.

>[!example]+ 
>Consider the maps $F:\mathbb{B}^{n}\to\mathbb{R}^{n}$ and $G:\mathbb{R}^{n}\to\mathbb{B}^{n}$ given by
>$$F(x)=\frac{x}{\sqrt{1-|x|^{2}}}\quad G(y)=\frac{y}{\sqrt{1+|y|^{2}}}$$
>These maps are smooth, and inverses of each other. Thus they are both diffeomorphisms, and therefore $\mathbb{B}^{n}$ is diffeomorphic to $\mathbb{R}^{n}$.^[[[John M. Lee - Introduction to smooth manifolds.pdf#page=56 |John M. Lee - "Introduction to smooth manifolds" p.38 ]]]
>>[!proof]+
>>

#### Properties
>[!dsn]+ Proposition
>1. Every composition of diffeomorphisms is a diffeomorphism.
>2. Every finite product of diffeomorphisms between smooth manifolds is a diffeomorphism.
>3. Every diffeomorphism is a homeomorphism and an open map.
>4. The restriction of a diffeomorphism to an open submanifold with or without boundary is a diffeomorphism onto its image.
>5. "Diffeomorphic" is an equivalence relation on the class of all smooth manifolds with or without boundary.^[[[John M. Lee - Introduction to smooth manifolds.pdf#page=57 |John M. Lee - "Introduction to smooth manifolds" p.39 ]]]

>[!proof]+
>
***
#### Keywords
- [[Function(mapping)]],
- [[Smooth manifold]],
- [[Smooth maps between manifolds]],
- [[Inverse function]],
- [[Open ball in metric space]],
- [[Euclidean space]],
- [[Homeomorphism]],
- [[Open and closed mappings]],
- [[Submanifold]],
- [[Boundary of topological manifold]],
- [[Equivalence relation]]
#### Possibly related
- [[Product topology]],
***
#### Sources: