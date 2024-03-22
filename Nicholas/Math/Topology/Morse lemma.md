---
Last time checked: 2024-03-13
Complete: false
aliases:
---
# Morse lemma
***
###### tags: #Topology/Differential/Morse_theory 
***
#### Two variables case
>[!dsn]+ Direct strict note
>Let $p_{0}$ be a non-degenerate critical point of a function $f$ of two variables. Then we can choose appropriate local coordinates $(X,Y)$ in such a way that the function $f$ expressed with respect to $(X,Y)$ takes one of the following three standard forms:
>1. $f=X^{2}+Y^{2}+c$
>2. $f=X^{2}-Y^{2}+c$
>3. $f=-X^{2}-Y^{2}+c$

>[!proof]+
>Choose any local coordinate system $(x,y)$ near the point $p_{0}$. We may assume that the point $p_{0}$ is the origin $(0,0)$ in these coordinates. For simplicity we may assume that $f(p_{0})=0$. Further we will show that we may assume
>$$\frac{\partial^{2}f}{\partial x^{2}}(p_{0})\ne0$$
>Of course there is nothing to prove if we already have $\frac{\partial^{2}f }{\partial x^{2}}\ne0$. Also if $\frac{\partial^{2}f }{\partial y^{2}}(p_{0})\ne0$, then even if $\frac{\partial^{2}f}{\partial x^{2}}=0$, by interchanging the $x$-axis and the $y$-axis, we may assume that the condition above is valid. So consider the case where
>$$\frac{\partial^{2}f }{\partial x^{2}}(p_{0})=0\quad\text{and}\quad \frac{\partial^{2}f }{\partial y^{2}}(p_{0})=0$$
>In this case the Hessian $H_{f}$ with respect to $(x,y)$(at the point $p_{0}$) is as follows:
>$$H_{f}=\begin{pmatrix}0&a\\a&0 \end{pmatrix},\quad a\ne0$$
>Here we specify that $a\ne0$, because $p_{0}$ is a non-degenerate critical point. Introduce a new local coordinate system $(X,Y)$ by
>$$x=X-Y,\quad y=X+Y$$
>Then the Jacobian $J$ for the change of coordinates from $(X,Y)$ to $(x,y)$ is
>$$J=\begin{pmatrix}1&-1\\1&1 \end{pmatrix}$$
>so that the Hessian $\mathcal{H}_{f}$ with respect to $(X,Y)$ is
>$$\mathcal{H}_{f}=J^{t}H_{f}J=\begin{pmatrix}2a&0\\0&-2a \end{pmatrix}$$
>Thus by [[type of critical point is not dependent on coordinate system]]
>$$\frac{\partial^{2}f}{\partial X^{2}}(p_{0})=2a\ne0,\quad\frac{\partial^{2}f}{\partial Y^{2}}(p_{0})=-2a\ne0$$
>Using the old notation $(x,y)$ for $(X,Y)$, we see that $f$ certainly satisfies 
>$$\frac{\partial^{2}f }{\partial x^{2}}(p_{0})\ne0$$
>Now we utilize [[function of several variables expressed near the origin]] *two* times, and express function $f$ first as
>$$f(x,y)=xg(x,y)+yh(x,y)$$
>and then
>$$g(x,y)=xh_{11}(x,y)+yh_{12}(x,y)$$
>$$h(x,y)=xh_{21}(x,y)+yh_{22}(x,y)$$
>and finally
>$$h(x,y)=x^{2}h_{11}+xy(h_{12}+h_{21})+y^{2}h_{22}$$
>make substitutions $H_{11}=h_{11}$, $H_{12}(h_{12}+h_{21})/2$ and $H_{22}=h_{22}$ thus
>$$f(x,y)=x^{2}H_{11}+2xyH_{12}+y^{2}H_{22}$$
>From this equality we obtain
>$$\begin{cases}\frac{\partial^{2}f}{\partial x^{2}}(0,0)=2H_{11}(0,0)\\ \frac{\partial^{2}f}{\partial x\partial y}(0,0)=\frac{\partial^{2} }{\partial y\partial x}(0,0)=2H_{12}(0,0)\\ \frac{\partial^{2}f}{\partial y^{2}}(0,0)=2H_{22}(0,0) \end{cases}$$
>As second derivatives are supposed to be non-zero, hence $H_{11}(0,0)\ne0$, and since $H_{11}$ is continuous, we see that 
>>$H_{11}(x,y)$ is not zero in some neighborhood of $(0,0)$.
>
>Now define a new $x$-coordinate $X$ near this neighborhood of the origin $(0,0)$ by
>$$X=\sqrt{|H_{11}|}\left(x+\frac{H_{12}}{H_{11}}y\right)$$
>and keep the $y$-coordinate as it is. The Jacobian between $(x,y)$ and $(X,y)$ evaluated at the origin is not zero, so $(X,Y)$ is certainly a local coordinate system for some neighborhood of the origin $(0,0)$. We square $X$:
>$$\begin{align}X^{2}&=|H_{11}|\left(x^{2}+2\frac{H_{12}}{H_{11}}xy+\frac{H_{12}^{2}}{H_{11}^{2}}y^{2} \right)\\ &=\begin{cases}H_{11}x^{2}+2H_{12}xy+\frac{H_{12}^{2}}{H_{11}}y^{2}&(H_{11}>0)\\ -H_{11}x^{2}-2H_{12}xy-\frac{H_{12}^{2}}{H_{11}}y^{2}&(H_{11}<0) \end{cases}\end{align}$$
>if we compare it with
>$$h(x,y)=x^{2}h_{11}+xy(h_{12}+h_{21})+y^{2}h_{22}$$
>we see that for $H_{11}>0$
>$$f=X^{2}+\left(H_{22}-\frac{H_{12}^{2}}{H_{11}}\right)y^{2}$$
>and for $H_{11}<0$
>$$f=-X^{2}+\left(H_{22}-\frac{H_{12}^{2}}{H_{11}} \right)y^{2}$$
>Therefore
>$$H_{11}(0,0)H_{22}(0,0)-H_{12}^{2}(0,0)=\frac{1}{4}\det H_{f}\ne0$$
>(the determinant of Hessian)
>where $\det H_{f}\ne0$ because of the assumption that the origin $p_{0}$ is a non-degenerate critical point of $f$. If we choose a new $y$-coordinate $Y$ near the origin $p_{0}=(0,0)$ by
>$$Y=y\sqrt{\left|\frac{H_{11}H_{22}-H_{12}^{2}}{H_{11}} \right|}$$
>and rewrite equalities for $f$(expressed above), $f$ has the following expression in the local coordinates $(X,Y)$:
>$$f=\begin{cases}X^{2}+Y^{2}&(H_{11}>0,\;K>0)\\ X^{2}-Y^{2}&(H_{11}>0,\;K<0)\\ -X^{2}+Y^{2}&(H_{11}>0,\;K>0)\\ -X^{2}-Y^{2}&(H_{11}>0,\;K>0)\\ \end{cases}$$
>where we denote $H_{11}H_{22}-H_{12}^{2}$ by $K$ for simplicity. If we interchange $X$ and $Y$ through a "$90^{\circ}$ rotation", we see that $f=X^{2}-Y^{2}$ and $f=-X^{2}+Y^{2}$ are essentially the same standard form. This concludes the proof.

>[!example]+ 
>
***
#### Keywords
- [[Critical point of a function]],
- [[Function(mapping)]],
- [[n-dimensional chart]],
- [[Change of coordinates]],
- [[Function derivative]],
- [[Hessian]],
- [[Jacobian matrix]],
- [[Matrix]],
- [[Continuous mapping]],
- [[Neighborhood in topological space]],
- [[Determinant]]
#### Possibly related
- [[Quadratic form]]
***
#### Sources: