# Convergence in real numbers
***
###### tags: #Analysis/Real
***
>[!dsn]+ Direct strict note
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
***
#### Keywords
- [[Sequence]],
- [[Real line]],
- [[Convergence in metric spaces]],
- [[Absolute value]]
#### Possibly related
- 
***
#### Sources: