---
Last time checked: 2024-02-14
Complete: true
aliases:
---
# Lipschitz continuous function
***
###### tags: #Geometry 
***
>[!dsn]+ Definition
>Let $(X,d_{X})$ and $(Y,d_{Y})$ be metric spaces. A function $f:X\to Y$ is said to be *Lipschitz continuous* if there exists a real constant $K\ge0$ such that, for all $x_{1},x_{2}\in X$, such that
>$$d_{Y}(f(x_{1}),f(x_{2}))\le Kd_{X}(x_{1},x_{2})$$
>Any such $K$ is referred as a *Lipschitz constant* for the function $f$.^[https://en.wikipedia.org/wiki/Lipschitz_continuity]


>![[Lipschitz_Visualisierung.gif]]
>For a Lipschitz continuous function, there exists a double cone (white) whose origin can be moved along the graph so that the whole graph always stays outside the doulbe cone.

>As we can see Lipschitz continous function is Holder continuous function of exponent $1$.

>If for a real number $K\ge1$ the following holds
>$$\frac{1}{K}d_{X}(x_{1},x_{2})\le d_{Y}(f(x_{1}),f(x_{2}))\le Kd_{X}(x_{1},x_{2})\quad\forall x_{1},x_{2}\in X$$
>then $f$ is called *$K$-bi-Lipschitz*. 

>[!example]+ 
>The function $f(x)=\sqrt{x^{2}+5}$ defined for all real numbers is Lipschitz continuous with the Lipschitz constant $K=1$.
***
#### Keywords
- [[Metric space]],
- [[Function(mapping)]],
- [[Real line]],
- [[Holder continuous function]],
#### Possibly related
- 
***
#### Sources: