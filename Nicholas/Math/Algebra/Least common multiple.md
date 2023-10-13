---
Last time checked: 2023-10-11
Complete: true
aliases:
- Найменше спільне кратне
- Наименьшее общее кратное
- LCM
---
# Least common multiple
***
###### tags: #Algebra/Number_theory 
***
>[!dsn]+ Definition
>Let $a,b,c\in\mathbb{Z}$. A number $c$ is said to be *common multiple* of $a$ and $b$, if $(a|c)\land(b|c)$.
>A number $c$ is said to be *least common multiple* of $a$ and $b$ if 
>1. $c$ is a common multiple of $a$ and $b$
>2. if $d$ is a common multiple of $a$ and $b$, then $c|d$.

>Let $a,b\in\mathbb{Z}\setminus\{0\}$,
>$$a=\pm\prod\limits_{p\in\mathcal{P}}p^{\alpha_{p}},\quad b=\pm\prod\limits_{p\in\mathcal{P}}p^{\beta_{p}}$$
>Let also
>$$\operatorname{gcd}(a,b)=\prod\limits_{p\in\mathcal{P}}p^{\gamma_{p}},\quad\operatorname{lcm}(a,b)=\prod\limits_{p\in\mathcal{P}}p^{\delta_{p}}$$
>Then $$\gamma_{p}=\min\{\alpha_{p},\beta_{p}\},\quad\delta_{p}=\max\{\alpha_{p},\beta_{p}\}$$
>for all $p\in\mathcal{P}$.
>>[!proof]+
>>Let $c=\prod\limits_{p\in\mathcal{P}}p^{\varepsilon_{p}}$ is a common divisor of $a$ and $b$. As two numbers $a$ and $b$ are divisible by $c$, then $\varepsilon_{p}\le\min\{\alpha_{p},\beta_{p}\}$, $p\in\mathcal{P}$. So number 
>>$$d=\prod\limits_{p\in\mathcal{P}}p^{\gamma_{p}},\quad \gamma_{p}=\min\{\alpha_{p},\beta_{p}\},\quad p\in\mathcal{P}$$
>>divide $a$ and $b$, and $c|d$, so $d=\operatorname{gcd}(a,b)$. Analogously for $\operatorname{lcm}(a,b)$

>[!example]+ 
>Let $a=35$ and $b=14$, then $\operatorname{lcm}(a,b)=70$.
***
#### Keywords
- [[Set of integers]],
- [[Divisibility]],
- [[Fundamental theorem of arithmetic]]
#### Possibly related
- 
***
#### Sources: