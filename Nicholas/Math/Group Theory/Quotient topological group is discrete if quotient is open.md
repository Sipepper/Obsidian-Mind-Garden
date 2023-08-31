# Quotient topological group is discrete if quotient is open
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Direct strict note
>Let $G$ be a topological group and $N$ a normal subgroup. Then $G/N$ is discrete if and only if $N$ is open. Also $G/N$ is Hausdorff if and only if $N$ is closed.^[[[Sidney A. Morris - Topology without tears.pdf#page=525|Sidney A. Morris - "Topology without tears" p.525]]]

>[!proof]+
>#### Discreteness
>$\Rightarrow$
>Let $G/N$ be discrete topological group. Then a set $\{e'\}$ which consists from only neutral element $e'$ in $G/N$, is open. Then $p^{-1}(\{e\})=N$, as $p$ is a quotient map, $p^{-1}(\{e\})$ is open in $G$, and so $N$ is also open.
>
>$\Leftarrow$
>Let $N$ be an open set. Then all cosets $gN$ is also an open sets, then as any subset of $G/N$ can be viewed as $p(g_{1}N\cup\dots\cup g_{n}N\cup\dots)$, every subset of $G/N$ is open, that is $G/N$ is discrete.
>***
>#### Hausdorfness
>$\Rightarrow$
>Let $G/N$ be a Hausdorff topological group. Then $\overline{\{e'\}}=e'$ where $e'$ is a neutral element of $G/N$, that is $\{e'\}$ is a closed set. Therefore, as $p^{-1}(\{e'\})=N$ and $p$ is a quotient map, $N$ is a closed set in $G$.
>
>$\Leftarrow$
>By [[T1 topological group is a Hausdorff space]] it sufficient to prove that every singleton set $\{x\}\in G/N$ is a closed set. Therefore let $\{x\}$ be a singleton subset of $G/N$, then $p^{-1}(x)=xN$, as $N$ is a closed set and by [[Topological group translations are homeomorphisms]] $xN$ is a closed set. Thus as $p$ is a quotient homomorphism, $\{x\}$ is closed in $G/N$, as $p^{-1}(x)$ is closed in $G$.

>[!example]+ 
>
***
#### Keywords
- [[Topological group]],
- [[Normal subgroup]],
- [[Discrete topology]],
- [[Quotient topology on a quotient group]],
- [[Hausdorff space]],
- [[Open and closed subsets]],
- [[Quotient group]],
- [[Preimage]],
- [[Group coset]],
- [[Closure of a set]],
- [[Closure of certain subgroups in topological groups]],
- [[Set]],
- [[Homomorphism]]
#### Possibly related
- 
***
#### Sources: