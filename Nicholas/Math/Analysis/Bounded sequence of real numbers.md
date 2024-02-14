---
Last time checked: 2024-02-02
Complete: true
aliases:
---
# Bounded sequence of real numbers
***
###### tags: #Analysis/Real 
***
>[!dsn]+ Definition
>A sequence of real numbers $\{a_{n}\}_{n\in\mathbb{N}}$ is called *bounded* if
>$$\exists C\in\mathbb{R}\quad\forall n\in\mathbb{N}:\quad|a_{n}|\le C$$
>Otherwise, the sequence is called *unbounded*.^[https://youtu.be/k-Wm6gJYfrw]

>Every convergent sequence $\{a_{n}\}_{n\in\mathbb{N}}$ is bounded. But not every bounded.
>>[!proof]+
>>There is $a\in\mathbb{R}$ such that for every $\varepsilon$-neighborhood of $a$ there are infinitely many members of $\{a_{n}\}$. So we can define constant $C$ as follows
>>$$C:=\max\left\{|a_{1}|,|a_{2}|,|a_{3}|,\dots,|a_{N-1}|,|a|+\varepsilon\right\}$$
>>And $\{(-1)^{n}\}$ is an example of bounded but *not* convergent sequence, with $C$ can be equal to $2$.

>[!example]+ 
>$\{\sin(n)\}$ is a bounded sequence, as $-1<\sin(x)<1$ for all $x\in\mathbb{R}$. 
***
#### Keywords
- [[Sequence]],
- [[Real line]],
- [[Bounded set]],
- [[Absolute value]],
- [[Convergence]],
- [[Neighborhood in topological space]],
- [[Trigonometric functions]]
#### Possibly related
- 
***
#### Sources: