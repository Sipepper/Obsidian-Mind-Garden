---
Last time checked: 2023-11-14
Complete: true
aliases:
---
# Integral domain
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Definition
>Let $R$ be a commutative ring. If $0_{R}\ne1_{R}$ and for all $a,b\in R$
>$$a\cdot b=0\quad \Rightarrow \quad (a=0)\lor (b=0)$$
>Then $R$ is said to be the *integral domain*.^[[Lectures at KAU - Yevgen Polulyakh](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)] 

>[!example]+ 
>Let $n\in\mathbb{Z}$, $n\ge 0$. Then by properties of [[modular arithmetic]] $\mathbb{Z}/n\mathbb{Z}$ is an integral domain if and only if $n$ is prime.

>Let $R$ be a ring, $a\in R$. If $a$ is not a zero divisor, then $\forall b,c\in R$
>$$\begin{align}(ab=ac)&\Rightarrow(b=c)\\(ba=ca)&\Rightarrow(b=c)\\  \end{align}$$
>In other words, we can "cancel out" respective elements. 
>If $R$ is an integral domain, we can cancel any non-zero element.
>>[!proof]+
>>If $a$ is not a zero divisor, then $a\ne0$, then
>>$$(ab=ac)\Rightarrow (a(b-c)=0)\Rightarrow (b-c=0)\Rightarrow (b=c)$$
>>analogously for $ba=ca$.

***
#### Keywords
- [[Ring]],
- [[Commutative property]],
- [[Set of integers]],
- [[Modular arithmetic]],
- [[Prime number]],
- [[Zero divisor]]
#### Possibly related
- 
***
#### Sources: