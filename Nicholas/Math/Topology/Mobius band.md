---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Mobius band
***
###### tags: #Topology 
***
>[!dsn]+
>Let $X=\mathbb{R}\times[-1,1]$ be a product space and $G=\mathbb{Z}$ be a group acting on $X$. The map
>$$\begin{align}\mathbb{Z}\times(\mathbb{R}\times[-1,1])&\to\mathbb{R}\times[-1,1]\\(n,(x,y))&\mapsto(x+n,(-1)^{n}\cdot y)\end{align}$$
>defines an action that is free and continuous. 
>![[Pasted image 20230811154036.png]]
>We refer to the quotient(space of orbits) $X/\mathbb{Z}$ as the *Mobius band*.^[Stefan Friedl - "Algebraic topology" p.188]

>Mobius band is a compact space.^[Stefan Friedl - "Algebraic topology" p.188]
>>[!proof]+
>>

>Mobius band can be embedden in $\mathbb{R}^{3}$ as follows: Given $\phi,\psi\in\mathbb{R}$ and $r\in[-1,1]$ we set
>$$A(\phi):=\begin{pmatrix}\cos\phi&-\sin\phi&0\\\sin\phi&\cos\phi&0\\0&0&1 \end{pmatrix}\quad\text{and}\quad v(r,\psi):=\begin{pmatrix}2+r\sin\phi\\0\\ r\cos\psi \end{pmatrix}$$
>Consider the map
>$$\begin{align}\Phi:(\mathbb{R}\times[-1,1])/\mathbb{Z}&\to \mathbb{R}^{3}\\ [(\phi,r)]&\mapsto A(2\pi\cdot\phi)\cdot v(r,\pi\phi) \end{align}$$
>such map $\Psi$ is an embedding.^[Stefan Friedl - "Algebraic topology" p.188]
>![[Pasted image 20230811160339.png]]
>>[!proof]+
>>

#### As a quotient space
>[!dsn]+ Direct strict note
>Consider topological space $X=[0,1]\times[0,1]\subset\mathbb{R}^{2}$, introduce the equivalence relation
>$$(0,y)\sim(1,1-y)\quad\forall y\in[0,1]$$
>The quotient space $X/\sim$, obtained from the square $X$ by gluing the edge on the left to the edge on the right but *with a twist*, is homeomorphic to space defined as orbit above(that is homeomorphic a Mobius band).^[Stefan Friedl - "Algebraic topology" p.204]

>[!proof]+
>Consider the map
>$$\begin{align}([0,1]\times[0,1])/\sim&\to(\mathbb{R}\times[-1,1])/\mathbb{Z}\\ [(x,y)]&\mapsto[(x,2y-1)] \end{align}$$
>The left-hand side is compact by [[Quotient space of compact space is compact]] and the right-hand side is Hausdorff by [[Quotient of Hausdorff space by group which acts properly and continuously is also Hausdorff]]

>[!example]+ 
>
***
#### Keywords
- [[Product topology]],
- [[Interval]],
- [[Real line]],
- [[Function(mapping)]],
- [[Free group action]],
- [[Quotient topology]],
- [[Compact set]],
- [[Embedding of topological spaces]],
- [[Topological space]],
- [[Equivalence relation]],
- [[Homeomorphism]],
- [[Hausdorff space]],
- [[Faithful action of a group on a set]]
#### Possibly related
- 
***
#### Sources: