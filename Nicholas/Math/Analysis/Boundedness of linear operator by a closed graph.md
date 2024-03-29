---
Last time checked: 2024-01-31
Complete: true
aliases:
---
# Boundedness of linear operator by a closed graph
***
###### tags: #Analysis/Functional 
***
>[!dsn]+ Proposition
>Let $U$ and $V$ be a Banach spaces and let $A:U\to V$ be a linear operator. Then $A$ will be bounded linear operator if and only if it's graph be a closed set.^[[[Fabio Silva Botelho - Functional Analysis and Applied Optimization in Banach Spaces.pdf#page= 50|Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.32]]]

>[!proof]+
>Suppose that $\Gamma(A)$ is a closed set. Because $A$ is a linear operator, then $\Gamma(A)$ be a subspace of a direct product $U\oplus V$. Also by closedness of $\Gamma$ is follows that it's a Banach space with norm $$\|(u,A(u))\|=\|u\|_{U}+\|A(u)\|_{V}$$ 
>Consider the following continuous mapping 
>$$\Pi_{1}(u,A(u))=u$$
>and
>$$\Pi_{2}(u,A(u))=A(u)$$
>Note that $\Pi_{1}$ is a bijection, and thus by [[Inverse mappings between two Banach spaces|theorem of inverse mappings between two Banach spaces]] it follows that $\Pi_{1}^{-1}$ be a continuous mapping. As well as mapping 
>$$A=\Pi_{2}\circ\Pi_{1}^{-1}$$
>
>If $A$ is a bounded linear operator then it's also a continuous mapping. Thus the strong convergence $u_{n}\to u$ in $U$ applies the strong convergence of $A(u_{n})\to A(u)$ in $V$. 
>Therefore by definition of closed set, the set $\Gamma(u)$ contains all of it's limit points. Thus closed.  
***
#### Keywords
- [[Banach space]],
- [[Linear operator]],
- [[Bounded operator]],
- [[Graph of a function]],
- [[Open and closed subsets]],
- [[Direct sum of vector spaces]],
- [[Normed space]],
- [[Continuous mapping]],
- [[Function(mapping)]],
- [[Inverse function]],
- [[Strong convergence]],
- [[Limit point in topological space]],
#### Possibly related
- [[Projection map in product spaces]]
***
#### Sources: