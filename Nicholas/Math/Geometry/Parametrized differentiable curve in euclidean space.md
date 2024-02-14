---
Last time checked: 2024-02-11
Complete: true
aliases:
---
# Parametrized differentiable curve in euclidean space
***
###### tags: #Geometry/Differential 
***
>[!dsn]+ Definition
>Let $\alpha:I\to\mathbb{R}^{n}$ be a differentiable mapping of the interval $I=(a,b)$ to euclidean space $\mathbb{R}^{n}$. Then such mapping is said to be a *parametrized differentiable curve*.^[Manfredo P. do Carmo - "Differential Geometry of Curves and Surfaces" p.2]

>By differentiability we mean that every coordinate function $x_{i}(t)$ is a differentiable function.

>[!example]+
>Parametrized differentiable curve defined as $$\alpha(t)=(a\cos(t),a\sin(t),bt),\quad t\in\mathbb{R}$$ have trace in $\mathbb{R}^{3}$ in form of spiral with step $2\pi b$ with a cylinder $x^{2}+y^{2}=a^{2}$. Parameter $t$ is responsible for angle between $x$ axis and projection of $\alpha(t)$ on $xy$ plane 
>![[Pasted image 20220519115056.png]]

>[!example]+
>Mapping $\alpha:\mathbb{R}\to\mathbb{R}^{2}$ defined by $\alpha(t)=(t^{3},t^{2})$, $t\in\mathbb{R}$, is a parametrized differentiable curve. Note that $\alpha'(0)=(0,0)$; i.e. tangent vector is a null vector for $t=0$.
>![[Pasted image 20220519115751.png]]

>[!example]+
>Mapping $\alpha:\mathbb{R}\to\mathbb{R}^{2}$ defined by $\alpha(t)=(t^{3}-4t,t^{2}-4)$, $t\in\mathbb{R}$ is a parametrized differentiable curve. Note that $\alpha(2)=\alpha(-2)=(0,0)$ thus $\alpha$ is not a bijection.
>![[Pasted image 20220519120731.png]]

>[!example]+
>Mapping $\alpha:\mathbb{R}\to\mathbb{R}^{2}$ given by $\alpha(t)=(t,|t|)$, $t\in\mathbb{R}$ *is not* a parametrized differentiable curve because $|t|$ is not differentiable in point $t=0$
>![[Pasted image 20220519120359.png]]

>[!example]+
>Two different parametrized differentiable curves 
>$$\begin{gather}\alpha(t)=(\cos(t),\sin(t))\\ \beta(t)=(\cos(2t),\sin(2t))\end{gather}$$
>where $t\in(0-\varepsilon,2\pi+\varepsilon)$, $\varepsilon>0$, have the same trace in form of a circle $x^{2}+y^{2}=1$. Note that tangent vector of the second curve is two time longer than in the first one.
>![[Pasted image 20220519120731.png]]
***
#### Keywords
- [[Function derivative]],
- [[Interval]],
- [[Euclidean space]],
- [[Function(mapping)]],
- [[Trigonometric functions]],
- [[Tangent vector]],
- [[Vector]],
- [[Absolute value]],
#### Possibly related
- [[Curve in metric space]],
***
#### Sources: