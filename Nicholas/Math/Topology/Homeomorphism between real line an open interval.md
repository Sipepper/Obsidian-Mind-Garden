# Homeomorphism between real line an open interval
***
###### tags: #Topology 
***
>[!dsn]+ 
>The space $\mathbb{R}$ with usual topology is homeomorphic to an open interval $(-1,1)$ with subspace topology, by using function $f:(-1,1)\to\mathbb{R}$ defined as
>$$f(x)=\frac{x}{1-|x|}$$.^[Sidney A. Morris - "Topology without tears" p.99]

>[!proof]+
>Consider a function
>$$g(x)=\frac{x}{1+|x|}$$
>we will show that $g\circ f=f\circ g=x$, that is $g$ is an inverse function to $f$.
>$$f\circ g=f(g(x))=f\left(\frac{x}{1+|x|}\right)=\frac{\frac{x}{1+|x|}}{1-\left|\frac{x}{1+|x|}\right|}=\frac{x}{1+|x|-|x|}=x$$
>and
>$$g\circ f=g(f(x))=g\left(\frac{x}{1-|x|}\right)=\frac{\frac{x}{1-|x|}}{1+\left|\frac{x}{1-|x|}\right|}=\frac{x}{1-|x|+|x|}=x$$
>so indeed $g=f^{-1}$. By definition of [[continuous maps between metric spaces]] we see that $f$ and $f^{-1}$ are continuous, thus $f$ is a homeomorphisms.

***
#### Keywords
- [[Real line]],
- [[Euclidean topology]],
- [[Homeomorphism]],
- [[Subspace topology]],
- [[Function(mapping)]],
- [[Interval]],
- [[Inverse function]],
- [[Absolute value]],
- [[Continuous mapping]]
#### Possibly related
- 
***
#### Sources: