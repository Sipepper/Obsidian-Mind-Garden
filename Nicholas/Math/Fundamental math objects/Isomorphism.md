---
Last time checked: 2024-02-07
Complete: false
aliases:
---
# Isomorphism
***
###### tags: #Algebra #Fundamental_math_objects 
***
#### Group isomorphism
>[!dsn]+ Definition
>Let $\phi:G\to G'$ be the group homomorphism, if $\phi$ is also a bijection, then $\phi$ is said to be an *isomorphism*, denoted as $G\simeq G'$.

>[!example]+ 
>

#### Ring isomorphism
>[!dsn]+ Definition
>Let $f:R\to S$ be a ring homomorphism, if $f$ is also a bijection we say that $f$ is a ring *isomorphism*. Two rings $R$ and $S$ are said to be *isomorphic*, denoted as $R\cong S$, if there exist a ring isomorphism.^[[Lectures at KAU - Yevgen Polulyakh](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>[!example]+
>A [[Complex conjugation]] $\zeta:\mathbb{C}\to\mathbb{C}$, $\zeta(z)=\overline{z}$, $\forall z\in \mathbb{C}$ is a ring isomorphism, as $\zeta$ is a homomorphism. 
>
>Moreover 
>$$\zeta\circ\zeta(a+bi)=\zeta(a-bi)=a+bi$$
>Thus $\zeta\circ\zeta=\operatorname{id}_{\mathbb{C}}$ and $\zeta^{-1}=\zeta$, that is $\zeta$ is an [[Involution]].

>If $f:R\to S$ is a ring isomorphism, then $f^{-1}:S\to R$ is also a ring isomorphism.
>>[!proof]+
>>Let $f:R\to S$ be a ring isomorphism, then $f(1_{R})=1_{S}$, thus $f^{-1}(1_{S})=1_{R}$.
>>Next let $b_{1},b_{2}\in S$, $a_{1}=f^{-1}(b_{1})$ and $a_{2}=f^{-1}(b_{2})$. Then $b_{1}=f(a_{1})$ and $b_{2}=f(a_{2})$. As $f$ is a homomorphism
>>$$f^{-1}(b_{1}+b_{2})=f^{-1}(f(a_{1})+f(a_{2}))=f^{-1}(f(a_{1}+a_{2}))=a_{1}+a_{2}=f^{-1}(b_{1})+f^{-1}(b_{2})$$
>>$$f^{-1}(b_{1}\cdot b_{2})=f^{-1}(f(a_{1})\cdot f(a_{2}))=f^{-1}(f(a_{1}\cdot a_{2}))=a_{1}\cdot a_{2}=f^{-1}(b_{1})\cdot f^{-1}(b_{2})$$

>If $R\cong S$, then
>- $R$ is an integral domain $\Leftrightarrow$ $S$ is an integral domain
>- $R$ is a field $\Leftrightarrow$ $S$ is a field.
>
>>[!proof]+
>>If for every $a,b\in R$, when $a\cdot b=0$, either $a=0_{R}$ or $b=0_{R}$, then
>>$$0_{S}=f(a\cdot b)=f(a)\cdot f(b)$$
>>as $f$ is an isomorphism, either $f(a)=0_{S}$ or $f(b)=0_{S}$, thus $S$ is also an integral domain. 
>>
>>If $R$ is a field, then every element $a\in R$ is invertible, i.e. there exist $a^{-1}\in R$ such that $a\cdot a^{-1}=a^{-1}\cdot a=1_{R}$. But
>>$$1_{S}=f(1_{R})=f(a\cdot a^{-1})=f(a)\cdot f(a^{-1})$$
>>so element $f(a^{-1})$ is an inverse of $f(a)$, and thus $f(a^{-1})=f(a)^{-1}$. 

#### Vector space isomorphism
>[!dsn] Definition
>Two vector spaces $V$ and $W$ over the same field $F$ are said to be *isomorphic* if there is a bijection $T:V\to W$ which preserves addition and scalar multiplication, that is $\forall u,v\in V$ and $c\in F$:
>$$T(u)+T(v)\quad\text{and}\quad T(cv)=cT(v)$$

>[!example] 
>

>Two vector spaces over the same field is isomorphic if and only if they has the same dimension.
>>[!proof]+
>>

***
#### Keywords
- [[Homomorphism]],
- [[Function(mapping)]],
- [[Ring]],
- [[Complex plane]],
- [[Inverse function]],
- [[Integral domain]],
- [[Unit in a ring]]
- [[Vector space]],
- [[Dimension of a vector space]],
- [[Field]],
- [[Group]],
#### Possibly related
- 
***