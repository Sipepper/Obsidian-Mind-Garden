---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Image of basis under quotient map is a basis in quotient topology
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>Let $X$ be a topological space and let $\sim$ be an equivalence relation on $X$. Further let $\mathcal{B}$ be a basis of the topology of $X$. If the projection $p:X\to X/\sim$ is an open map, then
>$$p(\mathcal{B})=\{p(B):B\in\mathcal{B}\}$$
>is a basis for the topology of $X/\sim$.^[[[Stefan Friedl - Algebraic topology.pdf#page=183|Stefan Friedl - "Algebraic topology" p.183]]]

>[!proof]+
>First note that the sets in $p(\mathcal{B})$ are indeed open subsets of $X/\sim$ since we assume that the projection is open.
>Let $U\subset X/\sim$ be an open set and let $y\in U$. We need to show that there exists a $B\in\mathcal{B}$ with $y\in p(B)\subset U$.
>We choose and $x\in X$ with $p(x)=y$. Since $\mathcal{B}$ is a basis for the topology of $X$ and since $p^{-1}(U)$ is open in $X$ there exists a $B\in\mathcal{B}$ with $x\in B\subset p^{-1}(U)$. But then we also have that $y=p(x)\in p(B)\subset p(p^{-1}(U))=U$. 

>[!example]+ 
>
***
#### Keywords
- [[Topological space]],
- [[Equivalence relation]],
- [[Quotient topology]],
- [[Topology basis]],
- [[Open and closed mappings]],
- [[Projection map]],
- [[Set]],
- [[Open and closed subsets]],
- [[Neighborhood in topological space]],
- [[Preimage]],
- [[Kernel and image of a mapping]]
#### Possibly related
- 
***
#### Sources: