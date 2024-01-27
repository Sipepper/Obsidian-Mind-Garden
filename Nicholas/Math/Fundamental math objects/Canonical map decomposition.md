---
Last time checked: 2023-11-23
Complete: true
aliases:
---
# Canonical map decomposition
***
###### tags: #Fundamental_math_objects 
***
>[!dsn]+ Definition
>Let $A,B$ be sets, and $f:A\to B$ some mapping. Consider a partition $\operatorname{zer}f=\{f^{-1}(b):b\in B\}$. Let $\pi:A\to A/\operatorname{zer}{f}$ be a projection map on quotient set $A/\operatorname{zer}f$. We can define a map 
>$$\begin{align}\overline{f}:A/\operatorname{zer}f&\to B\\ [x]&\mapsto f(x)\end{align}\qquad [x]\in A/\operatorname{zer}f$$
>then
>1. $\overline{f}$ is injective
>2. $f=\overline{f}\circ\pi$
>
>If we consider a restriction to $f(A)$, then map
>$$\begin{align}\tilde{f}:A&\to f(A)\\ [x]&\mapsto \overline{f}([x]) \end{align}\quad \forall[x]\in A/\operatorname{zer}f$$
>is a bijection which is called the *induced mapping*. 
>Let 
>$$\begin{align}i:f(A)&\to B\\ i(b)&=b  \end{align}\qquad \forall b\in f(A)\subset V$$
>Then the following commutative diagram
>![[Pasted image 20231123184542.png]]
>is said to be the *canonical map decomposition* of $f$.^[[Lectures at KAU - Yevgen Polulyakh](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>[!example]+ 
>Let $f:R\to S$ be a ring homomorphism. Then we have a commutative diagram
>![[Pasted image 20231124190917.png]]
>where $\pi$ is the natural projection, $i$ is the inclusion homomorphism, and $\tilde{f}$ is the induced homomorphism. Further: $\pi$ is surjective, $i$ is injective, and $\tilde{f}$ is an isomorphism of rings.^[[[Paolo Aluffi - Algebra.pdf#page=108 |Paolo Aluffi - "Algebra" p. 90]]]
>
>>[!proof]+
>>We already know that $\pi$ is a surjective homomorphism and $i$ is an injective homomorphism. To prove that the diagram is commutative, let $a$ be an arbitrary element of $R$; then
>>$$(i\circ\tilde{f}\circ\pi)(a)=i(\tilde{f}(\pi(a)))=i(\tilde{f}(a+I))=i(f(a))=f(a)$$
>>This shows that $i\circ\tilde{f}\circ\pi=f$, as needed.
>>Thus, all we have left to do is prove that the homomorphism $\tilde{f}$ is an isomorphism. To see that $\tilde{f}$ is surjective, let $s$ be an element of $f(R)$; then by definition of $f(R)$ there exists an element $a\in R$ such that $f(a)=s$, and we have
>>$$\tilde{f}(a+\ker{f})=f(a)=s$$
>>Thus shows that $s$ has a preimage in $R/\ker{f}$, proving that $\tilde{f}$ is surjective. To verify that $\tilde{f}$ is injective, suppose $\tilde{f}(a+\ker{f})=\tilde{f}(b+\ker{f})$. Then $f(a)=f(b)$, i.e., $f(b-a)=0$. This says that $b-a\in\ker{f}$, and shows that $a+\ker{f}=b+\ker{f}$, as needed.
>>We conclude that $\tilde{f}$ is an isomorphism, and we are done. 
***
#### Keywords
- [[Set]],
- [[Function(mapping)]],
- [[Partition of a set]],
- [[Preimage]],
- [[Projection map]],
- [[Quotient set]],
- [[Restriction and extension of a mapping]],
- [[Equivalence class]],
- [[Commutative diagram]],
- [[Homomorphism]],
- [[Ring]],
- [[Kernel and image of a mapping]],
- [[Isomorphism]]
#### Possibly related
- 
***
#### Sources: