---
Last time checked: 2024-03-13
Complete: true
aliases:
---
# Homeomorphism of closure is a closure of homeomorphism image
***
###### tags: #Topology 
***
>[!dsn]+ Proposition
>Let $X$ and $Y$ be topological spaces, let $f:X\to Y$ be a homeomorphism, and let $A\subseteq X$. Then $f(\overline{A})=\overline{f(A)}$.^[http://mathonline.wikidot.com/the-closure-of-a-set-under-homeomorphisms-on-topological-spa]


>[!proof]+
>Let $x\in f(\overline{A})$. Then $f^{-1}(x)\in\overline{A}$, i.e. $f^{-1}(x)$ is in the closure of $A$. So $f^{-1}(x)\in A\cup A'$. If $f^{-1}(x)\in A$ then $x\in f(A)$ and $f(A)\subseteq\overline{f(A)}$, so $x\in\overline{f(A)}$. If $f^{-1}(x)\in A'$ then $f^{-1}(x)$ is an accumulation point of $A$ so for every open set $U$ of $X$ with $f^{-1}(x)\in U$ we have that:
>$$A\cap\left(U\setminus\set{f^{-1}(x)}\right)\ne\emptyset$$
>So we have that:
>$$f\left(A\cap\left(U\setminus\set{f^{-1}(x)}\right)\right)=f(A)\cap f(U)\setminus\set{x}$$
>Since $f$ is a homeomorphism we have that since $U$ is an open set in $X$ then $f(U)$ is an open set in $Y$. But every open set on $Y$ is of the form $f(U)$ since $f$ is a bijection. Therefore $x$ is an accumulation point of $f(A)$ so $x\in(f(A))'$. But $(f(A))'\subseteq f(A)\cup(f(A))'=\overline{f(A)}$. Hence $x\in\overline{f(A)}$ which shows that:
>$$f(\overline{A})\subseteq\overline{f(A)}$$
>Now let $x\in\overline{f(A)}$. Then $x$ is an accumulation point of $f(A)$, so $x\in f(A)\cup(f(A))'$. If $x\in f(A)$ then $f^{-1}(x)\in A$. But $A\subseteq A\cup A'=\overline{A}$ so $f^{-1}(x)\in\overline{A}$ and $x\in f(\overline{A})$. If $x\in(f(A))'$ then $x$ is an accumulation point of $f(A)$ and so for every open set $V$ of $Y$ with $x\in V$ we have that:
>$$f(A)\cap V\setminus\set{x}\ne\emptyset$$
>So then:
>$$A\cap f^{-1}(V)\setminus\set{f^{-1}(x)}$$
>Since $f$ is a homemorphism and $V$ is an open set in $Y$ we have that $f^{-1}(V)$ is an open set in $X$. But every open set in $X$ is of the form $f^{-1}(V)$ since $f$ is a bijection. Therefore $f^{-1}(x)$ is an accumulation point of $A$ so $f^{-1}(x)\in f(A')$. But $f(A')\subseteq f(A\cup A')=f(\overline{A})$. Hence $x\in f(\overline{A})$ and so:
>$$\overline{f(A)}\subseteq f(\overline{A})$$
>We therefore conclude that $f(\overline{A})=\overline{f(A)}$.

>[!example]+ 
>Let $(G,\tau)$ be a topological group, let $H$ be a subgroup of $G$, then as [[topological group translations are homeomorphisms]] $a\overline{H}=\overline{aH}$.


***
#### Keywords
- [[Topological space]],
- [[Homeomorphism]],
- [[Closure of a set]],
- [[Kernel and image of a mapping]],
- [[Set]],
- [[Preimage]],
- [[Limit point in topological space]],
- [[Function(mapping)]],
- [[Open and closed subsets]],
- [[Topological group]],
#### Possibly related
- 
***
#### Sources: