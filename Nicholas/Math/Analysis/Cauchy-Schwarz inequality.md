# Cauchy-Schwarz inequality
***
###### tags: #Analysis/Functional 
***
>[!dsn]+ Direct strict note
>Let $H$ be a pre-Hilbert space. If we define a norm as
>$$\|u\|_{H}=\sqrt{(u,u)_{H}}\quad\forall u\in H$$
>we have the following inequality
>$$|(u,v)_{H}|\le\|u\|_{H}\|v\|_{H}\quad\forall u,v\in H$$
>Equality is meet if and only if $u=\alpha v$ for some $\alpha\in\mathbb{R}$ or $v=\theta$.

>[!proof]+
>When $v=\theta$, inequality is trivial. Suppose that $v\ne\theta$. Let $\alpha\in\mathbb{R}$ then
>$$\begin{align}0&\le(u-\alpha v,u-\alpha v)_{H}\\ &=(u,u)_{H}+\alpha^{2}(v,v)_{H}-2\alpha(u,v)_{H}\\ &=\|u\|_{H}^{2}+\alpha^{2}\|v\|_{H}^{2}-2\alpha(u,v)_{H} \end{align}$$
>In particular, for $\alpha=\frac{(u,v)_{H}}{\|v\|_{H}^{2}}$, we get the following
>$$0\le\|u\|_{H}^{2}-\frac{(u,v)_{H}^{2}}{\|v\|_{H}^{2}}$$
>i.e.
>$$|(u,v)_{H}|\le\|u\|_{H}\|v\|_{H}$$
>Because for any $u,v$ we can choose similar constant $\alpha$ then the inequality in proposition holds for all $u,v\in H$. 

>[!example]+ 
>
***
#### Keywords
- [[Pre-Hilbert space]],
- [[Normed space]],
- [[Inner product]],
#### Possibly related
- 
***
#### Sources: