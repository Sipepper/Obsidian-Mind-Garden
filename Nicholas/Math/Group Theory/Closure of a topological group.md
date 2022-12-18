# Closure of a topological group
***
###### tags: #Group_theory/Topological 
***
>[!dsn] Direct strict note
>Let $G$ be a topological group, $H\le G$, then
>1. Closure $\overline{H}$ of $H$ will also be a subgroup of $G$.
>2. $G$ is a Hausdorff space if and only if it's neutral element is a closed subset($\{e\}$).^[Alain M. Robert - "Course in p-adic analysis" p.19]

>[!proof]
>1. Let $\phi:G\times G\to G$ denotes the continuous mapping $(x,y)\mapsto xy^{-1}$. Because $H$ is a subgroup, we have that $\phi(H\times H)\subset H$ and thus
>   $$\phi(\overline{H}\times\overline{H})=\phi(\overline{H\times H})\subset\overline{\phi(H\times H)}\subset\overline{H}$$
>   Which proves that $\overline{H}$ is a subgroup of $G$.
>
>2. From the [[Хаусдорффовость через диагональ]] we know that space $X$ will be Hausdorff precisely when it's diagonal $\Delta_{X}$ is closed in $X\times X$. Also in any Hausdorff space every point is a closed set, therefore
>   $$\begin{align}G-\text{Hausdorff}&\Rightarrow\{e\}-\text{closed}\\ &\rightarrow\Delta_{G}=\phi^{-1}(e)\;\text{closed in}\;G\times G\\ &\Rightarrow G-\text{Hausdorff} \end{align}$$
>   Which completes the proof.
***
#### Keywords
- [[Closure of a set]],
- [[Topological group]],
- [[Открытое и замкнутое множества]],
- [[Непрерывное отображение]],
- [[Диагональ произведения топологических пространств]],
#### Possibly related
- 
***
#### Sources: