---
Last time checked: 2024-02-01
Complete: false
aliases:
---
# Orthogonal complement of a sphere in l2
***
###### tags: #Analysis/Functional 
***
>[!dsn]+ Proposition
>Let $S$ be a sphere of radius $1$ in $l^{2}$ space, i.e. $S=\{s\in l^{2}:\|s\|_{2}=1\}$. Then the $S^{\perp}=\theta$, i.e. only zero vector is orthogonal to $S$.

>[!proof]+
>Let's recall form of the scalar product and norm in $l^{2}$
>$$\langle x,y\rangle_{2}=\sum\limits_{i=1}^{\infty}x_{i}y_{i}$$
>By the definition of orthogonal complement we have
>$$S^{\perp}=\set{u\in l^{2}:\langle u,s\rangle=0}$$
>Let's take a subset $S'$ of $S$ with the following property
>$$S\subset\textbf{span}\{S'\}$$
>i.e. every element of $S$ can be represented as a linear combination of elements from $S'$.
>If we prove that $S'^{\perp}=\theta$ this will imply that $S^{\perp}=\theta$.
>
>As such set we can take $\{e_{n}\}$, i.e. vectors with $1$ on a $n$-th position and zeros on every other position. 
>
>Therefore, the set $S'^{\perp}$ will have the form
>$$\bigcap_{i=1}^{\infty}\{e_{i}\}^\perp$$
>where $\{e_{i}\}^{\perp}=\set{u\in l^{2}:\langle u,e_{i}\rangle=0}$ or in other words
>$$\sum\limits_{j=1}^{\infty}u_{j}e_{ij}=0\cdot e_{1}+\dots+0\cdot u_{i-1}+1\cdot u_{i}+0\cdot u_{i+1}+\cdot=u_{i}$$
>i.e the $\{e_{i}\}^{\perp}$ is a set of vectors with $0$ at the $i$-th place.
>
>Thus the intersection of all such sets is a zero vector. And finally if $S'^{\perp}=\theta$, then $S^{\perp}$ is also only consists of a zero vector.

***
#### Keywords
- [[Sphere]],
- [[Sequence spaces]],
- [[Open ball in metric space]],
- [[Open and closed subsets]],
- [[Orthogonal complement]],
- [[Vector space]],
- [[Inner product]],
- [[Linear span]],
- [[Set]],
- [[Orthonormal basis]],
#### Possibly related
- 
***
#### Sources:
