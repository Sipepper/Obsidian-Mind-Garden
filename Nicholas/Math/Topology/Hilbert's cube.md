# Hilbert's cube
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>For each positive integer $n$, let the topological space $(I_{n},\tau_{n})$ be homeomorphic to $[0,1]$. Then the product space $\prod_{n=1}^{\infty}(I_{n},\tau_{n})$ is called the *Hilbert cube* and is denoted by $I^{\infty}$. The product space $\prod_{i=1}^{n}(I_{i},\tau_{i})$ is called the *$n$-cube* and is denoted by $I^{n}$, for each $n\in\mathbb{N}$.^[Sidney A. Morris - "Topology without tears" p.230]

#### Compactness
>[!dsn]+ Direct strict note
>The Hilbert cube is compact.^[Sidney A. Morris - "Topology without tears" p.231]

>[!proof]+
>By [[Homeomorphisms of Cantor space#9.3.5. Об интервале как образе непрерывного отображения пространства Кантора]], there is a continuous mapping $\phi_{n}$ of $(G_{n},\tau_{n})$ onto $(I_{n},\tau'_{n})$ where, for each $n\in\mathbb{N}$, $(G_{n},\tau_{n})$ and $(I_{n},\tau'_{n})$ are homeomorphic to the Cantor Space and $[0,1]$, respectively. Therefore by [[Continuous maps between countable products of topological spaces]], there is a continuous mapping $\psi$ of $\prod_{n=1}^{\infty}(G_{n},\tau_{n})$ onto $\prod_{n=1}^{\infty}(I_{n},\tau'_{n})=I^{\infty}$. But  [[Homeomorphisms of Cantor space#9.3.3. О гомеоморфности пространства Кантора любому счетному произведению пространств Кантора]] says that $\prod_{n=1}^{\infty}(G_{n},\tau_{n})$ is homeomorphic to the Cantor Space $(G,\tau)$. Therefore $I^{\infty}$ is a continuous image of the compact space $(G,\tau)$, and hence is compact.

#### Metrizability
>[!dsn]+ Direct strict note
>The Hilbert cube is metrizable.^[Sidney A. Morris - "Topology without tears" p.233]

>[!proof]+
>Hilbert cube is metrizable by [[Countable product of metrizable spaces is metrizable]].

#### Separability
>[!dsn]+ Direct strict note
>The Hilbert cube is separable space.^[Sidney A. Morris - "Topology without tears" p.236]

>[!proof]+
>As $I^{\infty}$ is a compact and metrizable space, thus by [[Compact metrizable space is separable]] $I^{\infty}$ is separable.

***
#### Keywords
- [[Topological space]],
- [[Homeomorphism]],
- [[Product topology]],
- [[Compact set]],
- [[Continuous mapping]],
- [[Cantor space]],
- [[Metrizable space]],
- [[Separable space]],
- [[Interval]],
- [[Function(mapping)]]
#### Possibly related
- 
***
#### Sources: