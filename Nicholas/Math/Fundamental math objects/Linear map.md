# Linear map
***
###### tags: #Fundamental_math_objects 
***
>[!dsn] Direct strict note
>Function $f:U\to V$, where $U$ and $V$ is a topologival vector spaces, is said to be *linear* if $$f(\alpha u+\beta v)=\alpha f(u)+\beta f(v),\quad\forall u,v\in U,\quad\alpha,\beta\in\mathbb{F}$$

>[!example] 
>
#### Properties of linear maps
>[!dsn] Direct strict note
>Let $f:U\to V$ be a linear function. Suppose the following:
>1. $f$ is a continuous function.
>2. $f$ is a bounded function.
>3. If $u_{n}\to\theta$, then the sequence $\{f(u_{n})\}$ is bounded
>4. If $u_{n}\to\theta$, then $f(u_{n})\to\theta$
>
>Then, 
>- from $(1)$ follows the $(2)$
>- from $(2)$ follows the $(3)$
>- and if $U$ is metrizable, then from $(3)$ it follows the $(4)$, from which follows the $(1)$
>I.e. if $U$ is metrizable, then all four propositions are equivalent.

>[!proof]
>$(1)\Rightarrow(2)$:
>Suppose that $f$ is a continuous function, i.e. for neighbourhood of zero $\mathcal{W}\subset V$ there exists a neighbourhood of zero in $U$, denoted by $\mathcal{V}$, such that
>$$f(\mathcal{V})\subset\mathcal{W}$$
>Let $E$ be a bounded set, then exist a real number $t_{0}\in\mathbb{R}^{+}$ such that $E\subset t\mathcal{V}$, $\forall t\ge t_{0}$,  and 
>$$f(E)\subset f(t\mathcal{V})=tf(\mathcal{V})\subset t\mathcal{W},\quad\forall t\ge t_{0}$$
>therefore $f$ is a bounded function.
>
>$(2)\Rightarrow(3)$:
>Suppose that $u_{n}\to\theta$ and let $\mathcal{W}$ be a neighbourhood of zero. Then exist such $N\in\mathbb{N}$ that if $n\ge N$, then $u_{n}\in\mathcal{V}\subset\mathcal{W}$ where $\mathcal{V}$ is a balanced neighbourhood of zero. On the other hand, for $n<N$, exist $K_{n}$ such that $u_{n}\in K_{n}\mathcal{V}$. Define $K=\max\set{1,K_{1},\dots,K_{n}}$. Then , $u_{n}\in K\mathcal{V}$, $\forall n\in\mathbb{N}$ and therefore $\{u_{n}\}$ is a  bounded sequence. Finally from $(2)$ we obtain that sequence $\{f(u_{n})\}$ is bounded.
>
>$(3)\Rightarrow(4)$:
>Suppose that $U$ is metrizable and let $u_{n}\to\theta$. Let $K\in\mathbb{N}$, there exists a number $n_{K}\in\mathbb{N}$ such that if $n>n_{K}$, then $d(u_{n},\theta)<\frac{1}{K^{2}}$. Define $\gamma_{n}$ as $$\gamma_{n}=\begin{cases}1&n<n_{1}\\ K&n_{K}\le n<n_{K+1}\end{cases}$$ such that 
>$$d(\gamma_{n}u_{n},\theta)=d(Ku_{n},\theta)\le Kd(u_{n},\theta)<K^{-1}$$ 
>Therefore, because $(2)\Rightarrow(3)$ we obtained that the sequence $\{f(\gamma_{n}u_{n})\}$ is bounded, and by [[Boundedness using subsequences|boundedness using sequences]] it follows that $f(u_{n})=\gamma^{-1}f(\gamma_{n}u_{n})\to\theta$ when $n\to\infty$.
>
>$(4)\Rightarrow(1)$:
>Suppose that property $(1)$ is not holds; i.e. function $f$ is not continuous. Then exist some neighbourhood of zero $\mathcal{W}\subset V$ such that the preimage $f^{-1}(\mathcal{W})$ don't contain any neighbourhoods of zero in $U$. In particular, we can choose a sequence $\{u_{n}\}$ such that $u_{n}\in B_{1/n}(\theta)$ and $f(u_{n})\notin\mathcal{W}$ then $\{f(u_{n})\}$ is not converging to zero. Therefore $(4)$ will not hold.
***
#### Keywords
- [[Linear map]],
- [[Continuous mapping]],
- [[Bounded mapping]],
- [[Sequence]],
- [[Metrizable space]],
- [[Neighborhood in topological space]],
- [[Balanced subsets of topological vector spaces]],
- [[Convergence]],
- [[Function(mapping)]],
- [[Bounded set]],
- [[Preimage]],
#### Possibly related
- 
***
#### Sources:
1. Fabio Botelho "Functional analysis and Applied Optimization in Banach Spaces" p.21-23