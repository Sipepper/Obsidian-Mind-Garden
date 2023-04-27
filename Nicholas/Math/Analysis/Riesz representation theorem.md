# Riesz representation theorem
***
###### tags: #Analysis/Functional 
***
>[!dsn]+ Direct strict note
>Let $H$ be a Hilbert space and let $f:H\to\mathbb{R}$ is a linear functional. Then there exists a unique element $u_{0}\in H$ such that
>$$f(u)=(u,u_{0})_{H}\quad\forall u\in H$$
>Furthermore
>$$\|f\|_{H^{*}}=\|u_{0}\|_{H}$$
>.^[Fabio Silva Botelho - "Functional analysis and applied optimization in banach spaces" p.34-35]

>[!proof]+
>Define $N$ as $N=\{u\in H:f(u)=0\}$. Therefore because $f$ is continuous and linear functional, then $N$ is a closed subspace of $H$. Let $N=H$, then $f(u)=0=(u,\theta)_{H}$, $\forall u\in H$ and proof is done. Therefore, suppose that $N\ne H$. From [[Every element of Hilbert space can be expressed as unique sum of element from closed subspace and orthogonal to it]] we know that exists $v\ne\theta$ such that $v\in N^{\perp}$.
>Define 
>$$u_{0}=\frac{f(v)}{\|v\|_{H}^{2}}v$$
>Then, if $u\in N$ we get
>$$f(u)=0=(u,u_{0})_{H}=0$$
>Conversely, if $u=\alpha v$ for some $\alpha\in\mathbb{R}$, we have
>$$\begin{align}f(u)&=\alpha f(v)\\ &=\frac{f(v)(\alpha v,v)_{H}}{\|v\|_{H}^{2}}\\ &=\left(\alpha v,\frac{f(v)}{\|v\|_{H}^{2}}v \right)_{H}\\ &=(\alpha v,u_{0})_{H} \end{align}$$
>Therefore $f(u)$ is equal to $(u,u_{0})_{H}$ in subspaces spanned by $N$ and vector $v$. Let's show that such space is equal to $N$. Note that some element $u\in H$ can be represented as
>$$u=\left(u-\frac{f(u)v}{f(v)}\right)+\frac{f(u)v}{f(v)}$$
>Because $u-\frac{f(u)v}{f(v)}\in N$ then we proved first part, i.e. we proved that $f(u)=(u,u_{0})_{H}$, $\forall u\in H$. To finish the proof, suppose that exists an element $u_{1}\in H$ such that $f(u)=(u,u_{1})_{H}$, $\forall u\in H$. Then
>$$\begin{align}\|u_{0}-u_{1}\|_{H}^{2}&=(u_{0}-u_{1},u_{0}-u_{1})_{H}\\ &=(u_{0}-u_{1})_{H}-(u_{0}-u_{1},u_{1})_{H}\\ &=f(u_{0}-u_{1})-f(u_{0}-u_{1})\\ &=0 \end{align}$$
>Thus $u_{1}=u_{0}$.
>Now we prove that $\|f\|_{H^{*}}=\|u_{0}\|_{H}$. First note that
>$$\begin{align}\|f\|_{H^{*}}&=\sup\{f(u):u\in H,\|u\|_{H}\le1\}\\ &=\sup\{|(u,u_{0})_{H}|:u\in H,\|u\|_{H}\le1\}\\ &\le\sup\{\|u\|_{H}\|u_{0}\|_{H}:u\in H,\|u\|_{H}\le1\}\\ &\le\|u_{0}\|_{H}\end{align}$$
>Conversely
>$$\begin{align}\|f\|_{H^{*}}&=\sup\{f(u):u\in H,\|u\|_{H}\le1\}\\ &\ge f\left(\frac{u_{0}}{\|u_{0}\|_{H}}\right)\\ &=\frac{(u_{0},u_{0})_{H}}{\|u_{0}\|_{H}}\\ &=\|u_{0}\|_{H} \end{align}$$
>Thus $\|f\|_{H^{*}}=\|u_{0}\|_{H}$, which completes the proof.

***
#### Keywords
- [[Hilbert space]],
- [[Linear map]],
- [[Functional]],
- [[Inner product]],
- [[Dual topological space]],
- [[Continuous mapping]],
- [[Open and closed subsets]],
- [[Vector space#Subspace]],
- [[Linear span]],
- [[Supremum and infinum]],
- [[Orthogonal complement]]
#### Possibly related
- 
***
#### Sources: