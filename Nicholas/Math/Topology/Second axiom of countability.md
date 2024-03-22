---
Last time checked: 2024-03-01
Complete: false
aliases:
---
# Second axiom of countability
***
###### tags: #Topology 
***
>[!dsn]+ Axiom
>A topological space $(X,\tau)$ is said to satisfy the *second axiom of countability* (or to be *second countable*) if there exists a basis $\mathcal{B}$ for $\tau$ such that $\mathcal{B}$ consists of only a countable number of sets.^[[[Sidney A. Morris - Topology without tears.pdf#page=241|Sidney A. Morris - "Topology without tears" p.241]]]

>Let $\{U_{i}\}_{i\in\Lambda}$ be an open cover of $X$. If $X$ is second-countable, then there exists a countable subset $J\subset \Lambda$ with $X=\bigcup\limits_{j\in J}U_{j}$.^[[[Stefan Friedl - Algebraic topology.pdf#page=261|Stefan Friedl - "Algebraic topology" p.261 ]]]
>
>>[!proof]+
>>Let $\mathcal{B}$ be a countable basis for the topology of $X$. We write
>>$$\mathcal{B'}:=\{V\in\mathcal{B}:V\subset U_{i}\text{ for some }i\in\Lambda\}$$
>>Given $V\in\mathcal{B'}$ we pick $j\in\Lambda$ with $V\subset U_{j}$. From [[properties of countable sets]] that the set $J\subset\Lambda$  of all such $j$ is countable. It remains to show that $X=\bigcup\limits_{j\in J}U_{j}$.
>>Thus let $x\in X$. By hypothesis there exists an $i\in\Lambda$ with $x\in U_{i}$. Since $\mathcal{B}$ is a basis for the topology of $X$ there exists a $V\in\mathcal{B}$ with $x\in V\subset U_{i}$. Note that $V\in\mathcal{B'}$. But this implies that $x\in U_{j}$ for some $j\in J$.

>Let $X$ be a topological space.
>1. If $X$ admits a finite atlas, then $X$ is second-countable.
>2. If $X$ is compact and if it admits an atlas, then $X$ is second-countable.^[[[Stefan Friedl - Algebraic topology.pdf#page=262|Stefan Friedl - "Algebraic topology" p.262]]]
>
>>[!proof]+
>>1. Is a consequence of [[properties of countable sets]] (4), as every subset of $\mathbb{R}^{n}$ is second countable and as every chart $\Phi_{i}$ is a homeomorphism.
>>2. And this statement is a consequence of previous statement, as every compact topological space that admits an atlas also admits a finite atlas.

>[!example]+ 
>Let $\mathfrak{B}=\left\{\left(q-\frac{1}{n},q+\frac{1}{n} \right):q\in\mathbb{Q},n\in\mathbb{N}\right\}$. Then $\mathfrak{B}$ is a basis for the euclidean topology on $\mathbb{R}$. Therefore $\mathbb{R}$ is second countable.
>>[!proof]+
>>

>[!example]+
>Let $(X,\tau)$ be an uncountable set with the discrete topology. Then, as every singleton set must be in any basis for $\tau$, $(X,\tau)$ does not have any countable basis. So $(X,\tau)$ is not second countable.
***
#### Keywords
- [[Topological space]],
- [[Topology basis]],
- [[Cardinality of a set]],
- [[Set]],
- [[Open and closed subsets]],
- [[Covering of a set]],
- [[n-dimensional atlas]],
- [[n-dimensional chart]],
- [[Compact set]],
- [[Homeomorphism]],
- [[Neighborhood in topological space]],
- [[Euclidean topology]],
- [[Rational numbers]],
- [[Set of natural numbers]],
- [[Real line]],
- [[Discrete topology]],
#### Possibly related
- 
***
#### Sources: