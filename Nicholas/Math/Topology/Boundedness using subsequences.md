---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Boundedness using subsequences
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>A subset $E$ of topological vector space $(X,\tau)$ is bounded if and only if for any sequence $\set{u_{n}}\subset E$ and $\set{\alpha_{n}}\subset\mathbb{F}$ such that $\alpha_{n}\to0$ when $n\to\infty$  and $\alpha_{n}u_{n}\to\theta$ when $n\to\infty$.^[[[Fabio Silva Botelho - Functional Analysis and Applied Optimization in Banach Spaces.pdf#page= 22|Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.22]]]

>[!proof]
>Suppose that set $E$ is bounded. Let $\mathcal{U}$ be a balanced neighbourhood of $\theta$ in topological space $(X,\tau)$ then $E\subset t\mathcal{U}$ for some $t$.
>Then for sequence $\set{u_{n}}\subset E$, when $\alpha_{n}\to0$ exist a positive integer $N$ such that  if $n>N$, then $t<\frac{1}{|\alpha_{n}|}$. Because $t^{-1}E\subset\mathcal{U}$ and $\mathcal{U}$ is balanced, we have that $\alpha_{n}u_{n}\in\mathcal{U}$, $\forall n>N$, and therefore $\alpha_{n}u_{n}\to\theta$.
>
>Conversely, let $E$ be unbounded, then exist a neighbourooh of zero $\mathcal{V}$ and sequence such that $r_{n}\to\infty$ and $E\not\subset r_{n}\mathcal{V}$, that is we can choose elements from sequence $u_{n}$ such that $r_{n}^{-1}u_{n}\notin\mathcal{V}$, $\forall n\in\mathbb{N}$, and therefore $\set{r_{n}^{-1}u_{n}}$ is not converging to $\theta$.

>[!example]+
>
***
#### Keywords
- [[Set]],
- [[Topological vector space]],
- [[Bounded set]],
- [[Sequence]],
- [[Convergence]], 
- [[Balanced subsets of topological vector spaces]],
- [[Neighborhood in topological space]],
#### Possibly related
- 
***
#### Sources: