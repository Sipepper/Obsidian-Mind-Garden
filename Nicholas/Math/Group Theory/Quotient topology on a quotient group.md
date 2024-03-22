---
Last time checked: 2024-02-25
Complete: false
aliases:
---
# Quotient topology on a quotient group
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Proposition
>Let $N$ be a normal subgroup of a topological group $G$. If the quotient group $G/N$ is given the quotient topology under the canonical homomorphism $p:G\to G/N$ (that is, $U$ is open in $G/N$ if and only if $p^{-1}(U)$ is open in $G$), then $G/N$ becomes a topological group. Further, the map $p$ is not only continuous but also open.^[[[Sidney A. Morris - Topology without tears.pdf#page=523|Sidney A. Morris - "Topology without tears" p.523]]]

>[!proof]+
>To see that $p$ is an open map, let $O$ be an open set in $G$. Then $p(O)=p(NO)$, or $p^{-1}(p(O))=NO\subseteq G$. Since $O$ is open, $nO$,$n\in N$, is open (by [[topological group translations are homeomorphisms]]) and thus $NO$ is open as union of open sets. So by the definition of the quotient topology on $G/N$, $p(O)$ is open in $G/N$; that is, $p$ is an open map. 
>Let $aN,bN\in G/N$. Let $U$ be a neighbourhood of $ab^{-1}N$. Then to show that $m^{-1}(U)$ is open in $G/N\times G/N$, we can construct a diagram
>$$\begin{CD}G\times G@>{m}>>G\\ @V{p\times p}VV @V{p}VV\\ G/N\times G/N@>{m'}>> G/N\end{CD}$$
>from which, we have the following
>$$m'^{-1}(U)=(p\times p)\left(m^{-1}(p^{-1}(U))\right)$$
>i.e. $U$ is an open neighbourhood of $ab^{-1}N$, $p^{-1}(U)$ is an open neighbourhood of $ab^{-1}$ (because $p$ is a continuous map), $m^{-1}(p^{-1}(U))=A\times B$ where $A$ and $B$ are open neighbourhoods of $a$ and $b^{-1}$ respectively, then $(p\times p)(A\times B)=p(A)\times p(B)$ is an open neighbourhoods of $aN$ and $bN$ (because $p$ is an open map). Therefore $m'^{-1}(U)$ is open, and $m'$ is continuous.

>[!example]+
>

>Note that quotient maps of topological spaces are not necessarily open maps.

>Quotient maps of topological groups are not necessarily closed maps. For example, if $\mathbb{R}^{2}$ denote the product group $\mathbb{R}\times\mathbb{R}$ with the usual topology, and $p$ is the projection of $\mathbb{R}^{2}$ onto its first factor $\mathbb{R}$, then the set $S=\left\{\left(x,\frac{1}{x} \right):x\in\mathbb{R},x\ne0\right\}$ is closed in $\mathbb{R}^{2}$ and $p$ is a quotient map with $p(S)$ not closed in $\mathbb{R}$.
***
#### Keywords
- [[Normal subgroup]],
- [[Topological group]],
- [[Quotient group]],
- [[Quotient topology]],
- [[Homomorphism]],
- [[Open and closed subsets]],
- [[Preimage]],
- [[Continuous mapping]],
- [[Open and closed mappings]],
- [[Product topology]],
- [[Neighborhood in topological space]],
- [[Group coset]],
- [[Projection map in product spaces]],
- [[Cartesian product of sets]],
- [[Real line]]
#### Possibly related
- 
***
#### Sources: