---
Last time checked: 2024-02-09
Complete: true
aliases:
---
# Kernel and image of a mapping
***
###### tags: #Fundamental_math_objects 
***
#### Kernel
##### Ring homomorphism kernel
>[!dsn]+ Definition
>Let $f:R\to S$ be a ring homomorphism. The *kernel* of $f$ is said to be the following set
>$$\ker f:=\{r\in R:f(r)=0\}=f^{-1}(0_{S})$$

>Kernel is *not* a subring but it satisfies [[ring]] properties $(1)$-$(4)$.
>>[!proof]+
>>Let $a,b\in\ker f$. Then 
>>$$f(a+b)=f(a)+f(b)=0_{S}+0_{S}=0_{S}$$
>>so $\ker{f}$ is closed under addition. 
>>As $0_{S}=f(0_{R})$, $0_{R}\in\ker{f}$. Further
>>$$f(-a)=-f(a)=-0_{s}=0_{S}\quad\forall a\in\ker{f}$$
>>thus $\forall a\in\ker{f}$, $-a\in\ker{f}$.
>>Associativity and commutativity of addition is presented in $R$ by definition, therefore they are fulfilled on $\ker{f}\subset R$, which is closed under addition.

>[!example]+ 
>Let $n\in\mathbb{Z}$, $\phi:\mathbb{Z}\to\mathbb{Z}/n\mathbb{Z}$, $\phi(a)=[a]_{n}$ for all $a\in\mathbb{Z}$. Now as the following is equivalent
>- $\phi(a)=0$
>- $[a]_{n}=[0]_{n}$
>- $n|a$
>- $a\in n\mathbb{Z}=\{kn:n\in\mathbb{Z}\}$
>
>$\ker\phi=n\mathbb{Z}$.


#### Image
##### Ring homomorphism image
>[!dsn]+ Definition
>Let $f:R\to S$ be a ring homomorphism. Then the *image* $S'=\operatorname{im}f$ defined as 
>$$\operatorname{im}f:=\{y\in S:y=f(x),x\in R\}$$
>.^[[Lectures at KAU - Yevgen Polulyakh 6](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>By [[homomorphic image of a ring is a ring]] we know that $\operatorname{im}f$ is a subring of $S$.

>[!example]+
>Let $R=\mathbb{Z}$ and $S$ be an arbitrary ring. Then mapping $\sigma:\mathbb{Z}\to S$ defined as 
>$$\sigma(n)=n1_{S}$$
>is a homomorphism with image which consists of all multiples of neutral element.  

***
#### Keywords
- [[Function(mapping)]]
- [[Ring]],
- [[Homomorphism]],
- [[Preimage]],
- [[Set]],
- [[Set of integers]],
- [[Modular arithmetic]],
- [[Residue class]],
- [[Divisibility]],
#### Possibly related
- 
***
#### Sources: