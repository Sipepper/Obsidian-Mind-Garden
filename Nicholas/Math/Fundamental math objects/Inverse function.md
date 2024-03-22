---
Last time checked: 2024-02-08
Complete: false
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

>Let $f$ be a function(mapping) from set $X$ to set $Y$, then
>1. Function $f$ has an inverse if and only if it is a bijection.
>2. Let $g$ be a function from $Y$ to $X$. Then $g$ is an inverse function of $f$ if and only if $f$ is an inverse function of $g$.^[[[Sidney A. Morris - Topology without tears.pdf#page=41|Sidney A. Morris - "Topology without tears" p.41]]]
>
>>[!proof]+
>>$(1)$
>>$\Rightarrow$
>>Suppose that's not the case, i.e. there exists $x_{1}\ne x_{2}\in X$ such that $f(x_{1})=f(x_{2})$, then
>>$$g\circ f(x_{1})=g\circ f(x_{2})$$
>>therefore
>>$$x_{1}=x_{2}$$
>>which contradicts the fact that $x_{1}\ne x_{2}$. Which imply that $f$ is at least injective. Suppose that $f$ is not surjective, then there exists $y\in Y$ such that $f(x)\ne y$, $\forall x\in X$. Then as $g$ is inverse to $f$ we have
>>$$f\circ g(y)=y$$
>>which imply that $x=g(y)\in X$, which is false. Thus $f$ is indeed a bijection.
>>$\Leftarrow$
>>


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

