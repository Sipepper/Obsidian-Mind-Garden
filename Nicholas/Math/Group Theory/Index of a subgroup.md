***
###### tags: #Group_Theory  
***
>[!dsn] Direct strict note
>By one-to-one correspondence $gH\leftrightarrow Hg^{-1}$ we can deduce that the families of left and right cosets have the same cardinality. Therefore the cardinality of the family of cosets is called an *index* of a subgroup $H$ in group $G$. Denoted as $|G:H|$.

>Every coset $gH$, $Hg$ has the same cardinality as the original group. Because we can build a bijections $h\leftrightarrow gh$, $h\leftrightarrow hg$,$\forall h\in H$.


>[!example]
>Let $G=\mathbb{Z}$ and $H=3\mathbb{Z}$, then the index of $H$ in $G$ will be equal to $3$, because there are only three cosets $0+3\mathbb{Z}$, $1+3\mathbb{Z}$, $2+3\mathbb{Z}$.

#### Multiplicative property
>[!dsn] Direct strict note
>Let $G\supset H\supset K$ be subgroups of a group $G$. Then $[G:K]=[G:H][H:K]$.^[Michael Artin - "Algebra, second edition" p.59]

>[!proof]
>Let $[G:H]=m$ and $[H:K]=n$. We can list the $m$ cosets of $H$ in $G$ by choosing the representative elements for each coset, say $g_{1}H,\dots,g_{m}H$. Then $g_{1}H\cup\dots\cup g_{m}H$ is a partition of $G$. Similarly, we choose representative elements for each coset of $K$ in $H$, obtaining a partition $H=h_{1}K\cup\dots\cup h_{n}K$. Since multiplication by $g_{i}$ is an invertible operation, $g_{i}H=g_{i}h_{1}K\cup\dots\cup g_{i}h_{n}K$ will be a partition of the coset $g_{o}H$. Putting these partitions together, $G$ is partitionaed into the $mn$ costs $g_{i}h_{j}K$.
***
#### Keywords
- [[Мощность множества]],
- [[Смежный класс]],
- [[Group]],
- [[Set of integers]],
- [[Множество]],
- [[Function(mapping)]]
#### Possibly related
- 
***
#### Sources: