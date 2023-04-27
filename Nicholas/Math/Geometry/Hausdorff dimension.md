# Hausdorff dimension
***
###### tags: #Fundamental_math_objects #Geometry/Fractal 
***
>[!dsn]+ Direct strict note
>The *Hausdorff dimension* $\dim_{H}F$ of a set $F$, is
>$$\dim_{H}F=\inf\{s\ge0:\mathcal{H}^{s}(F)=0 \}=\sup\{s:\mathcal{H}^{s}(F)=\infty\}$$
>i.e. there is a critical point at which $\mathcal{H}^{s}(F)$ "jumps" from $\infty$ to zero.^[Kenneth Falconer - "Fractal Geometry 2e." p.32]
>![[Pasted image 20220816223542.png]]




#### Properties
1. *Monotonicity*
   Let $E\subset F$, then $\dim_{H}E\le\dim_{H}F$. It follows from measure property that $\mathcal{H}^{s}(E)\le\mathcal{H}^{s}(F)$, $\forall s$.
2. *Countable stability*
   Let $F_{1},F_{2},\dots$ be a sequence of sets, then 
   $$\dim_{H}\bigcup_{i=1}^{\infty}F_{i}=\sup_{1\le i<\infty}\{\dim_{H}F_{i}\}$$
   >[!proof]+
   >
   
3. *Countable sets*
   Let $F$ be a countable set, then $\dim_{H}F=0$.
   >[!proof]+
   >
   
4. *Open sets*
   Let $F\subset\mathbb{R}^{n}$ be an open set, then $\dim_{H}F=n$.
   >[!proof]+
   >
   
5. *Smooth manifolds*
   Let $F$ be a smooth $m$-dimensional submanifold of $\mathbb{R}^{n}$, then $\dim_{H}F=m$. In particular smooth curves have dimension $1$ and smooth surfaces have dimension $2$.
   >[!proof]+
   >

>[!example]+ 
>
***
#### Keywords
- [[Set]],
- [[Hausdorff measure]],
- [[Supremum and infinum]],
- [[Cardinality of a set]],
- [[Open and closed subsets]],
- [[Smooth manifold]]
#### Possibly related
- 
***
#### Sources: