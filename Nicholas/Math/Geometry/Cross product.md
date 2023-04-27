# Cross product
***
###### tags: #Geometry 
***
>[!dsn]+ Direct strict note
>A *cross product* $u\wedge v$ of two vectors $u$ and $v$(order is important) is a unique vector in $\mathbb{R}^{3}$ such that
>$$(u\wedge v)\cdot w=\det(u,b,w)\quad\forall w\in\mathbb{R}^{3}$$
>determinant is computed in default $e_{i}$ basis, then
>$$\det(u,v,w)=\begin{vmatrix}u_{1}&u_{2}&u_{3}\\ v_{1}&v_{2}&v_{3}\\ w_{1}&w_{2}&w_{3}\\ \end{vmatrix}$$ 
>By expanding the determinant by row we obtain the following
>$$u\wedge v=\begin{vmatrix}u_{2}&u_{3}\\ v_{2}&v_{3} \end{vmatrix}e_{1}-\begin{vmatrix}u_{1}&u_{3}\\ v_{1}&v_{3}\end{vmatrix}e_{2}+\begin{vmatrix}u_{1}&u_{2}\\ v_{1}&v_{2}\end{vmatrix}e_{3}$$
>because we can choose any vector $w\in\mathbb{R}^{3}$, we chosen the $(e_{1},e_{2},e_{3})$.^[Manfredo P. do Carmo - "Differential Geometry of Curves and Surfaces" p.15]

>Cross product has the following properties
>- $u\wedge v=-v\wedge u$, i.e. *anticommutativity*
>- $u\wedge v$ is linearly dependent on $v$ and $u$, i.e.
>  $$(au+bw)\wedge v=au\wedge v+bw\wedge v$$
>  $$u\wedge(av+bw)=au\wedge v+bu\wedge w$$
>- $u\wedge v=0$ if and only if $u$ and $v$ are linearly dependent.
>- $(u\wedge v)\cdot u=(u\wedge v)\cdot v=0$

***
#### Keywords
- [[Vector]],
- [[Vector space]],
- [[Euclidean space]],
- [[Determinant]],
- [[Basis of vector space]],
- [[Linear map]],
- [[Linearly dependent vectors]]
#### Possibly related
- 
***
#### Sources: