---
Last time checked: 2024-02-26
Complete: true
aliases:
---
# Orbit in homogeneous space
***
###### tags: #Group_Theory #Geometry  
***
>[!dsn]+ Definition
>Let $(G,X)$ be a homogeneous space. The orbit $O(x)$ of $x\in X$ is defined as
>$$O(x)=\{g(x):g\in G\}$$
>Thus orbits are just equivalence classes under the equivalence relation
>$$x\sim y\Longleftrightarrow \exists g\in G:g(x)=y$$
>.^[[[Marcel Berger - Geometry 1.pdf#page=21 |Marcel Berger - "Geometry 1" p.9]]]

>We can form the *space of orbits* $X/G$, for all $x\in X$,
>$$O(x)\cong G/G_{x}$$
>using proof of [[if group acting on homogeneous space is finite then this space is also finite]].

>[!example]+ 
>For a given $g\in S_{n}$, put $G=\{g^{k}:k\in\mathbb{Z}\}\subset S_{n}$. Then $G$ acts on $X=\{1,\dots,n\}$, and the orbits are called *cycles* of the permutation $g$.


>[!example]+
>Let $E$ be a Euclidean vector space, and put
>$$G=O(E)=\{f\in\text{GL}(E):f\text{ is an isometry}\}$$
>Then there is a natural $O(E)$-action on $X=E$, with orbits consisting of spheres $S_{r}(0)$ centered at the origin (where $r\in\mathbb{R}^{+}$)
>![[Pasted image 20230430225812.png]]

>[!example]+
>Put $G=\mathbb{R}$, $X=S^{3}=\{x\in\mathbb{R}^{4}:\|x\|=1\}\subset\mathbb{R}^{4}$. Identifying $\mathbb{R}^{4}$ with $\mathbb{C}^{2}$, we define an operation $(\mathbb{R},S^{3},\phi)$ by
>$$\phi(t)(z,z')=(e^{it}z,e^{it}z')$$
>The orbits are all circles, like $S^{1}=\mathbb{R}/2\pi\mathbb{Z}$ they all fit together to form the *Hopf fibration*: any two of the circles are linked, and the quotient space is homeomorphic to the sphere $S^{2}$.

#### If group acting on a set is finite so is the number of stabilizers
>[!dsn]+ Direct strict note
>If $G$ is finite, so is $O(x)$ for every $x$, and
>$$\# O(x)=(\# G)/(\# G_{x})$$

>[!proof]+
>It's a corollary of orbit definition and proof of [[If group acting on homogeneous space is finite then this space is also finite]].

***
#### Keywords
- [[Homogeneous space under group action]],
- [[Group acting on a set]],
- [[Equivalence class]],
- [[Equivalence relation]],
- [[Quotient set]],
- [[Symmetric group]],
- [[Permutation]],
- [[Cyclic group]],
- [[Euclidean space]],
- [[Vector space]],
- [[Linear groups]],
- [[Isometry]],
- [[Sphere]],
- [[Cardinality of a set]],
- [[Centralizer in a group]],
- [[Complex plane]],
- [[Hopf fibration]],
- [[Homeomorphism]],
- [[Quotient topology]]
#### Possibly related
- 
***
#### Sources: