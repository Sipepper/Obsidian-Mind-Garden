# Gluing of continuous maps
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Let $(X,\tau)$ and $(Y,\tau_{1})$ be a topological spaces. Let $X=X_{1}\cup\dots\cup X_{n}$, with $X_{i}$ closed in $(X,\tau)$. Consider the mapping $f:X\to Y$ and it's restrictions $f_{i}=f|_{X_{i}}$. Then $f$ is continuous if and only if, every $f_{i}$ is continuous.^[В.В. Прасолов - "Элементы комбинаторной и дифференциальной топологии" p.14]

>[!proof]+
>Suppose $f$ is continuous map, then every restriction $f_{i}$ is continous by [[Restriction of continuous mapping of a subspace is continuous]].
>
>Conversely, suppose that every $f_{i}$ is continuous and $C\subset Y$ is an arbitrary closed set in $Y$. Then set $C_{i}=f_{i}^{-1}(C)=f^{-1}(C)\cap X_{i}$ is closed in $X_{i}$, that is there exist closed subset $C_{i}'$ in $X$, for which $C_{i}=C'_{i}\cap X_{i}$. Both sets $C'_{i}$ and $X_{i}$ are closed in $X$, thus set $C_{i}$ is also closed in $X$. Therefore a set $f^{-1}(C)=C_{1}\cup\dots\cup C_{n}$ is closed in $X$.

>[!example]+ 
>
***
#### Keywords
- [[Topological space]],
- [[Open and closed subsets]],
- [[Set]],
- [[Function(mapping)]],
- [[Restriction and extension of a mapping]],
- [[Continuous mapping]],
- [[Preimage]]
#### Possibly related
- 
***
#### Sources: