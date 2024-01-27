---
Last time checked: 2024-01-25
Complete: true
aliases:
  - Invertible element in ring
---
# Unit in a ring
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Definition
>Let $R$ be a ring, and $a\in R$. Then if there exists an element $b\in R$ such that $ab=ba=1_{R}$, then $a$ is called a *unit* (or *invertible*) in $R$. Multiplicative inverse to $a$ is denoted as $a^{-1}$.

>The set of all units is denoted as $R^{\times}$, i.e.
>$$R^{\times}=\{a\in R:\exists a^{-1}\}$$

>Inverses are unique.
>>[!proof]+
>>Let $a\in R$, and suppose that there exists $b,b'\in R$, such that
>>$$\begin{cases}ab=ba=1_{R}\\ab'=b'a=1_{R} \end{cases}$$
>>Then
>>$$ab=1_{R}=ab'\Rightarrow b'ab=b'ab'\Rightarrow b=b'$$

>[!example]+ 
>Let $R=\mathbb{Z}$, then $\mathbb{Z}^{\times}=\{\pm 1\}$.
>>[!proof]+
>>Consider an equation
>>$$ab=1$$
>>If $|a|>1$, then $|b|<1$, thus either $b=0$, or $0<|b|<1$. Suppose that $0<|b|<1$, but then $b\notin\mathbb{Z}$, i.e. $b$.
>>Now let $a=1$, then $b=1$, and if $a=-1$, $b=-1$.
***
#### Keywords
- [[Ring]],
- [[Set]],
- [[Set of integers]],
- [[Absolute value]]
#### Possibly related
- 
***
#### Sources: