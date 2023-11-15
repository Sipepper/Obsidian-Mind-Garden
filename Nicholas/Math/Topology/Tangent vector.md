---
Last time checked: 2023-10-19
Complete: false
aliases:
---
# Tangent vector
***
###### tags: #Geometry/Differential #Topology/Differential 
***
#### Differentiable curves
>[!dsn]+ Direct strict note
>Vector $\alpha'(t)=(x'(t),y'(t),z'(t))\in\mathbb{R}^{3}$ is called a *tangent vector*(or *vector of speed*) of curve $\alpha$ in point $t$.^[Manfredo P. do Carmo - "Differential Geometry of Curves and Surfaces" с.2]

>Image $\alpha(I)\subset\mathbb{R}^{3}$ is called a *trace* of a curve $\alpha(t)$. Trace of a curve and curve is a different objects.

>[!example]+
> Let $\alpha(t)=(t^{2},t,t^{3})$ be a parametrized differentiable curve, then its tangent vector will have form $$\alpha'(t)=(2t,1,3t^{2})$$ in point $t$.

#### Geometric tangent vectors
>[!dsn]+ Definition
>Given a point $a\in\mathbb{R}$, a *geometric tangent space to $\mathbb{R}^{n}$ at $a$* is a set
>$$\{a\}\times\mathbb{R}^{n}=\{(a,v):v\in\mathbb{R}^{n}\}$$
>denoted as $\mathbb{R}_{a}^{n}$. An element of $\mathbb{R}_{a}^{n}$ is a *geometric tangent vector* in $\mathbb{R}^{n}$.^[[[John M. Lee - Introduction to smooth manifolds.pdf#page=70 |John M. Lee - "Introduction to smooth manifolds" p.52 ]]]

>There is a natural isomorphism between $\mathbb{R}^{n}$ and $\mathbb{R}_{a}^{n}$.

>Let $a\in\mathbb{R}^{n}$.
>1. For each geometric tangent vector $v_{a}=\mathbb{R}_{a}^{n}$, the map $D_{v}|_{a}:C^{\infty}(\mathbb{R}^{n})\to\mathbb{R}$ defined as
>   $$D_{v}|_{a}f=\frac{d}{dt}\bigg|_{t=0}f(a+tv)$$
>   is a derivation at $a$.
>2. The map $v_{a}\mapsto D_{v}|_{a}$ is an isomorphism from $\mathbb{R}_{a}^{n}$ onto $T_{a}\mathbb{R}^{n}$.
>
>>[!proof]+
>>.^[[[John M. Lee - Introduction to smooth manifolds.pdf#page=71 |John M. Lee - "Introduction to smooth manifolds" p.53 ]]]

#### Tangent vectors on manifolds
>[!dsn]+ Definition
>Let $M$ be a smooth manifold and let $p$ be a point of $M$. The set of all derivations of $C^{\infty}$ at $p$, denoted by $T_{p}M$ is a vector space called the *tangent space to $M$ at $p$*. An element of $T_{p}M$ is called a *tangent vector at $p$*.^[[[John M. Lee - Introduction to smooth manifolds.pdf#page=72 |John M. Lee - "Introduction to smooth manifolds" p.54 ]]]

>Suppose $M$ is a smooth manifold with or without boundary, $p\in M$, $v\in T_{p}M$, and $f,g\in C^{\infty}(M)$.
>1. If $f$ is a constant function, then $vf=0$.
>2. If $f(p)=g(p)=0$, then $v(fg)=0$.
>
>>[!proof]+
>>exercise
***
#### Keywords
- [[Vector]],
- [[Parametrized differentiable curve in euclidean space]],
- [[Function derivative]],
- [[Set]],
- [[Cartesian product of sets]],
- [[Isomorphism]],
- [[Euclidean space]],
- [[Derivation]]
#### Possibly related
- 
***
#### Sources: