# Topological manifold
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Let $X$ be a topological space. We say that $X$ is an $n$-*dimensional topological manifold*, if $X$ is second-countable and Hausdorff, and if for every $x\in X$ there exists an $n$-dimensional chart $\Phi:U\to V$ at $x$.^[Stefan Friedl - "Algebraic topology" p.262]

>A topological manifold $X$ is *closed* if $X$ is compact with $\partial X=\emptyset$.^[Stefan Friedl - "Algebraic topology" p.262]

>[!example]+ 
>Consider the sphere $S^{n}$. Let 
>$$N:=(0,\dots,0,1)\in S^{n}$$
>be the *North Pole* and 
>$$S:=(0,\dots,0,-1)\in S^{n}$$
>be the *South Pole*. Then by using [[Stereographic projection]] namely maps
>$$\Phi_{N}:S^{n}\setminus\{N\}\to\mathbb{R}^{n}$$
>$$(x_{1},\dots,x_{n+1})\mapsto\left(\frac{x_{1}}{1-x_{n+1}},\dots,\frac{x_{n}}{1-x_{n+1}} \right)$$
>and
>$$\Phi_{N}:S^{n}\setminus\{S\}\to\mathbb{R}^{n}$$
>$$(x_{1},\dots,x_{n+1})\mapsto\left(\frac{x_{1}}{1+x_{n+1}},\dots,\frac{x_{n}}{1+x_{n+1}} \right)$$
>![[Pasted image 20230709201047.png]]
>(need to be proven)
>We see that $\Phi_{N}$ and $\Phi_{S}$ are $n$-dimensional charts of type $(i)$ that cover all of $S^{n}$. Then by [[every subset of Euclidean space is second countable and Hausdorff]] $S^{n}$ is an $n$-dimensional topological manifold.^[Stefan Friedl - "Algebraic topology" p.263]
>
>>[!Proof]+
>>




***
#### Keywords
- [[Topological space]],
- [[Second axiom of countability]],
- [[Hausdorff space]],
- [[n-dimensional chart]],
- [[Boundary of topological manifold]],
- [[Sphere]],
- [[Covering of a set]],
#### Possibly related
***
#### Sources: