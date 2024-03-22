---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Product of Hausdorff spaces is Hausdorff
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>Let $(X,\tau_{1})$ and $(Y,\tau_{2})$ be a Hausdorff spaces. Then $(X\times Y,\tau)$ is a Hausdorff space.

>[!proof]+
>Let $x_{1}\ne x_{2}\in X$ and $y_{1}\ne y_{2}\in Y$, as $(X,\tau_{1})$ and $(Y,\tau_{2})$ are Hausdorff there exists an open neighborhoods $U_{1}\cap U_{2}=\emptyset$ and $V_{1}\cap V_{2}=\emptyset$ of points $x_{1},x_{2}$ and $y_{1},y_{2}$ respectively.
>Then
>$$U_{1}\times V_{1}\quad U_{2}\times V_{2}$$
>are neighborhoods in $X\times Y$ of points $(x_{1},y_{1})$ and $(x_{2},y_{2})$ respectively. But
>$$(U_{1}\times V_{1})\cap(U_{2}\times V_{2})=(U_{1}\cap U_{2})\times(V_{1}\cap V_{2})=\emptyset$$
>as points $x_{i}$ and $y_{j}$ were chosen arbitrarily, indeed for any two points $(x_{1},y_{1})$ and $(x_{2},y_{2})$ there exists a disjoint open neighborhoods. Thus $X\times Y$ is Hausdorff. 

>[!example]+ 
>
***
#### Keywords
- [[Hausdorff space]],
- [[Product topology]],
- [[Neighborhood in topological space]],
- [[Set]]
#### Possibly related
- 
***
#### Sources: