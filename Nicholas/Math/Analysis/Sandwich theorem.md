---
Last time checked: 2024-02-02
Complete: true
aliases:
---
# Sandwich theorem
***
###### tags: #Analysis/Real 
***
>[!dsn]+ Theorem
>Let $\{a_{n}\}_{n\in\mathbb{N}}$ and $\{b_{n}\}_{n\in\mathbb{N}}$ be two convergent sequences of real numbers, such that
>$$\lim\limits_{n\to \infty}a_{n}=\lim\limits_{n\to \infty}b_{n}$$
>then, if there is a sequence $\{c_{n}\}_{n\in\mathbb{N}}$ such that
>$$a_{n}\le c_{n}\le b_{n}\quad\forall n\in\mathbb{N}$$
>then $\{c_{n}\}_{n\in\mathbb{N}}$ is convergent with 
>$$\lim\limits_{n\to \infty}c_{n}=\lim\limits_{n\to \infty}a_{n}=\lim\limits_{n\to \infty}b_{n}$$
>.^[https://www.youtube.com/watch?v=Y6rRSip3QN4&list=PLBh2i93oe2quABbNq4I_-hyjhW8eOdgrO&index=5]

>[!proof]+
>By monotonicity and [[properties of convergent sequences of real numbers]] the sequence $\{b_{n}-a_{n}\}_{n\in\mathbb{N}}$ converges to zero
>$$\lim\limits_{n\to \infty}(b_{n}-a_{n})=\lim\limits_{n\to \infty}a_{n}-\lim\limits_{n\to \infty}b_{n}=0$$
>Consider the sequence $d_{n}:=c_{n}-a_{n}$, then
>$$0\le d_{n}\le b_{n}-a_{n}$$
>Let $\varepsilon>0$. Then there is $N\in\mathbb{N}$ with: $\forall n\ge N:|b_{n}-a_{n}|<\varepsilon$. But
>$$|d_{n}-0|\le|b_{n}-a_{n}|<\varepsilon$$
>That is a precisely the definition of [[Convergence]], thus $d_{n}\to0$.
>Then $\{c_{n}\}_{n\in\mathbb{N}}=\{d_{n}+a_{n}\}_{n\in\mathbb{N}}$ is convergent to $a$.

>[!example]+ 
>Sequence $\{c_{n}\}_{n\in\mathbb{N}}$ is given by 
>$$c_{n}=\sqrt{n^{2}+1}-n$$
>then
>$$\begin{align}c_{n}&=\sqrt{n^{2}+1}-n\\ &=\left(\sqrt{n^{2}+1}-n\right)\cdot\frac{\sqrt{n^{2}+1}+n}{\sqrt{n^{2}+1}+n}\\ &=\frac{1}{\sqrt{n^{2}+1}+n}\\ &\le\frac{1}{n}\end{align}$$
>thus
>$$0\le c_{n}\le\frac{1}{n}\quad\forall n\in\mathbb{N}$$
>therefore by sandwich theorem $\lim\limits_{n\to \infty}c_{n}=0$
***
#### Keywords
- [[Convergence]],
- [[Sequence]],
- [[Limit]],
- [[Real line]],
- [[Monotonicity]],
- [[Absolute value]]
#### Possibly related
- 
***
#### Sources: