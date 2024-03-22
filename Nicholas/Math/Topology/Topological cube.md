---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Topological cube
***
###### tags: #Topology 
***
>[!dsn]+ Definition
>Let $A$ be any set and for each $a\in A$ let the topological space $(I_{a},\tau_{a})$ be homeomorhpic to $[0,1]$. Then the product space $\prod\limits_{a\in A}(I_{a},\tau_{a})$ is denoted by $I^{A}$ and referred to as a *cube*.^[[[Sidney A. Morris - Topology without tears.pdf#page=274|Sidney A. Morris - "Topology without tears" p.274]]]

>[!example]+
>

>Hilbert cube is a special case of a topological cube, denoted as $I^{\mathbb{N}}$ or $I^{\infty}$.

>For any set $A$, the cube $I^{A}$ is compact.^[[[Sidney A. Morris - Topology without tears.pdf#page=274|Sidney A. Morris - "Topology without tears" p.274]]]
>>[!proof]+
>>It's a corollary of [[Tychonoff's theorem]].

#### Every metric space is homeomorphic to a subspace of a cube indexed by this space
>[!dsn]+ Proposition
>Let $(X,d)$ be a metric space. Then it is homeomorphic to a subspace of the cube $I^{X}$.^[[[Sidney A. Morris - Topology without tears.pdf#page=274|Sidney A. Morris - "Topology without tears" p.274]]]

>[!proof]+
>Without loss of generality, assume $d(a,b)\le1$ for all $a$ and $b$ in $X$. For each $a\in X$, let $f_{a}$ be the continous mapping of $(X,d)$ into $[0,1]$ given by
>$$f_{a}(x)=d(x,a)$$
>That the family $\{f_{a}\}$, $a\in X$, separates points and closed sets is easily shown in proof of [[every separable metric space is homeomorphic to a subspace of the Hilbert cube]]. Thus, by [[the embedding lemma]] $(X,d)$ is homeomorphic to a subspace of the cube $I^{X}$.

>[!example]+ 
>
***
#### Keywords
- [[Set]],
- [[Topological space]],
- [[Homeomorphism]],
- [[Interval]],
- [[Product topology]],
- [[Hilbert's cube]],
- [[Compact set]],
- [[Metric space]],
- [[Continuous mapping]],
- [[Subspace topology]],
- [[Open and closed subsets]]
#### Possibly related
- 
***
#### Sources: