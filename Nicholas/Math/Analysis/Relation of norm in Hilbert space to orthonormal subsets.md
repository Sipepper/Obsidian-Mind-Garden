# Relation of norm in Hilbert space to orthonormal subsets
***
###### tags: #Analysis/Functional 
***
>[!dsn]+ Direct strict note
>Let $H$ be a Hilbert space and let $\{u_{n}\}_{n=1}^{N}$ be an orthonormal set. Then for all $u\in H$, the following equality holds
>$$\|u\|_{H}^{2}=\sum\limits_{n=1}^{N}|(u,u_{n})_{H}|^{2}+\left\|u-\sum\limits_{n=1}^{N}(u,u_{n})_{H}u_{n}\right\|_{H}^{2}$$
>.^[Favio Silva Botelho - "Functional analysis and applied optimization in Banach spaces" p.36-37]

>[!proof]+
>Note that
>$$u=\sum\limits_{n=1}^{N}(u,u_{n})_{H}u_{n}+\left(u-\sum\limits_{n=1}^{N}(u,u_{n})_{H}u_{n}\right)$$
>further, as $u_{n}$ is an orthonormal set, then $\sum\limits_{n=1}^{N}(u,u_{n})_{H}u_{n}$ and $u-\sum\limits_{n=1}^{N}(u,u_{n})_{H}u_{n}$ are orthogonal vectors, and thus
>$$\begin{align}\|u\|_{H}^{2}&=(u,u)_{H}\\ &=\left\|\sum\limits_{n=1}^{N}(u,u_{n})_{H}u_{n} \right\|_{H}^{2}+\left\|u-\sum\limits_{n=1}^{N}(u,u_{n})_{H}u_{n}\right\|_{H}^{2}\\ &=\sum\limits_{n=1}^{N}|(u,u_{n})_{H}|^{2}+\left\|u-\sum\limits_{n=1}^{N}(u,u_{n})_{H}u_{n}\right\|_{H}^{2} \end{align}$$

***
#### Keywords
- [[Hilbert space]],
- [[Orthonormal basis]],
- [[Normed space]]
#### Possibly related
- [[Vector]]
***
#### Sources: