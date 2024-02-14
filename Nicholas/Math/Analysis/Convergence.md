---
Last time checked: 2024-01-27
Complete: false
aliases:
---
# Convergence 
***
###### tags: #Topology #Fundamental_math_objects 
***
#### In TVS
>[!dsn]+ Definition
>Let $U$ be a topological vector space. A sequence $\{u_{n}\}$ *converges* to an element $u_{0}\in U$, if for every neighbourhood $V$ of $u_{0}$, there exists a natural number $N$ suh that
>$$u_{n}\in V\quad\forall n\ge N$$^[[[Fabio Silva Botelho - Functional Analysis and Applied Optimization in Banach Spaces.pdf#page= 27|Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.9]]]

>[!example]+ 
>

#### In real numbers
>[!dsn]+ Definition
>A sequence $\{a_{n}\}_{n\in\mathbb{N}}$ is called *convergent* to $a\in\mathbb{R}$ if
>$$\forall\varepsilon>0\quad\exists N\in\mathbb{N}\quad\forall n\ge N:|a_{n}-a|<\varepsilon$$
>.^[https://www.youtube.com/watch?v=1SguKALJji8&list=PLBh2i93oe2quABbNq4I_-hyjhW8eOdgrO&index=2]

>In another words $a_{n}$ get's closer and closer to $a$.

>If there is *no* such $a\in\mathbb{R}$, we call the sequence $\{a_{n}\}_{n\in\mathbb{N}}$ *divergent*.

>[!example]+ 
>$\{a_{n}\}_{n\in\mathbb{N}}=\left\{\frac{1}{n} \right\}_{n\in\mathbb{N}}$ is convergent to $0\in\mathbb{R}$.
>>[!proof]+
>>Let $\varepsilon>0$. We choose $N\in\mathbb{N}$ such that $N\cdot\varepsilon>1$ which is possible by [[Archimedean property]]. Then for $n\ge N$, we have:
>>$$|a_{n}-0|=|a_{n}|=\frac{1}{n}\le\frac{1}{N}<\varepsilon$$

>[!example]+
>$\{a_{n}\}_{n\in\mathbb{N}}=\{(-1)^{n}\}_{n\in\mathbb{N}}$ is divergent.
>>[!proof]+
>>Assume the sequence $\{a_{n}\}_{n\in\mathbb{N}}$ is convergent to $a\in\mathbb{R}$.
>>$$\forall\varepsilon>0\quad\exists N\in\mathbb{N}\quad\forall n\ge N:|a_{n}-a|<\varepsilon$$
>>choose $\varepsilon=1$, then 
>>$$|a_{N}-a|<\varepsilon$$
>>and
>>$$|a_{N+1}-a|<\varepsilon$$
>>Hence
>>$$|1-a|<\varepsilon\quad\text{and}\quad|(-1)-a|<\varepsilon$$
>>Note that
>>$$|1-a|+|(-1)-a|<2$$
>>Now
>>$$2=|1-(-1)|=|1-a+a-(-1)|\le |1-a|+|a-(-1)|<2$$
>>So we got a contradiction $2<2$, so the assumption is false. Thus sequence is indeed divergent.

#### In metric spaces
>[!dsn]+ Definition
>Let $(X,d)$ be a metric space and $\set{x_{n}}$ a sequence of points in $X$. Then the sequence is said to *converge to* $x\in X$ if $\forall\varepsilon>0$ there exists an integer $n_{0}$ such that $\forall n\ge n_{0}$, $d(x,x_{n})<\varepsilon$. This is denoted by $x_{n}\to x$.^[[[Sidney A. Morris - Topology without tears.pdf#page=144|Sidney A. Morris - "Topology without tears" p.144]]]
>
>The sequence $\set{y_{n}}$ of points in $(X,d)$ is said to be *convergent* if there exists a point $y\in X$ such that $y_{n}\to y$.

>Let $\set{x_{n}}$ be a sequence of points in a metric space $(X,d)$. Further let $x$ and $y$ be points in $(X,d)$ such that $x_{n}\to x$ and $x_{n}\to y$. Then $x=y$.^[[[Sidney A. Morris - Topology without tears.pdf#page=141|Sidney A. Morris - "Topology without tears" p.141]]]
>>[!proof]+
>>As [[Metric space is a Hausdorff space]] and [[Every convergent sequence of Hausdorff space has a unique limit]] indeed if $x_{n}\to x$ and $x_{n}\to y$, then $x=y$.

>[!example]+
>
***
#### Keywords
- [[Topological vector space]],
- [[Sequence]],
- [[Neighborhood in topological space]],
- [[Set of natural numbers]],
- [[Real line]],
- [[Absolute value]],
- [[Metric space]]
#### Possibly related
- 
***
#### Sources: