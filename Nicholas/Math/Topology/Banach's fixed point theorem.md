# Banach's fixed point theorem
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>Let $(X,d)$ be a complete metric space and $f$ is a contraction mapping of $(X,d)$ into itself. Then $f$ has exactly one fixed point.^[Sidney A. Morris - "Topology without tears" p.162]

>[!proof]
>Let $x\in X$ be some arbitrary point, let's consider the following sequence
>$$x,f(x),f^{2}(x),f^{3}(x),\dots,f^{n}(x),\dots$$
>We show that this sequence is a Cauchy sequence. Put $a=d(x,f(x))$. Because $f$ is a contraction mapping, exists $r\in(0,1)$ such that $d(f(x_{1}),f(x_{2}))\le r\cdot d(x_{1},x_{2})$,$\forall x_{1},x_{2}\in X$. 
>Replacing the $x_{2}$ with $f(x_{1})$ we get that $d(f(x),f^{2}(x))\le r\cdot d(x,f(x))=r\cdot a$, $d(f^{2}(x),f^{3}(x))\le r^{2}\cdot(x,f(x))=r^{2}\cdot a$, and by induction $\forall k\in\mathbb{N}$, $d(f^{k}(x),f^{k+1}(x))\le r^{k}\cdot d(x,f(x))=r^{k}\cdot a$.
>Let $m,n\in\mathbb{N}$ such that $n>m$. Then
>$$d(f^{m}(x),f^{n}(x))=d(f^{m}(x),f^{m}(f^{n-m}(x)))$$
>$$\begin{align}d(f^{m}(x),f^{m}(f^{n-m}(x)))&\le r^{m}d(x,f^{n-m}(x))\\ &\le r^{m}(d(x,f(x))+d(f(x),f^{2}(x))+\dots+d(f^{n-m-1}(x),f^{n-m}(x)))\\ &\le r^{m}d(x,f(x))(1+r+r^{2}+\dots+r^{n-m-1})\\ &\le \frac{r^{m}a}{1-r} \end{align}$$
>Because $r<1$, it's clear that $\set{f^{n}(x)}$ is a Cauchy sequence. Since $(X,d)$ is a complete metric space, there exists $z\in X$, such that $f^{n}(x)\to z$.
>From a [[Сжимающее отображение#6.4.3. О непрерывности сжимающего отображения|continuity of the contraction mapping]] we know that $f$ is a continuous mapping, that is
>$$f(z)=f\left(\lim_{n\to\infty}f^{n}(x)\right)=\lim_{n\to\infty}f^{n+1}(x)=z$$
>Therefore indeed $z$ is a fixed point of $f$.
>Finally, let $t$ be an arbitrary fixed point of $f$. Then
>$$d(t,z)=d(f(t),f(z))\le r\cdot d(t,z)$$
>Since $r<1$, we conclude that $d(t,z)=0$ and thus $t=z$,i.r. mapping $f$ has precisely one fixed point.

>[!example] 
>
***
#### Keywords
- [[Полное метрическое пространство]],
- [[Сжимающее отображение]],
- [[Fixed point]],
- [[Последовательность]],
- [[Последовательность Коши]],
- [[Induction]],
- [[Непрерывное отображение]],
#### Possibly related
- 
***
#### Sources: