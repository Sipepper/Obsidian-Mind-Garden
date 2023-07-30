# Change of Hessian under coordinates change
***
###### tags: #Analysis/Multivariable 
***
#### Two variables
>[!dsn]+ Direct strict note
>Let $p_{0}$ be a critical point of a function $z=f(x,y)$. Let $H_{f}(p_{0})$ be the Hessian of $f$ computed using the coordinates $(x,y)$, and $\mathcal{H}_{f}(p_{0})$ be the Hessian of the same $f$ computed using different coordinates $(X,Y)$. Then the following relation holds:
>$$\mathcal{H}_{f}(p_{0})=J^{t}(p_{0})H_{f}(p_{0})J(p_{0})$$
>where $J(p_{0})$ is the Jacobian matrix for the above coordinate transformation, defined by
>$$J(p_{0})=\begin{pmatrix}\frac{\partial x}{\partial X}(p_{0})&\frac{\partial x}{\partial Y}(p_{0})\\\frac{\partial y}{\partial X}(p_{0})&\frac{\partial y}{\partial Y}(p_{0})  \end{pmatrix}$$
>.^[Yukio Matsumoto - "An introduction to Morse theory" p.8]

>[!proof]+
>We apply the formula of [[Change of variables in partial derivatives]]
>$$\frac{\partial f}{\partial X}=\frac{\partial f}{\partial x}\frac{\partial x}{\partial X}+ \frac{\partial f}{\partial y}\frac{\partial y}{\partial X}$$
>$$\frac{\partial f}{\partial Y}=\frac{\partial f}{\partial x}\frac{\partial x}{\partial Y}+ \frac{\partial f}{\partial y}\frac{\partial y}{\partial Y}$$
>and express $\frac{\partial^{2}f }{\partial X^{2}}$, $\frac{\partial^{2}f}{\partial X\partial Y}$ and $\frac{\partial^{2}f }{\partial Y^{2}}$ in terms of $\frac{\partial^{2} f}{\partial x^{2}}$, $\frac{\partial^{2}f }{\partial x\partial y}$ and $\frac{\partial^{2} f}{\partial y^{2}}$.(I'll finish it at some day)

>[!example]+ 
>Let $z=xy$ be a function on two variables. Introduce new coordinates
>$$\begin{cases}x=X-Y\\ y=X+Y \end{cases}$$
>we obtain
>$$xy=(X-Y)(X+Y)=X^{2}-Y^{2}$$
>The Hessians at the origin $\textbf{0}$(critical point) of these functions with respect to the coordinates $(x,y)$ and $(X,Y)$ were
>$$\begin{pmatrix}0&1\\1&0\end{pmatrix}\qquad\begin{pmatrix}2&0\\0&-2 \end{pmatrix}$$
>respectively. The Jacobian matrix for the coordinate transformation is
>$$\begin{pmatrix}1&-1\\1&1 \end{pmatrix}$$
>and respectively
>$$\begin{pmatrix}2&0\\0&-2 \end{pmatrix}=\begin{pmatrix}1&1\\-1&1 \end{pmatrix}\begin{pmatrix}0&1\\1&0 \end{pmatrix}\begin{pmatrix}1&-1\\1&1 \end{pmatrix}$$
***
#### Keywords
- [[Critical point of a function]],
- [[Hessian]],
- [[Change of coordinates]],
- [[Jacobian matrix]],
- [[Function derivative]],
- [[Function(mapping)]],
- [[Matrix]]
#### Possibly related
- 
***
#### Sources: