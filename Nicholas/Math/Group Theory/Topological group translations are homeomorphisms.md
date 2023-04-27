# Topological group translations are homeomorphisms
***
###### tags: #Group_theory/Topological 
***
>[!dsn]+ Direct strict note
>Let $(G,\tau)$ be a topological group. For each $a\in G$, left and right translation by $a$ are homeomorphisms of $(G,\tau)$. Inversion is also a homeomorphism.^[Sidney A. Morris - "Topology without tears" p.514]

>[!proof]+
>The map $L_{a}:(G,\tau)\to(G,\tau)$ fiven by $g\mapsto ag$ is the product of the two continuous maps.
>$$(G,\tau)\to(G,\tau)\times(G,\tau)$$
>given by $g\mapsto(a,g)$, where $g\in G$, $a$ is fixed, and
>$$(G,\tau)\times(G,\tau)\to(G,\tau)$$
>given by $(x,y)\mapsto xy$, $x,y\in G$. And is therefore continuous. So left translation by any $a\in G$ is continuous. Further, $L_{a}$ has a continuous inverse, namely $L_{a^{-1}}$, since $L_{a}(L_{a^{-1}}(g))=L_{a}(a^{-1}g)=a(a^{-1}g)=g$ and $L_{a^{-1}}(L_{a}(g))=L_{a^{-1}}(ag)=a^{-1}(ag)=g$. So left translation is a homeomorphism. Similarly right translation is a homeomorphism.
>
>The map $I:(G,\tau)\to(G,\tau)$ given by $g\mapsto g^{-1}$ is continuous, by definition. Also $I$ has a continuous inverse, namely $I$ itself, as $I(I(g))=I(g^{-1})=(g^{-1})^{-1}=g$. So $I$ is also a homeomorphism. 

***
#### Keywords
- [[Topological group]],
- [[Homeomorphism]],
- [[Function(mapping)]],
- [[Cartesian product of sets]],
- [[Product topology]],
- [[Inverse function]],
- [[Continuous mapping]]
#### Possibly related
- 
***
#### Sources: