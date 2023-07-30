# Open mapping theorem
***
###### tags: #Topology #Group_theory/Topological 
***
#### For Banach spaces
>[!dsn]+ Direct strict note
>Let $(B,\|\cdot\|)$ and $(B_{1},\|\cdot\|_{1})$ be Banach spaces and $L:B\to B_{1}$ a continuous linear (in the vector space sense) mapping of $B$ *onto* $B_{1}$. Then $L$ is an open mapping.^[Sidney A. Morris - "Topology without tears" p.168]

>[!proof]+
>It suffices to show that there exists an $N\in\mathbb{N}$ such that $L(B_{N}(0))\supset B_{s}(0)$, for some $s>0$.
>Clearly $B=\bigcup\limits_{n=1}^{\infty}B_{n}(0)$ and as $L$ is surjective we have $B_{1}=L(B)=\bigcup\limits_{n=1}^{\infty}L(B_{n}(0))$. 
>As $B_{1}$ is a Banach space, by [[At least one element from countable partition of complete metric space has a non empty interior]] of the [[Baire Category theorem]], there is an $N\in\mathbb{N}$, such that $\overline{L(B_{N}(0))}$ has non-empty interior.
>So there is a $z\in B_{1}$ and $t>0$, such that $B_{t}(z)\subseteq\overline{L(B_{N}(0))}$.
>There is no loss of generality in assuming that $z\in L(B_{N}(0))$.
>But $B_{t}(z)=B_{t}(0)+z$, and so
>$$B_{t}(0)\subseteq\overline{L(B_{N}(0))}-z=\overline{L(B_{N}(0))-z}\subseteq\overline{L(B_{N}(0))-L(B_{N}(0))}\subseteq\overline{L(B_{2N}(0))}$$
>which, by the linearity of $L$, implies that $B_{t/2}(0)\subseteq\overline{L(B_{N}(0))}$.
>We shall show that this implies that $B_{t/4}(0)\subseteq L(B_{N}(0))$.
>Let $w\in B_{t/2}(0)$. Then there is an $x_{1}\in B_{N}(0)$, such that $\|w-L(x_{1})\|_{1}<\frac{t}{4}$.
>Note that by linearity of the mapping $L$, for each integer $k>0$
>$$B_{t/2}(0)\subseteq\overline{L(B_{N}(0))}\Rightarrow B_{t/(2k)}(0)\subseteq\overline{L(B_{N/k}(0))}$$
>So there is an $x_{2}\in B_{N/2}(0)$, such that
>$$\|(w-L(x_{1}))-L(x_{2})\|_{1}=\|w-L(x_{1})-L(x_{2})\|_{1}<\frac{t}{8}$$
>Continuing in this way, we obtain by induction a sequence $\{x_{m}\}$ such that $\|x_{m}\|<\frac{N}{2^{m-1}}$ and
>$$\|w-L(x_{1}+x_{2}+\dots+x_{m})\|_{1}=\|w-L(x_{1})-L(x_{2})-\dots-L(x_{m})\|_{1}<\frac{t}{2^{m}}$$
>Since $B$ is complete, the series $\sum\limits_{m=1}^{\infty}x_{m}$ converges to a limit $a$.
>Clearly $\|a\|<2N$ and by continuity of $L$, we have $w=L(a)\in L(B_{2N}(0))$.
>So $B_{t/2}(0)\subseteq L(B_{2N}(0))$ and thus $B_{t/4}(0)\subseteq L(B_{N}(0))$ which completes the proof.

>[!example]+ 
>

#### For locally compact groups
>[!dsn]+
>Let $G$ be a locally compact group which is $\sigma$-compact; that is, $G=\bigcup\limits_{n=1}^{\infty}A_{n}$, where each $A_{n}$ is compact. Let $f$ be any continuous homomorphism of $G$ onto a locally compact Hausdorff group $H$. Then $f$ is an open mapping.^[Sidney A. Morris - "Topology without tears" p.535]

>[!proof]+
>Let $\mathcal{U}$ be the family of all symmetric neighbourhoods of $e$ in $G$ and $\mathcal{U}'$ the family of all neighbourhoods of $e$ in $H$. It suffices to show that for every $U\in\mathcal{U}$ there is a $U'\in\mathcal{U}'$ such that $U'\subseteq f(U)$.
>
>Let $U\in\mathcal{U}$. Then there exists (why?) a $V\in\mathcal{U}$ having the property that $\overline{V}$ is compact and $(\overline{V})^{-1}\overline{V}\subseteq U$. The family of sets $\{xV:x\in G\}$ is then an open cover of $G$ and hence also of each compact set $A_{n}$. So a finite collection of these sets will cover any given $A_{n}$. Thus there is a countable collection $\{x_{n}V:n\in\mathbb{N}\}$ which covers $G$.
>
>So
>$$H=\bigcup\limits_{n=1}^{\infty}f(x_{n}V)=\bigcup\limits_{n=1}^{\infty}f(x_{n}\overline{V})=\bigcup\limits_{n=1}^{\infty}f(x_{n})f(\overline{V})$$
>This expresses $H$ as a countable union of closed sets, and by [[Baire Category theorem]] for locally spaces, on of them must have non-empty interior; that is, $f(x_{n})f(\overline{V})$ contains an open set. Then $f(\overline{V})$ contains an open subset $V'$ of $H$:
>To complete the proof select any point $x'$ of $V'$ and put $U'=(x')^{-1}V'$. Then we have
>$$\begin{align}U'=(x')^{-1}V'&\subseteq (V')^{-1}V'\\&\subseteq(f(\overline{V}))^{-1}f(\overline{V})\\ &=f((\overline{V})^{-1}\overline{V})\\ &\subseteq f(U) \end{align}$$
>as required.


***
#### Keywords
- [[Banach space]],
- [[Continuous mapping]],
- [[Linear map]],
- [[Vector space]],
- [[Open and closed mappings]],
- [[Function(mapping)]],
- [[Closure of a set]],
- [[Open ball in metric space]],
- [[Interior, Exterior and boundary of a set in topological space]],
- [[Mathematical induction]],
- [[Convergence in metric spaces]],
- [[Locally compact space]],
- [[Topological group]],
- [[sigma-compact space]],
- [[Compact set]],
- [[Homomorphism]],
- [[Hausdorff space]],
- [[Symmetric neighborhoods in topological groups]],
- [[Cardinality of a set]]
#### Possibly related
- 
***
#### Sources: