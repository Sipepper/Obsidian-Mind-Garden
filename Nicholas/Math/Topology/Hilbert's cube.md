---
Last time checked: 2024-03-07
Complete: true
aliases:
---
# Hilbert's cube
***
###### tags: #Topology 
***
>[!dsn]+ Definition
>For each positive integer $n$, let the topological space $(I_{n},\tau_{n})$ be homeomorphic to $[0,1]$. Then the product space $\prod_{n=1}^{\infty}(I_{n},\tau_{n})$ is called the *Hilbert cube* and is denoted by $I^{\infty}$. The product space $\prod_{i=1}^{n}(I_{i},\tau_{i})$ is called the *$n$-cube* and is denoted by $I^{n}$, for each $n\in\mathbb{N}$.^[[[Sidney A. Morris - Topology without tears.pdf#page=230|Sidney A. Morris - "Topology without tears" p.230]]]

>The Hilbert cube is compact.^[[[Sidney A. Morris - Topology without tears.pdf#page=231|Sidney A. Morris - "Topology without tears" p.231]]]
>>[!proof]+
>>As [[homeomorphisms of Cantor space#interval is a continuous image of a Cantor space]], there is a continuous mapping $\phi_{n}$ of $(G_{n},\tau_{n})$ onto $(I_{n},\tau'_{n})$ where, for each $n\in\mathbb{N}$, $(G_{n},\tau_{n})$ and $(I_{n},\tau'_{n})$ are homeomorphic to the Cantor Space and $[0,1]$, respectively. Therefore by [[continuous maps between countable products of topological spaces]], there is a continuous mapping $\psi$ of $\prod_{n=1}^{\infty}(G_{n},\tau_{n})$ onto $\prod_{n=1}^{\infty}(I_{n},\tau'_{n})=I^{\infty}$. But  [[homeomorphisms of Cantor space#cantor space is homeomorhic to a countable product of cantor spaces]] says that $\prod_{n=1}^{\infty}(G_{n},\tau_{n})$ is homeomorphic to the Cantor Space $(G,\tau)$. Therefore $I^{\infty}$ is a continuous image of the compact space $(G,\tau)$, and hence is compact.

>The Hilbert cube is metrizable.^[[[Sidney A. Morris - Topology without tears.pdf#page=233|Sidney A. Morris - "Topology without tears" p.233]]]
>>[!proof]+
>>Hilbert cube is metrizable as [[countable product of metrizable spaces is metrizable]].

>The Hilbert cube is separable space.^[[[Sidney A. Morris - Topology without tears.pdf#page=236|Sidney A. Morris - "Topology without tears" p.236]]]
>>[!proof]+
>>As $I^{\infty}$ is a compact and metrizable space, thus by [[compact metrizable space is separable]] $I^{\infty}$ is separable.

***
#### Keywords
- [[Set of integers]],
- [[Topological space]],
- [[Homeomorphism]],
- [[Interval]],
- [[Product topology]],
- [[Compact set]],
- [[Set of natural numbers]],
- [[Continuous mapping]],
- [[Cantor space]],
- [[Kernel and image of a mapping]],
- [[Metrizable space]],
- [[Separable space]],
#### Possibly related
- [[n-cell]] 
***
#### Sources: