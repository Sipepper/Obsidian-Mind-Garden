---
Last time checked: 2024-01-26
Complete: true
aliases:
---
# Finite integral domain is a field
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Proposition
>Let $R$ be a finite integral domain. Then $R$ is a field.^[[Lectures at KAU - Yevgen Polulyakh](https://drive.google.com/drive/folders/1OBF4iFXhiyJQ2lVaDTRnDEnyDf6hImIg)]

>[!proof]+
>By definition $0_{R}\ne 1_{R}$. Let $a\in R$, $a\ne 0$. Consider a map
>$$\begin{align}f_{a}:R&\to R\\ r&\mapsto a\cdot r \end{align}\quad \forall r\in R$$
>A map $f_{a}$ is injective. Indeed if $f_{a}(r)=f_{a}(s)$ for some $r,s\in R$, then
>$$a\cdot r=a\cdot s\Rightarrow r=s$$
>then as $R$ is finite and $f_{a}$ is injective $f$ is a bijection. Thus there exists $b\in R$, such that 
>$$a\cdot b=\underbrace{1_{R}}_{f_{a}(b)}=1_{R}=b\cdot a\Rightarrow a\in R^{\times}$$ 

>[!example]+ 
>Let $R=\mathbb{Z}/3\mathbb{Z}$, then consider a map $f_{2}:\mathbb{Z}/3\mathbb{Z}\to\mathbb{Z}/3\mathbb{Z}$, then
>$$\begin{align}[1]_{n} \cdot [2]_{n}&=[2]_{n}\\ [2]_{n}\cdot [2]_{n}&=[1]_{n}\\  \end{align}$$
>thus $[2]_{3}$ is a unit with inverse being itself. 
***
#### Keywords
- [[Cardinality of a set]],
- [[Integral domain]],
- [[Field]],
- [[Function(mapping)]],
- [[Residue class]],
- [[Modular arithmetic]],
- [[Unit in a ring]],
- [[Group of invertible elements in a ring]]
#### Possibly related
- 
***
#### Sources: