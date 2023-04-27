# Finite product of connected spaces is connected
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Let $(X_{1},\tau_{1}),(X_{2},\tau_{2}),\dots,(X_{n},\tau_{n})$ be topological spaces. Then $\prod_{i=1}^{n}(X_{i},\tau_{i})$ is connected if and only if each $(X_{i},\tau_{i})$ is connected.^[Sidney A. Morris - "Topology without tears" p.214] 

>[!proof]+
>To show that the product of a finite number of connected spaces is connected, it suffices to prove that the product of any two connected spaces is connected.
>
>Let $(X,\tau)$ and $(Y,\tau_{1})$ be connected spaces and $(x_{0},y_{0})$ any point in the product space $(X\times Y,\tau_{2})$. Let $(x_{1},y_{1})$ be any other point in $X\times Y$. Then the subspace $\set{x_{0}}\times Y$ of $(X\times y,\tau)$ is homeomorphic to the connected space $(Y,\tau_{1})$ and so is connected.
>
>Similarly the subspace $X\times\set{y_{1}}$ is connected. Furthermore, $(x_{0},y_{1})$ lies in the connected space $\set{x_{0}}\times Y$, so $C_{X\times Y}((x_{0},y_{1}))\supseteq\set{x_{0}}\times Y\ni(x_{0},y_{0})$, while $(x_{0},y_{1})\in X\times\set{y_{1}}$, and so $C_{X\times Y}((x_{0},y_{1}))\supseteq X\times\set{y_{1}}\ni(x_{1},y_{1})$.
>
>Thus $(x_{0},y_{0})$ and $(x_{1},y_{1})$ lie in the connected set $C_{X\times Y}((x_{0},y_{1}))$, and so by [[Component of topological space#Equality of components]], $C_{X\times Y}((x_{0},y_{0}))=C_{X\times Y}((x_{1},y_{1}))$. In particular, $(x_{1},y_{1})\in C_{X\times Y}((x_{0},y_{0}))$. As $(x_{1},y_{1})$ was an arbitrary point in $X\times Y$, we have that $C_{X\times Y}((x_{0},y_{0}))=X\times Y$. Hence $(X\times Y,\tau_{2})$ is connected.
>
>Conversely if $\prod_{i=1}^{n}(X_{i},\tau_{i})$ is connected then by [[Projection map in product spaces#8.2.5. Конечный случай|projection of finite product of topological spaces]] and [[Connected topological space#Continuous surjective mappings preserve connectedness|continuous surjective mappings preserve connectedness]] if follows that each $(X_{i},\tau_{i})$ is connected.

>[!example]+ 
>
***
#### Keywords
- [[Topological space]],
- [[Connected topological space]],
- [[Product topology]],
- [[Homeomorphism]],
- [[Component of topological space]]
#### Possibly related
- 
***
#### Sources:
