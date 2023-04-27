# Compact subsets of a metric space
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>Let $A$ be a compact subset of a metric space $(X,d)$. Then $A$ is closed and bounded.^["Topology without tears" Sidney A. Morris с. 184]

>[!proof]
>From [[Compact subset of metrizable space is closed]] we can conclude that $A$ is a closed set. Now choose some point $x_{0}\in X$ and define a mapping $f:(A,\tau)\to\mathbb{R}$ in following way $$f(a)=d(a,x_{0})\quad \forall a\in A$$ where $\tau$ is the subspace topology on $A$. Where $f$ is the continuous mapping. Then, by [[Compactness is preserved under surjective continuous mapping]], image $f(A)$ will be compact. Therefore, by inverse of [[Heine-Borel theorem]], $f(A)$ will be bounded; i.e. exists some real number $M$ such that $$f(a)\le M\quad\forall a\in A$$ Thus $d(a,x_{0})\le M$, $\forall a\in A$. Putting $r=2M$, we see that by triangle inequality we have that $d(a_{1},a_{2})\le r$, $\forall a_{1},a_{2}\in A$.

>[!example] 
>
***
#### Keywords
- [[Compact set]],
- [[Metric space]],
- [[Open and closed subsets]],
- [[Bounded set]],
- [[Function(mapping)]],
- [[Continuous mapping]],
- [[Subspace topology]]
#### Possibly related
- 
***
#### Sources: