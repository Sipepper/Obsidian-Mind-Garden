# Hessian
***
###### tags: #Analysis/Multivariable  
***
#### Two variables case
>[!dsn]+ Direct strict note
>Suppose that $p_{0}=(x_{0},y_{0})$ is a critical point of a function $z=f(x,y)$. We call the matrix
>$$\begin{pmatrix}\frac{\partial^{2}f}{\partial x^{2}}(p_{0})&\frac{\partial^{2}f}{\partial x\partial y}(p_{0})\\ \frac{\partial^{2}f}{\partial y\partial x}(p_{0})&\frac{\partial^{2}f}{\partial y^{2}}(p_{0})\end{pmatrix}$$
>of second derivatives evaluated at $p_{0}$, the *Hessian* of the function $z=f(x,y)$ at a critical point $p_{0}$, and denote it by $H_{f}(p_{0})$.^[Yukio Matsumoto - "An introduction to Morse theory" p.5]

>[!example]+ 
>- For $z=x^{2}+y^{2}$, the Hessian at the origin is
>  $$\begin{pmatrix}2&0\\0&2 \end{pmatrix}$$
>- For $z=x^{2}-y^{2}$, we have
>  $$\begin{pmatrix}2&0\\0&-2 \end{pmatrix}$$
>- For $z=-x^{2}-y^{2}$, we have
>  $$\begin{pmatrix}-2&0\\0&-2 \end{pmatrix}$$

>The matrix $H_{f}(p_{0})$ is symmetric matrix, since 
>$$\frac{\partial^{2}f}{\partial x\partial y}=\frac{\partial^{2}f}{\partial y\partial x}$$
>by [[Symmetry of second partial derivatives]].

>Hessian matrix of a function $f$ is the transpose of the Jacobian matrix of the gradient of the function $f$, that is
>$$H_{f}=J(\nabla f(x))$$
>
>>[!proof]+
>>Let $z=f(x,y)$, then $\nabla f=\left(\frac{\partial f}{\partial x},\frac{\partial f}{\partial y} \right)$. Thus we can define a new coordinate system 
>>$$\begin{cases}X=\frac{\partial f}{\partial x}(x,y)\\ Y=\frac{\partial f}{\partial y}(x,y) \end{cases}$$
>>now Jacobi matrix has the following form
>>$$\begin{pmatrix}\frac{\partial X}{\partial x}&\frac{\partial X}{\partial y}\\ \frac{\partial Y}{\partial x}&\frac{\partial Y}{\partial y} \end{pmatrix}=\begin{pmatrix}\frac{\partial^{2} f}{\partial x^{2}}&\frac{\partial^{2}f }{\partial x\partial y}\\ \frac{\partial^{2}f }{\partial y\partial x}&\frac{\partial^{2} f}{\partial y^{2}} \end{pmatrix}$$
>>thus indeed $H_{f}=J(\nabla f)$.

***
#### Keywords
- [[Critical point of a function]],
- [[Matrix]],
- [[Function(mapping)]],
- [[Function derivative]],
- [[Function gradient]],
- [[Jacobian matrix]],
- [[Change of coordinates]]
#### Possibly related
- 
***
#### Sources: