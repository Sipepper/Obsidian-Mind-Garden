# Critical point of a function
***
###### tags: #Analysis 
***
#### Of one variable
>[!dsn]+ Direct strict note
>Consider a real function $y=f(x)$. A point $x_{0}$ which satisfies
>$$f'(x_{0})=0$$
>is called a *critical point* of the function $f$.^[Yukio Matsumoto - "An introduction to Morse theory" p.2]

>The critical point $x_{0}$ is said to be *non-degenerate* if $f''(x_{0})\ne0$, and *degenerate* if $f''(x_{0})=0$.

>Non-degenerate points can be viewed as *stable* when degenererate critical points are *unstable*. 
>
>For example, if we perturb quadratic function $y=x^{2}$ by adding linear function $y=ax+b$, then
>$$y=x^{2}+ax+b$$
>has non-degenerate critical point $x=-a/2$, with second derivative $y''=2$.
>Conversely function
>$$y=x^{3}+ax+b$$
>has critical points of the form
>$$x=\pm\sqrt{\frac{-a}{3}}$$
>But we see that when $a>0$ there are no real solutions, so the perturbed function has no critical point if $a>0$. So we *lost* critical point after perturbation.
>![[Pasted image 20230718203245.png]]

>[!example]+ 
>The quadratic function $y=x^{2}$ gives $y''=2$; so the critical point $x=0$ of $y=x^{2}$ is non-degenerate.
>
>![[Pasted image 20230716215852.png]]
>
>For $n\ge3$, the critical point $x=0$ of the degree $n$ function $y=x^{n}$ is degenerate. In fact, the second derivative $y''=n(n-1)x^{n-2}$ of $y=x^{n}$ is zero at $x=0$.

#### Of two variables
>[!dsn]+
>Let $f:\mathbb{R}^{2}\to\mathbb{R}$ be a real function of two variables. Point $p_{0}=(x_{0},y_{0})$ in the $xy$-plane is a *critical point* of a function $z=f(x,y)$ if the following conditions hold:
>$$\frac{\partial f}{\partial x}(p_{0})=0,\quad\frac{\partial f}{\partial y}(p_{0})=0$$

>A critical point $p_{0}$ of a function $z=f(x,y)$ is *non-degenerate* if the determinant of [[Hessian]] of $f$ at $p_{0}$ is not zero; that is
>$$\det H_{f}(p_{0})=\frac{\partial^{2}f}{\partial x^{2}}(p_{0})\frac{\partial^{2}f}{\partial y^{2}}(p_{0})-\left(\frac{\partial^{2}f}{\partial x\partial y}(p_{0}) \right)^{2}\ne0$$
>and if $\det H_{f}(p_{0})=0$, $p_{0}$ is a *degenerate critical point*.

>[!example]+
>The origin $\textbf{0}=(0,0)$ is a critical point of each of the following three functions:
>$$z=x^{2}+y^{2},\quad z=x^{2}-y^{2},\quad z=-x^{2}-y^{2}$$
>![[Pasted image 20230718204203.png]]
>
>- For $z=x^{2}+y^{2}$, the Hessian at the origin is
>  $$\begin{pmatrix}2&0\\0&2 \end{pmatrix}$$
>- For $z=x^{2}-y^{2}$, we have
>  $$\begin{pmatrix}2&0\\0&-2 \end{pmatrix}$$
>- For $z=-x^{2}-y^{2}$, we have
>  $$\begin{pmatrix}-2&0\\0&-2 \end{pmatrix}$$
>
>With all non-zero determinants, thus $(0,0)$ is a non-degenerate critical point. 
***
#### On surface
>[!dsn]+ Direct strict note
>Let $f:M\to\mathbb{R}$ be a smooth function on a surface. We say that a point $p_{0}$ of a surface $M$ is a *critical point* of a function $f:M\to\mathbb{R}$ if 
>$$\frac{\partial f}{\partial x}(p_{0})=0,\quad \frac{\partial f}{\partial y}(p_{0})=0$$
>with respect to local coordinates in some neighborhood of $p_{0}$.^[Yukio Matsumoto - "An introduction to Morse theory" p.16]

#### Keywords
- [[Function(mapping)]],
- [[Function derivative]],
- [[Function order]],
- [[Linear map]],
- [[Determinant]],
- [[Functions on surfaces]],
- [[Smooth surface]],
- [[n-dimensional chart]],
- [[Neighborhood in topological space]]
#### Possibly related
- 
***
#### Sources: