---
Last time checked: 2023-11-01
Complete: true
aliases:
---
# Chinese remainder theorem
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Theorem
>Let $m_{1},\dots,m_{r}\in\mathbb{Z}$, $m_{i}>1$, $i\in\{1,\dots,r\}$. Also let all $m_{1},\dots,m_{r}$ be relatively prime numbers(i.e. $\operatorname{gcd}(m_{i},m_{j}=1$ if $i\ne j$.). Then system of congruences
>$$\begin{cases}x\equiv b_{1}\mod{m_{1}},\\x\equiv b_{2}\mod{m_{2}},\\ \quad\vdots\\ x\equiv b_{r}\mod{m_{r}} \end{cases}$$
>has the following solution:
>$$x=\sum\limits_{i=1}^{r}b_{i}s_{i}M_{i}$$
>where
>$$M_{i}=m_{1}\cdot m_{2}\cdot\ldots\cdot \hat{m}_{i}\cdot\ldots\cdot m_{r}$$
>and
>$$s_{i}M_{i}\equiv 1\mod{m_{i}}\quad \forall i\in\{1,\dots,r\}$$
>Moreover arbitrary two solutions are equal modulo $M=m_{1}\cdot m_{2}\cdot\ldots\cdot m_{r}$.^[Lecture note from KAU, Eunege Polulyakh]

>[!proof]+
>It's obvious that $M_{i}\equiv0\mod{m_{k}}$, $\forall k\ne i$. So for all $i$ we have that
>$$\begin{align}x&=b_{1}(s_{1}M_{1})+b_{2}(s_{2}M_{2})+\ldots+b_{r}(s_{r}M_{r})\\ &\equiv b_{i}(s_{i}M_{i})\mod{m_{i}}\\ &\equiv b_{i}\mod{m_{i}} \end{align}$$
>as $s_{i}M_{i}\equiv 1\mod{m_{i}}$.
>Suppose that there is another solution $y$, i.e. $y\equiv b_{i}\mod{m_{i}}$, then $x-y\equiv0\mod{m_{i}}$.
>As all $\operatorname{gcd}(m_{i},m_{j})=1$, $i\ne j$, so $x-y\equiv 0\mod{M}$, where $M=\prod\limits_{i=1}^{r} m_{i}$.

>[!example]+ 
>Suppose we have the following system
>$$\begin{cases}3x\equiv3\mod{4}\\ 2x\equiv1\mod{5}\\ x\equiv 2\mod{7} \end{cases}$$
>then, as $[3]_{4}\cdot[3]_{4}=[1]_{4}$ and $[2]_{5}\cdot[3]_{5}=[1]_{5}$ we can obtain an equivalent system
>$$\begin{cases}x\equiv 3\cdot 3\mod4\\x\equiv1\cdot 3\mod{5} \\ x\equiv 2\mod{7}\end{cases}\quad\Leftrightarrow\quad\begin{cases}x\equiv1\mod4\\x\equiv 3\mod{5}\\ x\equiv 2\mod{7} \end{cases}$$
>Now calculate $M_{i}$
>$$\begin{align}M_{1}&=5\cdot 7=35\\ M_{2} &= 4\cdot 7=28\\ M_{3}&=4\cdot 5=20\\ M&=4\cdot5\cdot 7=140 \end{align}$$
>and $s_{i}$
>$$\begin{align}35\cdot s_{1}\equiv 1\mod{4}\qquad 3\cdot s_{1}\mod{4}\qquad s_{1}=3\\ 28\cdot s_{2}\equiv 1\mod{5}\qquad 3\cdot s_{2}\mod{5}\qquad s_{2}=2\\20\cdot s_{3}\equiv 1\mod{7}\qquad 6\cdot s_{3}\mod{7}\qquad s_{3}=6\\\end{align}$$
>So
>
>$$x\equiv 93\mod{140}$$
***
#### Keywords
- [[Set of integers]],
- [[Congruent integers]],
- [[Relatively prime numbers]],
- [[Greatest common divisor]],
- [[Modular arithmetic]],
- [[Residue class]]
#### Possibly related
- 
***
#### Sources: