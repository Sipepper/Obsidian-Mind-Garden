---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Product topology
***
###### tags: #Topology 
***
#### Finite case
>[!dsn]+ Definition
>Let $(X_{1},\tau_{1}),(X_{2},\tau_{2}),\dots,(X_{n},\tau_{n})$ be topological spaces. Then the *product topology* $\tau$ on the set $X_{1}\times X_{2}\times\dots\times X_{n}$ is the topology having the family $\set{O_{1}\times O_{2}\times\dots\times O_{n}:O_{i}\in\tau_{i},\;i=1,\dots,n}$ as a basis. The set $X_{1}\times X_{2}\times\dots\times X_{n}$ with the topology $\tau$ is said to be the *product of the spaces* $(X_{1},\tau_{1}),(X_{2},\tau_{2}),\dots,(X_{n},\tau_{n})$ and is denoted by $(X_{1}\times X_{2}\times\dots\times X_{n},\tau)$ or $(X_{1},\tau_{1})\times(X_{2},\tau_{2})\times\dots\times(X_{n},\tau_{n})$.^[[[Sidney A. Morris - Topology without tears.pdf#page=194|Sidney A. Morris - "Topology without tears" p.194]]]

>[!example]+ 
>Let $X_{i}=\mathbb{R}$, $\forall i=1,\dots,n$ then $X_{1}\times X_{2}\times\dots\times X_{n}$ be the set $\mathbb{R}^{n}$ with topology with basic open sets are consisting of "open parallelepipeds". In particular it's the Euclidean topology.

>Let $\mathfrak{B}_{1},\mathfrak{B}_{2},\dots,\mathfrak{B}_{n}$ be bases for the topological spaces $(X_{1},\tau_{1}),(X_{2},\tau_{2}),\dots,(X_{n},\tau_{n})$, respectively. Then the family of sets 
>$$\mathcal{O}=\set{O_{1}\times O_{2}\times\dots\times O_{n}:O_{i}\in\mathfrak{B}_{i},i=1,\dots,n}$$ is a basis for the product topology on $X_{1}\times X_{2}\times\dots\times X_{n}$.^[[[Sidney A. Morris - Topology without tears.pdf#page=195|Sidney A. Morris - "Topology without tears" p.195]]]
>>[!proof]+
>>Let $W\subset X_{1}\times\dots\times X_{n}$ be an open set and let $(x_{1},\dots,x_{n})\in W$. By the definition of the product topology there exist open sets $U_{i}\subset X_{i}$, $i=1,\dots,k$ with $(x_{1},\dots,x_{n})\in U_{1}\times\dots\times U_{n}$ and $U_{1}\times\dots\times U_{n}\subset W$.
>>Let $i\in\{1,\dots,n\}$. Since $\mathcal{B}_{i}$ is a basis for $X_{i}$ we see that there exists a $B_{i}\in\mathcal{B}_{i}$ with $x\in B_{i}\subset U_{i}$. It follows that
>>$$(x_{1},\dots,x_{n})\in B_{1}\times\dots\times B_{n}\subset U_{1}\times\dots\times U_{n}\subset W$$
>>Therefore $\mathcal{O}$ is indeed a basis for $X_{1}\times\dots\times X_{n}$

>Let $C_{1},C_{2},\dots,C_{n}$ be closed subsets of the topological spaces $(X_{1},\tau_{1}),(X_{2},\tau_{2}),\dots,(X_{n},\tau_{n})$, respectively. Then $C_{1}\times C_{2}\times\dots\times C_{n}$ is a closed subset of the product space $(X_{1}\times X_{2}\times\dots\times X_{n},\tau)$.^[[[Sidney A. Morris - Topology without tears.pdf#page=195|Sidney A. Morris - "Topology without tears" p.195]]]
>>[!proof]+
>>$$\begin{align}&(X_{1}\times X_{2}\times\dots\times X_{n})\setminus(C_{1}\times C_{2}\times\dots\times C_{n})\\ &=((X_{1}\setminus C_{1})\times X_{2}\times\dots\times X_{n})\cup\\ &\cup (X_{1}\times(X_{2}\setminus C_{2})\times X_{3}\times\dots\times X_{n})\cup\\ &\dots \\ &\cup(X_{1}\times X_{2}\times\dots\times X_{n-1}\times(X_{n}\setminus C_{n})) \end{align}$$
>>which is a union of open sets(as a product of open sets is open) and so is an open set in $(X_{1},\tau_{1})\times(X_{2},\tau_{2})\times\dots\times(X_{n},\tau_{n})$. Therefore its compliment, $C_{1}\times C_{2}\times\dots\times C_{n}$, is a closed set, as required.

#### Countable case
>[!dsn]+ Definition
>Let $(X_{1},\tau_{1}),(X_{2},\tau_{2}),\dots,(X_{n},\tau_{n}),\dots$ be a countably infinite family of topological spaces. Then the *product*,$\prod_{i=1}^{\infty}X_{i}$, of the sets $X_{i}$, $i\in\mathbb{N}$ consists of all the infinite sequences $\set{x_{i}}_{i=1}^{\infty}$, where $x_{i}\in X_{i}$ for all $i$(sometimes written as $\prod_{i=1}^{\infty}x_{i}$). The *product space*, $\prod_{i=1}^{\infty}(X_{i},\tau_{i})$ consists of the product $\prod_{i=1}^{\infty}X_{i}$ with the topology $\tau$ having as its basis the family
>$$B=\left\{\prod_{i=1}^{\infty}O_{i}:O_{i}\in\tau_{i}\text{ and } O_{i}=X_{i}\text{ for all but a finite number of }i \right\}$$
>So a basic open set is of the form
>$$O_{1}\times O_{2}\times\dots\times O_{n}\times X_{n+1}\times X_{n+2}\times\dots$$
>.^[[[Sidney A. Morris - Topology without tears.pdf#page=224|Sidney A. Morris - "Topology without tears" p.224]]]

>Also the *product of open sets need not be open in the product topology* $\tau$. In particular, if $O_{1},O_{2},\dots,O_{n},\dots$ are such that each $O_{i}\in\tau_{i}$, and $O_{i}\ne X_{i}$ for all $i$, then $\prod_{i=1}^{\infty}O_{i}$ cannot be expressed as a union of members of $\mathfrak{B}$ and so is not open in the product space $(\prod_{i=1}^{\infty}X_{i},\tau)$.

#### Case of arbitrary cardinality
>[!dsn]+ Definition
>Let $I$ be a set, and for each $i\in I$, let $(X_{i},\tau_{i})$ be a topological space. The *product space*, denoted by $\prod_{i\in I}(X_{i},\tau_{i})$, consists of the product set $\prod_{i\in I}X_{i}$ with the topology $\tau$ having as its basis the family
>$$\mathfrak{B}=\left\{\prod_{i\in I}O_{i}:O_{i}\in\tau_{i}\text{ and }O_{i}=X_{i},\text{ for all but a finite number of }i \right\}$$
>The topology $\tau$ is called the *product topology* (or the *Tychonoff topology*).^[[[Sidney A. Morris - Topology without tears.pdf#page=260|Sidney A. Morris - "Topology without tears" p.260]]]

>Let $I$ be a set and for $i\in I$, let $C_{i}$ be a closed subset of a topological space $(X_{i},\tau_{i})$. Then $\prod_{i\in I}C_{i}$ is a closed subset of $\prod_{i\in I}(X_{i},\tau_{i})$.^[[[Sidney A. Morris - Topology without tears.pdf#page=261|Sidney A. Morris - "Topology without tears" p.261]]]
>>[!proof]+
>>

>Let $I$ be a set and let $\set{(X_{i},\tau_{i}):i\in I}$ be a family of topological spaces having product space $(\prod_{i\in I}X_{i},\tau)$. If for each $i\in I$, $B_{i}$ is a basis for $\tau_{i}$, then
>$$\mathfrak{B}'=\left\{\prod_{i\in I}O_{i}:O_{i}\in B_{i}\text{ and }O_{i}=X_{i}\text{ for all but a finite number of }i\right\}$$
>is a basis for $\tau$.^[[[Sidney A. Morris - Topology without tears.pdf#page=261|Sidney A. Morris - "Topology without tears" p.261]]]
>>[!proof]+
***
#### Keywords
- [[Topological space]],
- [[Cartesian product of sets]],
- [[Topology basis]],
- [[Set]],
- [[Euclidean topology]],
- [[Real line]],
- [[Euclidean space]],
- [[Open and closed subsets]],
- [[Cardinality of a set]],
- [[Sequence]]
#### Possibly related
- 
***
#### Sources: