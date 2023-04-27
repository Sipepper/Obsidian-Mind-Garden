# Quotient group of a locally compact group is locally compact
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Direct strict note
>If $G/N$ is any quotient group of a locally compact group $G$, then $G/N$ is locally compact.^[Sidney A. Morris - "Topology without tears" p.525]

>[!proof]+
>As $G$ is locally compact then every point $g\in G$ has a compact neighborhood $U$. As $p$ is a quotient mapping and canonical homomorphism and is open, 
>$$p(g)\in p(U)\subseteq p\left(\bigcup\limits_{i=1}^{n}O_{i}\right)=\bigcup_{i=1}^{n}p(O_{i})$$
>
>let $\bigcup_{i} V_{i}$ be an open cover of $p(U)$, then 
>$$U\subseteq p^{-1}(p(U))\subseteq p^{-1}\left(\bigcup_{i\in I}V_{i}\right)=\bigcup_{i\in I}p^{-1}(V_{i})$$ 
>that is $\bigcup\limits_{i\in I}p^{-1}(V_{i})$ is an open covering of $U$, as $U$ is compact, we can choose a finite subcover $\bigcup\limits_{i=1}^{n}p^{-1}(V'_{i})$. Then applying the proven before, $p(U)$ is compact.
>
>
>Also it can be proven by observing that [[Continuous image of a locally compact space is locally compact]].

>[!example]+ 
>
***
#### Keywords
- [[Quotient group]],
- [[Locally compact space]],
- [[Quotient topology on a quotient group]],
- [[Compact set]],
- [[Neighborhood in topological space]],
- [[Quotient topology]],
- [[Homomorphism]],
- [[Open and closed subsets]],
- [[Open and closed mappings]],
- [[Preimage]],
- [[Covering of a set]],
- [[Cardinality of a set]]
#### Possibly related
- 
***
#### Sources: