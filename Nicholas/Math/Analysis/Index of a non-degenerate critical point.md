---
Last time checked: 2024-02-02
Complete: false
aliases:
---
# Index of a non-degenerate critical point
***
###### tags: #Analysis/Multivariable 
***
#### Two variable case
>[!dsn]+ Definition
>Let $p_{0}$ be a non-degenerate critical point of a function $f$ of two variables. We choose a suitable coordinate system $(x,y)$ in some neighborhood of the point $p_{0}$ so that the function has a standard form given by [[Morse lemma]]. Then the *index* of the non-degenerate critical point $p_{0}$ of $f$ is $0$, $1$ and $2$, respectively for 
>$$f=x^{2}+y^{2}+c$$
>$$f=x^{2}-y^{2}+c$$
>$$f=-x^{2}-y^{2}+c$$
>The index of a non-degenerate critical point $p_{0}$ is determined by the behaviour of $f$ near $p_{0}$.^[[[Yukio Matsumoto - An introduction to Morse theory.pdf#page=27|Yukio Matsumoto - "An introduction to Morse theory" p.13]]]

>In other words, the number of minus signs in the standard form is the index of $p_{0}$.

>- If the index of $p_{0}$ is $0$ then $f$ takes a minimum value at $p_{0}$.
>- If the index of $p_{0}$ is $1$, then in some neighborhood of $p_{0}$, $f$ may take values strictly larger than $f(p_{0})$ or it may take values strictly smaller than $f(p_{0})$.
>- If the index of $p_{0}$ is $2$, then $f$ takes a maximum value at $p_{0}$.

>The index is well-defined.
>>[!proof]+
>>Consider the Hessians of the functions $z=x^{2}+y^{2}$, $z=x^{2}-y^{2}$ and $z=-x^{2}-y^{2}$
>>$$\begin{pmatrix}2&0\\0&2 \end{pmatrix},\quad \begin{pmatrix}2&0\\0&-2 \end{pmatrix}\quad\text{and}\quad \begin{pmatrix}-2&0\\0&-2 \end{pmatrix}$$
>>respectively.
>>We may think of these matrices as the diagonalized Hessian $H_{f}(p_{0})$ of $f$. In other words, there is a matrix $J$ such that the matrix $J^{t}H_{f}(p_{0})J$ is a diagonal matrix (one of the above). According to [[Sylvester law]], when we diagonalize a symmetric matrix such as our $H_{f}(p_{0})$, the number of minus signs appearing in the diagonal depends on $H_{f}(p_{0})$ and not on the way we diagonalize it. This proves that the index is well-defined.

>[!example]+ 
>
***
#### Keywords
- [[Critical point of a function]],
- [[n-dimensional chart]],
- [[Matrix]],
- [[Hessian]],
- [[Matrix diagonalization]]
#### Possibly related
- [[Neighborhood in topological space]],
***
#### Sources: