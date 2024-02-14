---
Last time checked: 2024-02-10
Complete: false
aliases:
---
# Change of coordinates
***
###### tags: #Geometry #Fundamental_math_objects 
***
>[!dsn]+ Definition
>Let $x_{i}$ be default cartesian coordinates in region(open subset) of euclidean space. We can introduce new coordinate system $(z_{1},\dots,z_{n})$ by
>$$\begin{gather}x_{i}=x_{i}(z_{1},\dots,z_{n})\quad i=1,2,\dots,n\\z_{j}=z_{j}(x_{1},\dots,x_{n})\quad j=1,2,\dots,n \end{gather}$$
>that is for every point in region we can assign a default collection of cartesian coordinates as well as a new coordinates $(z_{1},\dots,z_{n})$ therefore coordinates can be expressed by each other.

>[!example]+ 
>
#### Singular points
>[!dsn]+ Definition
>A point $P=(x_{1}^{0},\dots,x_{n}^{0})$ is said to be *non-singular point* of a coordinate system $(z_{1},\dots,z_{n})$ if Jacobian matrix
>$$A=(a_{ij})=\left(\frac{\partial x_{i}}{\partial z_{j}}\right)\Bigg|_{z_{1}=z_{1}^{0},\dots,z_{n}=z_{n}^{0}}$$
>is non-singular, i.e. has a non-zero determinant at point $x_{i}(z_{1}^{0},\dots,z_{n}^{0})=x_{i}^{0}$. 

>[!example]+ 
>
#### Linear change of coordinates
>[!dsn]+ Definition
>In this case change of basis is performed by linear transformation
>$$x_{i}=\sum\limits_{j=1}^{n}a_{ij}z_{j}=a_{ij}z_{j}\quad i=1,\dots,n$$
>It can be expressed in a matrix form
>$$X=AZ,\quad X=(x_{1},\dots,x_{n})\quad Z=(z_{1},\dots,z_{n})$$
>In order to be possible to express $z$ by $x$ and vice versa $A$ must be invertible.

>[!example]+ 
>
***
#### Keywords
- [[Euclidean space]],
- [[Open and closed subsets]],
- [[Jacobian matrix]],
- [[Determinant]],
- [[Matrix]],
- [[Linear map]],
#### Possibly related
- [[n-dimensional chart]],
- [[Critical point of a function]]
***
#### Sources: