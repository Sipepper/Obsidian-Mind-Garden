---
Last time checked: 2024-02-03
Complete: true
aliases:
---
# Cardinality of a set
***
###### tags: #Fundamental_math_objects 
***
#### Naive definition
>[!dsn]+ Definition
>The *cardinality*(or a *cardinal number*) of a set $X$ denoted as $|X|$ is a numerical characteristic which generalizes the notion of number of elements in a set. And used primarily to distinguish different types of infinity.
>- Set $X$ is said to be *finite* if we can construct a bijection between $X$ and $I_{n}=\{1,2,\dots,n\}$.
>- Set $X$ is said to be *countable* if we can construct a bijection between $X$ and $\mathbb{N}$.
>- If we cannot construct a bijection between $X$ and $\mathbb{N}$ we say that $X$ is *uncountable*, i.e. we cannot "list" all elements of a set.^[https://ru.wikipedia.org/wiki/Мощность_множества#Примеры]

>[!example]+ 
>- $A=\{a,b,c\}$ is finite, as $f:\mathbb{N}\to A$ defined as $(1,2,3)\mapsto(a,b,c)$ is a bijection.
>- $B=\mathbb{Z}$ is countable, as 
>  $$f(n)=\begin{cases}\frac{n}{2}& n\in2\mathbb{N}\\ -\frac{n-1}{2}& n\in2\mathbb{N}-1\end{cases}$$
>  is a bijection between $\mathbb{N}$ and $\mathbb{Z}$
>- $C=\mathbb{R}$ is uncountable, as can be seen by [[Cantor's diagonal argument]], i.e. we cannot construct a bijection between $\mathbb{N}$ and $\mathbb{R}$.
***
#### Keywords
- [[Set]],
- [[Function(mapping)]],
- [[Set of integers]],
- [[Set of natural numbers]],
- [[Real line]]
#### Possibly related
- 
***
#### Sources: