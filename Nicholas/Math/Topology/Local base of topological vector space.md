---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Local base of topological vector space
***
###### tags: #Topology 
***
>[!dsn]+ Definition
>Suppose $\set{\delta_{n}}$ is a sequence such that $\delta_{n}\to0$, $\delta_{n}<\delta_{n-1}$, $\forall n\in\mathbb{N}$ and $\mathcal{V}$ a bounded neighborhood of zero in $U$, then $\set{\delta_{n}\mathcal{V}}$ is a local base for $U$.

>[!proof]+
>Let $\mathcal{U}$ be a neighborhood of zero; as $\mathcal{V}$ is bounded, there exists $t_{0}\in\mathbb{R}^{+}$ such that $\mathcal{V}\subset t\mathcal{U}$ for any $t>t_{0}$. As $\lim\limits_{n\to\infty}\delta_{n}=0$, there exists $n_{0}\in\mathbb{N}$ such that if $n\ge n_{0}$, then $\delta_{n}<\frac{1}{t_{0}}$, so that $\delta_{n}\mathcal{V}\subset\mathcal{U}$, $\forall n$ such that $n\ge n_{0}$.

>[!example]+
>
***
#### Keywords
- [[Sequence]],
- [[Bounded set]],
- [[Properties of balanced and convex neighbourhoods of zeros in topological vector spaces]],
- [[Neighborhood in topological space]],
- [[Neighborhood basis at point in topological space]],
#### Possibly related
- 
***
#### Sources: