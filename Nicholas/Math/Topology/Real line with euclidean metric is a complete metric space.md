# Real line with euclidean metric is a complete metric space
***
###### tags: #Topology 
***
>[!dsn] Direct strict note
>The metric space $\mathbb{R}$ with the euclidean metric is a complete metric space.^[Sidney A. Morris - "Topology without tears" p.152]

>[!proof]
>Let $\{x_{n}\}$ be any Cauchy sequence in $(\mathbb{R},d)$.
>As $\set{x_{n}}$ is a Cauchy sequence, there exists a positive integer $N$, such that $\forall n\ge N$ and $\forall m\ge N$, $d(x_{n},x_{m})<1$; that is, $|x_{n}-x_{m}|<1$. Put $M=|x_{1}|+|x_{2}|+\dots+|x_{N}|+1$. Then $|x_{n}|<M$, $\forall\in\mathbb{N}$; that is, the sequence $\set{x_{n}}$ is bounded.
>So by [[Bolzano-Weierstrass Theorem]], this sequence has a convergent subsequence; that is, there is an $a\in\mathbb{R}$ and a subsequence $\set{x_{n_{k}}}$ with $x_{n_{k}}\to a$.
>
>Let $\varepsilon>0$. As $\set{x_{n}}$ is a Cauchy sequence, there exists a positive integer $N_{0}$ such that 
>$$|x_{n}-x_{m}|<\frac{\varepsilon}{2}\qquad\forall m,n\ge N_{0}$$
>Since $x_{n_{k}}\to a$, there exists a positive integer $N_{1}$, such that
>$$|x_{n_{k}}-a|<\frac{\varepsilon}{2}\qquad\forall n_{k}\ge N_{1}$$
>So if we choose $N_{2}=\max\set{N_{0},N_{1}}$, combining the above two inequalities yields
>$$\begin{align}|x_{n}-a|&\le|x_{n}-x_{n_{k}}|+|x_{n_{k}}-a|\\ &<\frac{\varepsilon}{2} +\frac{\varepsilon}{2}\qquad\forall n,n_{k}>N_{2}\\ &=\varepsilon\end{align}$$
>Hence $x_{n}\to a$, which completes the proof.
***
#### Keywords
- [[Metric space]],
- [[Euclidean topology]],
- [[Complete metric space]],
- [[Cauchy sequence]],
- [[Bounded set]],
- [[Convergence in metric spaces]],
#### Possibly related
- 
***
#### Sources: