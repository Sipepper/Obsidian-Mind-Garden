# Sphere
***
###### tags: #Geometry #Fundamental_math_objects 
***
#### As a submanifold
>[!dsn] Direct strict note
>The *unit* $n$*-sphere* is
>$$\mathbb{S}^{n}=\{x\in\mathbb{R}^{n+1}:|x|=1 \}$$
>where $|x|=\left(\sum\limits_{i=1}^{n+1}x_{i}^{2}\right)^{1/2}$. We can introduce local coordinates in $\mathbb{S}^{n}$ as follows. For $j=1,\dots,n+1$ define open hemispheres
>$$U_{2j-1}=\{x\in\mathbb{S}^{n}:x_{j}>0\}$$
>$$U_{2j}=\{x\in\mathbb{S}^{n}:x_{j}<0\}$$
>For $i=1,\dots,2(n+1)$ define maps
>$$\phi_{i}:U_{i}\to\mathbb{R}^{n}$$
>$$\phi_{i}(x)=(x_{1},\dots,\hat{x}_{j},\dots,x_{n+1})\quad\text{if}\quad i=2j-1\text{ or }2j$$
>this means the $n$-tuple obtained from $x$ by deleting the $j$-th coordinate.^[Morris W. Hirsch - Differential Topology p.8-9]

>$\phi_{i}$ maps $U_{i}$ homeomorphically onto the open $n$-disk
>$$B=\{y\in\mathbb{R}^{n}:|y|<1 \}$$
>and $\phi_{i}^{-1}:B\to\mathbb{R}^{n+1}$ is analytic.
>>[!proof]+
>>

>Each $(\phi_{i},U_{i})$ is called a *chart* for $\mathbb{S}^{n}$; the set of all $(\phi_{i},U_{i})$ is an *atlas*. In terms of this atlas we say a map $f:S^{m}\to\mathbb{R}^{k}$ is *differentiable of class $C^{r}$* is case each composite map
>$$f\circ\phi_{i}^{-1}:B\to\mathbb{R}^{k}$$
>is $C^{r}$.

***
#### Keywords
- [[Euclidean space]],
- [[Smooth manifold]],
- [[Local coordinates]],
- [[Open and closed subsets]],
- [[Function(mapping)]],
- [[Homeomorphism]],
- [[Inverse function]],
- [[Function derivative]],
- [[Smooth function]],
- [[Analytic function]],
- [[Set]]
#### Possibly related
- 
***
#### Sources: