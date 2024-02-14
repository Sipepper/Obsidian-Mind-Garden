---
Last time checked: 2024-01-27
Complete: false
aliases:
---
# Every element of Hilbert space can be expressed as unique sum of element from closed subspace and orthogonal to it
***
###### tags: #Analysis/Functional 
***
>[!dsn]+ Proposition
>Let $H$ be a Hilbert space and $M$ is a closed subspace of $H$ and $u\in H$. Then there exists a unique $m_{0}\in M$ such that 
>$$\|u-m_{0}\|_{H}=\min_{m\in M}\{\|u-m\|_{H}\}$$
>Futhermore exist element $n_{0}=u-m_{0}\in M^{\perp}$ such that $u=m_{0}+n_{0}$, i.e. $U=M\oplus M^{\perp}$ is unique.^[[[Fabio Silva Botelho - Functional Analysis and Applied Optimization in Banach Spaces.pdf#page= 50|Fabio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.32]]]

>[!proof]+
>Define $d$ as $d=\inf\limits_{m\in M}\{\|u-m\|_{H}\}$. Let $\{m_{i}\}\subset M$ is a sequence such that $\|u-m_{i}\|_{H}\to d$, as $i\to\infty$. Then by [[Parallelogram law]] we obtain that
>$$\begin{align}\|m_{i}-m_{j}\|_{H}^{2}&=\|m_{i}-u-(m_{j}-u)\|_{H}^{2}\\ &=2\|m_{i}-u\|_{H}^{2}+2\|m_{j}-u\|_{H}^{2}\\ &\quad-2\|-2u+m_{i}+m_{j}\|_{H}^{2}\\ &=2\|m_{i}-u\|_{H}^{2}+2\|m_{j}-u\|_{H}^{2}\\ &\quad-4\|-u+(m_{i}+m_{j})/2\|_{H}^{2}\\ &\to2d^{2}+2d^{2}-4d^{2}=0\quad\text{as}\quad i,j\to+\infty \end{align}$$
>Thus $\{m_{i}\}\subset M$ is a Cauchy sequence. Since $M$ is closed, there exists $m_{0}\in M$ such that $m_{i}\to m_{0}$ as $i\to+\infty$, so that
>$$\|u-m_{i}\|_{H}\to\|u-m_{0}\|_{H}=d$$
>Define $n_{0}=u-m_{0}$, we now prove that $n_{0}\in M^\perp$.
>Pick $m\in M$ and $t\in\mathbb{R}$, and thus we have
>$$\begin{align}d^{2}&\le\|u-(m_{0}-tm)\|_{H}^{2}\\ &=\|n_{0}+tm\|_{H}^{2}\\ &=\|n_{0}\|_{H}^{2}+2(n_{0},m)_{H}t+\|m\|_{H}^{2}t^{2} \end{align}$$
>Since $\|n_{0}\|_{H}^{2}=\|u-m_{0}\|_{H}^{2}=d^{2}$, we obtain
>$$2(n_{0},m)_{H}t+\|m\|_{H}^{2}t^{2}\ge0\quad\forall t\in\mathbb{R}$$
>so that $(n_{0},m)_{H}=0$. Being $m\in M$ arbitrary, we obtain $n_{0}\in M^{\perp}$.
>
>It remains to prove the uniqueness. Let $m\in M$, and thus
>$$\begin{align}\|u-m\|_{H}^{2}&=\|u-m_{0}+m_{0}-m\|_{H}^{2}\\ &=\|u-m_{0}\|_{H}^{2}+\|m-m_{0}\|_{H}^{2}\end{align}\quad(*)$$
>since $$(u-m_{0},m-m_{0})_{H}=(n_{0},m-m_{0})_{H}=0$$
>From $(*)$ we obtain
>$$\|u-m\|_{H}^{2}>\|u-m_{0}\|_{H}^{2}=d^{2}$$
>if $m\ne m_{0}$. Therefore $m_{0}$ is unique.
>
>Now suppose $u=m_{1}+n_{1}$, where $m_{1}\in M$ and $n_{1}\in M^{\perp}$. As above, for $m\in M$
>$$\begin{align}\|u-m\|_{H}^{2}&=\|u-m_{1}+m_{1}-m\|_{H}^{2}\\ &=\|u-m_{1}\|_{H}^{2}+\|m-m_{1}\|_{H}^{2}\\ &\ge \|u-m_{1}\|_{H} \end{align}$$
>and thus since $m_{0}$ such that $d=\|u-m_{0}\|_{H}$ is unique, we get $m_{1}=m_{0}$ and therefore $n_{1}=u-m_{0}=n_{0}$.

>[!example]+ 
>
***
#### Keywords
- [[Hilbert space]],
- [[Open and closed subsets]],
- [[Normed space]],
- [[Direct sum of vector spaces]],
- [[Orthogonal complement]],
- [[Supremum and infinum]],
- [[Sequence]],
- [[Real line]],
- [[Vector space]],
- [[Cauchy sequence]],
- [[Convergence]],
- [[Inner product]]
#### Possibly related
- 
***
#### Sources: