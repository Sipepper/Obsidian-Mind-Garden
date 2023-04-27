# Jacobian matrix
***
###### tags: #Analysis/Multivariable #Fundamental_math_objects 
***
>[!dsn] Direct strict note
>Suppose $f:\mathbb{R}^{n}\to\mathbb{R}^{m}$ is a function such that each of its first-order partial derivatives exist on $\mathbb{R}^{n}$. This function takes a point $x\in\mathbb{R}^{n}$ as input and produces the vector $f(x)\in\mathbb{R}^{m}$ as output. Then the *Jacobian matrix* of $f$ is defined to be an $m\times n$ matrix, denoted by $\textbf{J}$, whose $(i,j)$-th entry is $\textbf{J}_{ij}=\frac{\partial f_{i}}{\partial x_{j}}$, or explicitly
>$$\textbf{J}=\begin{bmatrix}\frac{\partial f}{\partial x_{1}}&\dots&\frac{\partial f}{\partial x_{n}}\end{bmatrix}=\begin{bmatrix}\nabla^{t}f_{1}\\ \vdots\\ \nabla^{t}f_{m}\end{bmatrix}=\begin{bmatrix}\frac{\partial f}{\partial x_{1}}&\dots&\frac{\partial f}{\partial x_{n}} \\ \vdots&\ddots&\vdots \\ \frac{\partial f_{m}}{\partial x_{1}}&\dots&\frac{\partial f_{m}}{\partial x_{n}}\end{bmatrix}$$
>where $\nabla^{t}f_{i}$ is the transpose of the gradient of the $i$ component. Jacobian matrix often denoted as 
>$$\frac{\partial(f_{1},\dots,f_{m})}{\partial(x_{1},\dots,x_{n})}$$
>.^[https://en.wikipedia.org/wiki/Jacobian_matrix_and_determinant]

>The Jacobian matrix represents the differential of $f$ at every point where $f$ is differentiable.

>[!example] 
>Consider the function $f:\mathbb{R}^{2}\to\mathbb{R}^{2}$, with $(x,y)\mapsto(f_{1}(x,y),f_{2}(x,y))$, given by
>$$f\left(\begin{bmatrix}x\\ y \end{bmatrix}\right)=\begin{bmatrix}f_{1}(x,y)\\ f_{2}(x,y) \end{bmatrix}=\begin{bmatrix}x^{2}y\\ 5x+\sin y\end{bmatrix}$$
>then the Jacobian matrix of $f$ is
>$$\textbf{J}_{f}(x,y)=\begin{bmatrix}\frac{\partial f_{1}}{\partial x}&\frac{\partial f_{1}}{\partial y}\\ \frac{\partial f_{2}}{\partial x}&\frac{\partial f_{2}}{\partial y} \end{bmatrix}=\begin{bmatrix}2xy& x^{2}\\ 5&\cos y \end{bmatrix}$$
>and the Jacobian determinant is 
>$$\det(\textbf{J}_{f}(x,y))=2xy\cos y-5x^{2}$$

>More examples and visualizations can be found in this video
><iframe width="560" height="315" src="https://www.youtube.com/embed/wCZ1VEmVjVo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
***
#### Keywords
- [[Function(mapping)]],
- [[Function derivative]],
- [[Vector function]],
- [[Matrix]],
- [[Linear form]],
- [[Differential]],
- [[Determinant]],
#### Possibly related
- 
***
#### Sources: