# Any union of components of the boundary of manifold is closed subset
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Let $M$ be a topological manifold, then any union of components of $\partial M$ is a closed subset of $M$. In particular $\partial M$ itself is a closed subset of $M$.^[Stefan Friedl - "Algebraic topology" p.265]

>[!proof]+
>Let $M$ be a topological manifold. By definition the set of points in $M$ admitting a chart of type $(i)$ is an open subset of $M$. If follows from the definition of $\partial M$ that $M\setminus\partial M$ is an open subset. Thus the boundary $\partial M$ is a closed subset of $M$.
>
>Denote by $\{Y_{i}\}_{i\in I}$ the family of all components of $\partial M$. By [[in topological space with finite number of components every component is open]] each $Y_{i}$ is an open subset of $\partial M$, as $M$ is second countable and. 
>Thus for any $i\in I$ there exists, by definition of the subspace topology, an open set $Z_{i}\subset M$ with $Z_{i}\cap\partial M=Y_{i}$. For any $J\subset I$ we have
>$$M\setminus\bigcup\limits_{j\in J}Y_{j}=\underbrace{M\setminus\partial M}_{\text{open in }M}\cup\underbrace{\bigcup\limits_{j\notin J}Z_{j}}_{\text{open in }M}$$
>we have thus shown that the union of componenets of $\partial M$ corresponding to $J$ is indeed a closed subset of $M$.

>[!example]+ 
>
***
#### Keywords
- [[Topological manifold]],
- [[Component of topological space]],
- [[Boundary of topological manifold]],
- [[Open and closed subsets]],
- [[n-dimensional chart]],
- [[Subspace topology]],
- [[Set]]
#### Possibly related
- 
***
#### Sources: