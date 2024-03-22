---
Last time checked: 2024-02-16
Complete: false
aliases:
---
# Subgroup of translations of euclidean plane is a lattice
***
###### tags: #Geometry #Algebra 
***
>[!dsn]+ Proposition
>The subgroup $\Gamma=G\cap T(E)$ of translation of crystallographic group $G$ is a lattice, that is there exists a basis $\{\vec{u},\vec{v}\}$ of $\vec{E}$ such that $\Gamma$ consists exactly of translations by vectors in $\mathbb{Z}\vec{u}+\mathbb{Z}\vec{v}$.^[Marcel Berger - "Geometry 1" p.16]

>[!proof]+
>We start by proving, by contradiction, that $\Gamma$ contains at least two linearly independent translations. Assume first that $\Gamma=\text{Id}_{E}$, that is, $G$ contains only rotations; if two such rotations $r,s$ had different centers, their commutator $[r,s]=rsr^{-1}s^{-1}$ would be a non-trivial translation, by [[Commutator of two rotations with different centers is a translations]]. Thus the rotations of $G$ all have the same center $\omega$, and $\bigcup\limits_{g\in\Gamma}g(P)$ is contained in a disc of fixed radius, contradicting first axiom of [[axioms for tilings and crystallographic group]].
>![[Pasted image 20230815233102.png]]
>Now suppose that the directions of elements of $\Gamma$ are all parallel. Take $r\in G\setminus\Gamma$ and a translation $t\in\Gamma$ by a vector $\vec{\xi}$. Then $rtr^{-1}$ is a translation by the vector $r(\vec{\xi})$, and, since $r(\vec{\xi})$ must be parallel to $\vec{\xi}$, we conclude that $r$ is a reflection through some point. All elements of $G\setminus\Gamma$ are thus reflections through points; but if two reflections $r,s$ have centers $a,a'$, then $sr$ is a translation by the vector $2\overrightarrow{aa'}$
>![[Pasted image 20230815233926.png]]
>Thus the centers of all elements of $G\setminus\Gamma$ are on a line $D$ parallel to the direction of the translations; this implies that 
>$$\bigcup\limits_{g\in G}g(P)$$
>is contained in a strip centered on $D$
>![[Pasted image 20230815234102.png]]
>again contradicting first axiom of [[axioms for tilings and crystallographic group]].
>
>This shows that $\Gamma$ contains translations by two linearly independent vectors. There remains to show that there exist $\vec{u},\vec{v}$ such that
>$$\Gamma=\{\text{translations by }\vec{w}:\vec{w}\in\mathbb{Z}\vec{u}+\mathbb{Z}\vec{v}\}$$
>As [[crystallographic group acts discretely on real plane]], we can choose a translation in $\Gamma$ by a vector $\vec{u}$ with minimal norm $\|\vec{u}\|$, then another translation in $\Gamma$ by $\vec{v}\notin \mathbb{Z}\vec{u}$ with minimal norm $\|\vec{v}\|$. We will show that $\vec{u}$ and $\vec{v}$ are the desired vectors.
>
>Let $Q$ be the parallelogram
>$$Q=\{a+t\vec{u}+s\vec{v}:t,s\in[0,1]\}$$
>for a fixed $a\in E$. Since $G$ is a group, and 
>$$\Gamma\supset\{\text{translations by }\vec{w}:\vec{w}\in\mathbb{Z}\vec{u}+\mathbb{Z}\vec{v}\}$$
>the images $g(Q)$, $g\in\Gamma$, fill $E$. Thus, if there is a point in the orbit of $a$ under $\Gamma$ that is not in $a+\mathbb{Z}\vec{u}+\mathbb{Z}\vec{v}$, there is also one, which we call $y$, inside $Q$
>![[Pasted image 20230817120739.png]]
>We claim that the distance from $y$ to one of the vertices of $Q$ is strictly less than $\|\vec{u}\|$ or $\|\vec{v}\|$; to see this, assume, without loss of generality, that $y$ is in the interior of the triangle
>$$\{a,b=a+\vec{u},c=a+\vec{v}\}$$
>and observe that the line $\langle a,y \rangle$ intersects the side $\langle b,c \rangle$ at $a'$, and we have $d(a,y)<d(a,a')$
>![[Pasted image 20230817121426.png]]
>But then
>$$\begin{align}d(a,a')&<\frac{d(a,b)+d(a,c)}{2}\\ &=\frac{\|\vec{u}\|+\|\vec{v}\|}{2} \end{align}$$
>proving our claim, and contradicting the choice of $\vec{u}$ and $\vec{v}$.

>[!example]+ 
>
***
#### Keywords
- [[Group]],
- [[Axioms for tilings and crystallographic group]],
- [[Lattice in vector space]],
- [[Basis of vector space]],
- [[Euclidean space]],
- [[Linear span]],
- [[Set of integers]],
- [[Commutator subgroup]],
- [[Rotations of euclidean space]],
- [[Conjugation in groups]],
- [[Normed space]],
- [[Euclidean space]],
- [[Vector]],
- [[Vector space]],
- [[Orbit in homogeneous space]],
#### Possibly related
- 
***
#### Sources: