---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Every subset of Euclidean space is second countable and Hausdorff
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>Every subset of some $\mathbb{R}^{n}$ is second countable and Hausdorff.^[[[Stefan Friedl - Algebraic topology.pdf#page=262|Stefan Friedl - "Algebraic topology" p.262]]]

>[!proof]+
>As $\mathbb{R}$ is second countable, if we choose
>$$\mathcal{B}=\left\{\left(q-\frac{1}{n},q+\frac{1}{n}\right):q\in\mathbb{Q},n\in\mathbb{N} \right\}$$
>as a basis. Then by [[Euclidean topology]] we see that euclidean topology can have basis of all *hyperrectangles*
>$$[a_{1},b_{1}]\times\dots\times[a_{k},b_{k}]\qquad a_{i},b_{j}\in\mathbb{Q}$$
>taken from $\mathcal{B}$. As finite product of countable number of elements is countable, thus $\mathbb{R}^{n}$ is second countable.
>
>Therefore as every subset $V\subset\mathbb{R}^{n}$ has subspace topology where every basic open set is of the form $V\cap B$, $B\in\mathcal{B}$, thus is atmost countable. That is  $V$ is second countable with subspace topology.
>
>Let $V,W\subset\mathbb{R}^{n}$ be an open subset of $\mathbb{R}^{n}$ such that $V\cap W=\emptyset$. Let $A\subset\mathbb{R}^{n}$. Then $A\cap V$ and $A\cap W$ are open subsets of $A$, and
>$$A\cap V\cap A\cap W=A\cap V\cap W=A\cap\emptyset=\emptyset$$
>thus $A$ is Hausdorff. 

>[!example]+ 
>
***
#### Keywords
- [[Set]],
- [[Euclidean space]],
- [[Second axiom of countability]],
- [[Hausdorff space]],
- [[Topology basis]],
- [[Cardinality of a set]],
- [[Euclidean topology]],
- [[Subspace topology]],
- [[Open and closed subsets]],
#### Possibly related
- 
***
#### Sources: