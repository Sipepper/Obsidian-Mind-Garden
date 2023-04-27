# Norm on a pre-Hilbert space
***
###### tags: #Analysis/Functional 
***
>[!dsn]+ Direct strict note
>Let $H$ be a pre-Hilbert space, then function $\|\cdot\|_{H}:H\to\mathbb{R}$ defined as $\|u\|_{H}=\sqrt{(u,u)}$ is a norm on $H$.^[Fabio Silva Botelho - "Functional analysis and applied optimization on banach spaces" p.31-32]

>[!proof]+
>We only need to prove a triangle inequality. Note that for any two elements $u,v\in H$ Cauchy-Schwarz inequality implies the following
>$$\begin{align}\|u+v\|_{H}^{2}&=(u+v,u+v)_{H}\\ &=(u,u)_{H}+(v,v)_{H}+2(u,v)_{H}\\ &\le (u,u)_{H}+(v,v)_{H}+2|(u,v)_{H}|\\ &\le \|u\|_{H}^{2}+\|v\|_{H}^{2}+2\|u\|_{H}\|v\|_{H}\\ &=(\|u\|_{H}+\|v\|_{H})^{2} \end{align}$$
>Thus $\|u+v\|_{H}\le\|u\|_{H}+\|v\|_{H}$, $\forall u,v\in H$.

***
#### Keywords
- [[Pre-Hilbert space]],
- [[Function(mapping)]],
- [[Normed space]],
- [[Cauchy-Schwarz inequality]]
#### Possibly related
- 
***
#### Sources: