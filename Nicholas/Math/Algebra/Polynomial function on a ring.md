---
Last time checked: 2024-01-25
Complete: true
aliases:
---
# Polynomial function on a ring
***
###### tags: #Algebra 
***
>[!dsn]+ Definition
>Let $R[x]$ be a polynomial ring over $R$,
>$$\alpha=a_{0}+a_{1}x+\dots+a_{n}x^{n}\in R[x]$$
>Then mapping 
>$$\begin{align}\hat{\alpha}:R&\to R\\ c&\mapsto a_{0}+a_{1}\cdot c+\dots+a_{n}\cdot c^{n} \end{align}$$
>is said to be the *polynomial function on a ring $R$*.
^[[Lectures at KAU - Yevgen Polulyakh](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>[!example]+
>Consider $\mathbb{Z}[x]$, $\alpha=2+3x-4x^{2}$, then
>$$\hat{\alpha}(3)=2+3\cdot 3-4\cdot 9=-25$$

>Different polynomials can have same polynomial functions. 
>>[!example]+ 
>>Consider $\left(\mathbb{Z}/m\mathbb{Z}\right)[x]$, then function $\hat{\beta}$ which corresponds to
>>$$\beta=x\cdot(x-1)\cdot\ldots\cdot(x-m+1)$$
>>is always zero, i.e. $\hat{\beta}(c)=0$, $\forall c\in\mathbb{Z}/m\mathbb{Z}$

***
#### Keywords
- [[Polynomial]],
- [[Ring]],
- [[Function(mapping)]],
- [[Set of integers]],
- [[Modular arithmetic]]
#### Possibly related
- 
***
#### Sources: