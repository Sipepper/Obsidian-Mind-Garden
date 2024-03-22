---
Last time checked: 2023-10-19
Complete: true
aliases:
---
# Transitive group action on a set
***
###### tags: #Group_Theory #Algebra 
***
>[!dsn]+ Definition
>The action $(G,X,\phi)$ is called *transitive* if for every $x,y\in X$ there exists $g\in G$ such that $g(x)=y$.^[[[Marcel Berger - Geometry 1.pdf#page=18 |Marcel Berger - "Geometry 1" p.6]]]

>In practice, it sufficient to check that some fixed $a\in X$ can be mapped to any $x\in X$ by some element $g\in G$. For if we have $g(a)=x$ and $h(a)=y$, then $y=(hg^{-1})(x)$.
>![[Pasted image 20230425212654.png]]

>[!example]+ 
>Put $A=\{1,\dots,n\}$, $S(A)=S_{n}$ (the symmetric group). Let $G=S_{n}$ then $G$ acts on $A$, and such action is transitive.

>[!example]+
>If $X$ is a vector space, it's linear group $\text{GL}(X)$, acts on $X$ *not* transitively, as $0\in X$, cannot be "moved" to some element $x\in X$ by any element from $\text{GL}(X)$. But if we exclude $0$ from $X$, $\text{GL}(X)$ will act transitively on $X\setminus\{0\}$.
***
#### Keywords
- [[Group acting on a set]],
- [[Function(mapping)]],
- [[Symmetric group]],
- [[Vector space]],
- [[Linear groups]]
#### Possibly related
- 
***
#### Sources: