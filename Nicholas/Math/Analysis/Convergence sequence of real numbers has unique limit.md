# Convergence sequence of real numbers has unique limit
***
###### tags: #Analysis/Real 
***
>[!dsn]+ Direct strict note
>Let $\{a_{n}\}_{n\in\mathbb{N}}$ be a convergent sequence of real numbers. Then there is only one limit $a\in\mathbb{R}$.^[https://youtu.be/k-Wm6gJYfrw]

>[!proof]+
>Assume there are two limits $a\ne\tilde{a}$. Thus $|a-\tilde{a}|>0$. But it leads to contradiction, as we can choose suitable $\varepsilon_{1}$ and $\varepsilon_{2}$ such that
>$$(a-\varepsilon_{1},a+\varepsilon_{1})\cap (\tilde{a}-\varepsilon_{2},\tilde{a}+\varepsilon_{2})=\emptyset$$
>so there is not such $N$ after which every member of $\{a_{n}\}$ will lie inside such $\varepsilon$-neighborhoods simultaneously.
>
>And more formally
>$$\exists N\in\mathbb{N}\quad\forall n\ge N:\quad|a_{n}-a|<\varepsilon$$
>and 
>$$\exists \tilde{N}\in\mathbb{N}\quad\forall n\ge \tilde{N}:\quad|a_{n}-\tilde{a}|<\varepsilon$$
>Therefore, for $n\ge\max(N,\tilde{N})$
>$$\begin{align}|a-\tilde{a}|&=|a-a_{n}+a_{n}-\tilde{a}|\\ &\le|a-a_{n}|+|a_{n}-\tilde{a}|\\ &\le\varepsilon+\varepsilon\end{align}$$
>consider $\varepsilon:=\frac{1}{4}|a-\tilde{a}|$
>$$|a-\tilde{a}|<\frac{1}{2}|a-\tilde{a}|$$
>which is a contradiction.

***
#### Keywords
- [[Sequence]],
- [[Convergence in real numbers]],
- [[Limit]],
- [[Real line]],
- [[Absolute value]],
- [[Epsilon neighborhood]]
#### Possibly related
- 
***
#### Sources: