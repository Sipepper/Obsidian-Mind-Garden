# Properties of convergent sequences of real numbers
***
###### tags: #Analysis/Real 
***
>[!dsn]+ Direct strict note
>Let $\{a_{n}\}_{n\in\mathbb{N}}$ and $\{b_{n}\}_{n\in\mathbb{N}}$ be a convergent sequences. Then
>1. $$\lim\limits_{n\to\infty}(a_{n}+b_{n})=\lim\limits_{n\to\infty}a_{n}+ \lim\limits_{n\to \infty}b_{n}$$
>2. $$\lim\limits_{n\to \infty}(a_{n}\cdot b_{n})=\lim\limits_{n\to\infty}a_{n}\cdot \lim\limits_{n\to\infty}b_{n}$$
>3. $$\lim\limits_{n\to\infty}\left(\frac{a_{n}}{b_{n}}\right)=\frac{\lim\limits_{n\to\infty}a_{n}}{\lim\limits_{n\to\infty}b_{n}}\quad b_{n}\ne0,\forall n\in\mathbb{N}$$

>Also if $a_{n}\le b_{n}$, for all $n\in\mathbb{N}$, then
>$$\lim\limits_{n\to \infty}a_{n}\le\lim\limits_{n\to \infty}b_{n}$$
>such property is called *monotonicity*.^[https://www.youtube.com/watch?v=Y6rRSip3QN4&list=PLBh2i93oe2quABbNq4I_-hyjhW8eOdgrO&index=5]

>[!proof]+
>1. Let $\{a_{n}\}$ and $\{b_{n}\}$ be convergent sequences with limits $a$ and $b$ respectively, then
>   $$\forall\varepsilon>0\quad\exists N_{1}\in\mathbb{N}:\forall n\ge N_{1}\quad |a_{n}-a|<\varepsilon/2$$
>   and
>   $$\forall\varepsilon>0\quad\exists N_{2}\in\mathbb{N}:\forall n\ge N_{2}\quad |b_{n}-b|<\varepsilon/2$$
>   consider the $N=\max\{N_{1},N_{2}\}$
>   Now
>   $$\forall\varepsilon>0\quad\exists M\in\mathbb{N}:\forall n\ge M\quad |a_{n}+b_{n}-(a+b)|<\varepsilon$$
>   and
>   $$\begin{align}|a_{n}+b_{n}-(a+b)|&=|a_{n}-a+b_{n}-b|\\ &\le|a_{n}-a|+|b_{n}-b|\\ &<\varepsilon/2+\varepsilon/2=\varepsilon \end{align}$$
>   thus $a+b$ is a limit for sequence $\{a_{n}+b_{n}\}$
>   

>[!example]+ 
>Let 
>$$\begin{align}c_{n}&=\frac{2n^{2}+5n-1}{-5n^{2}+n+1}\\ &=\frac{\frac{1}{n^{2}}}{\frac{1}{n^{2}}}\cdot \frac{2n^{2}+5n-1}{-5n^{2}+n+1}\\ &=\frac{2+\frac{5}{n}-\frac{1}{n^{2}}}{-5+\frac{1}{n}+\frac{1}{n^{2}}} \end{align}$$
>We know that $\lim\limits_{n\to\infty}\frac{1}{n}=0$ and by $(2)$ $\lim\limits_{n\to\infty}\frac{1}{n}\cdot \frac{1}{n}=0\cdot0$, thus
>$$\lim\limits_{n\to\infty}c_{n}=-\frac{2}{5}$$
***
#### Keywords
- [[Convergence in real numbers]],
- [[Sequence]],
- [[Limit]],
- [[Monotonicity]]
#### Possibly related
- 
***
#### Sources: