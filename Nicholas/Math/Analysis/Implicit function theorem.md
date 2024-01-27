---
Last time checked: 2024-01-11
Complete: false
aliases:
---
# Implicit function theorem
***
###### tags: #Analysis/Multivariable #Topology/Differential 
***
>[!dsn]+ Theorem
>Let $U\subseteq \mathbb{R}^{n}\times\mathbb{R}^{k}$ be an open subset, and let $(x,y)=(x^{1},\dots,x^{n},y^{1},\dots,y^{k})$ denote the standard coordinates on $U$. Suppose $\Phi:U\to\mathbb{R}^{k}$ is a smooth function, $(a,b)\in U$, and $c=\Phi(a,b)$. If the $k\times k$ matrix
>$$\left(\frac{\partial \Phi^{i}}{\partial y^{j}}(a,b) \right)$$
>is non-singular, then there exist neighborhoods $V_{0}\subseteq\mathbb{R}^{n}$ of $a$ and $W_{0}\subseteq\mathbb{R}^{k}$ of $b$ and a smooth function $F:V_{0}\to W_{0}$ such that $\Phi^{-1}(c)\cap(V_{0}\times W_{0})$ is the graph of $F$, that is $\Phi(x,y)=c$ for $(x,y)\in V_{0}\times W_{0}$ if and only if $y=F(x)$.^[[[John M. Lee - Introduction to smooth manifolds.pdf#page=679 |John M. Lee - "Introduction to smooth manifolds" p.661 ]]]

>[!proof]+
>See [[John M. Lee - Introduction to smooth manifolds.pdf#page=679 |John M. Lee - "Introduction to smooth manifolds" p.661 ]]

>[!example]+ 
>
***
#### Keywords
- [[Euclidean space]],
- [[Open and closed subsets]],
- [[Smooth function]],
- [[Matrix]],
- [[Determinant]],
- [[Neighborhood in topological space]],
- [[Preimage]],
- [[Graph of a function]],
- [[Cartesian product of sets]]
#### Possibly related
- 
***
#### Sources: