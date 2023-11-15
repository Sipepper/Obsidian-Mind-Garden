# Calculating velocity vector under change of coordinates
***
###### tags: #Geometry/Differential 
***
>[!dsn] Direct strict note
>Suppose we have a coordinate system $(x_{1},\dots,x_{2})$ in some region of euclidean space, and we defined another one $(z_{1},\dots,z_{n})$. Let $z_{i}=z_{i}(t)$, $i=1,\dots,n$, define a parametrized curve in $z_{i}$ coordinates. Then in original coordinates it has the following form
>$$x_{j}=x_{j}(z(t))=h_{j}\qquad j=1,\dots,n$$
>Then the velocity vector(tangent vector) $v_{z}$ will have the following form
>$$v_{z}^{j}=\left(\frac{dz_{1}}{dt},\dots,\frac{dz_{n}}{dt}\right),\qquad j=1,\dots,n$$
>In the original coordinates it's defined as follows
>$$v_{x}^{i}=\frac{dh_{i}}{dt}=\frac{\partial x_{i}}{\partial z_{j}}\frac{dz_{j}}{dt}=\sum\limits_{j=1}^{n}\frac{\partial x_{i}}{\partial z_{j}}v_{z}^{j}$$.^[Б.А. Дубровин, С.П. Новиков, А.Т. Фоменко - "Современная геометрия" p.29]
>


>[!example] 
>
***
#### Keywords
- [[Change of coordinates]],
- [[Tangent vector]],
- [[Parametrized differentiable curve in euclidean space]],
- [[Function derivative]],
#### Possibly related
- [[Euclidean space]],
- [[Open and closed subsets]]
***
#### Sources: