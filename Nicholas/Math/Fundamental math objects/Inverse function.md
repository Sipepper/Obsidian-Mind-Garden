---
Last time checked: 2024-02-08
Complete: true
aliases:
---
# Inverse function
***
###### tags: #Fundamental_math_objects 
***
>[!dsn]+ Definition
>Let $f$ be a function whose domain is the set $X$, and whose codomain is the set $Y$. Then $f$ is said to be *invertible* if there exists a function $g:Y\to X$ such that $g\circ f(x)=g(f(x))=x$ for all $x\in X$ and $f(g(y))=y$ for all $y\in Y$. The function $g$ is called the *inverse* of $f$ and denoted as $f^{-1}$.^[https://en.wikipedia.org/wiki/Inverse_function]

>If $f$ is invertible, then there is *exactly one* function $g$ satisfying this property.
>>[!proof]+
>>Suppose that $f_{1}(x)$ and $f_{2}(x)$ are inverses of function $g(x)$, i.e. $g\circ f_{1}=f_{1}\circ g=x$ and $g\circ f_{2}=f_{2}\circ g=x$. Then
>>$$g\circ f_{1}=x=g\circ f_{2}$$
>>and
>>$$f_{2}\circ g\circ f_{1}=f_{2}\circ g\circ f_{2}$$
>>$$f_{1}=f_{2}$$ 

>[!example]+
>Let $f:[0,+\infty)\to[0,+\infty)$ defined as $f(x)=x^{2}$, then the function $g(x)=\sqrt{x}$ is an inverse of $f$. If we change the domain to be $\mathbb{R}$ then function $f$ *is not* invertible.
***
#### Keywords
- [[Function(mapping)]],
- [[Domain and codomain]],
- [[Set]],
- [[Real line]]
#### Possibly related
- [[Preimage]]
***
#### Sources: