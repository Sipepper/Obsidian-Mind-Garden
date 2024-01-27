---
Last time checked: 2023-10-20
Complete: false
aliases:
  - tangent map
  - push-forward
---
# Differential
***
###### tags: #Topology/Differential 
***
>[!dsn]+ Definition
>Let $M$ and $N$ be smooth manifolds with or without boundary and $F:M\to N$ is a smooth map, for each $p\in M$ a map defined as
>$$dF_{p}:T_{p}M\to T_{F(p)}N$$
>$$dF_{p}(v)(f)=v(f\circ F)$$
>is called the *differential of $F$ at $p$*.^[[[John M. Lee - Introduction to smooth manifolds.pdf#page=73 |John M. Lee - "Introduction to smooth manifolds" p.55 ]]]
>![[Pasted image 20231020225218.png]]

>The operator $dF_{p}(v):C^{\infty}(N)\to\mathbb{R}$ is linear because $v$ is, and is a derivation at $F(p)$ because for any $f,g\in C^{\infty}(N)$ we have
>$$\begin{align}dF_{p}(v)(fg)&=v\left((fg)\circ F \right)=v\left((f\circ F)(g\circ F) \right)\\ &=f\circ F(p)v(g\circ F)+g\circ F(p)v(f\circ F)\\ &=f(F(p))dF_{p}(v)(g)+g(F(p))dF_{p}(v)(f) \end{align}$$

>Let $M$, $N$, and $P$ be smooth manifolds with or without boundary, let $F:M\to N$ and $G:N\to P$ be smooth maps, and let $p\in M$ then
>1. $dF_{p}:T_{p}M\to T_{F(p)}N$ is linear.
>2. $d(G\circ F)_{p}=dG_{F(p)}\circ dF_{p}:T_{p}M\to T_{G\circ F(p)}P$.
>3. $d(\operatorname{Id}_{M})_{p}=\operatorname{Id}_{T_{p}M}:T_{p}M\to T_{p}M$.
>4. If $F$ is a diffeomorphism, then $dF_{p}:T_{p}M\to T_{F(p)}N$ is an isomorphism, and $(dF_{p})^{-1}=d\left(F^{-1}\right)_{F(p)}$
>
>>[!proof]+
>>


>[!example]+ 
>
***
#### Keywords
- [[Smooth manifold]],
- [[Boundary of topological manifold]],
- [[Smooth maps between manifolds]],
- [[Tangent vector]],
- [[Operator]],
- [[Linear map]],
- [[Smooth function]],
- [[Real line]],
- [[Derivation]],
- [[Diffeomorphism]],
- [[Inverse function]],
- [[Isomorphism]]
#### Possibly related
- 
***
#### Sources: