# Function of several variables expressed near the origin
***
###### tags: #Analysis/Multivariable 
***
#### Of two variables
>[!dsn]+ Direct strict note
>Suppose we have a function $z=f(x,y)$ defined near the origin with $f(0,0)=0$. Then there are functions $g(x,y)$ and $h(x,y)$ such that we can write
>$$f(x,y)=xg(x,y)+yh(x,y)$$
>in some neighborhood of the origin $(0,0)$, and such that
>$$\frac{\partial f}{\partial x}(0,0)=g(0,0)\qquad \frac{\partial f}{\partial y}(0,0)=h(0,0)$$

>[!proof]+
>For simplicity assume that $z=f(x,y)$ is defined in the entire $xy$-plane. Choose an arbitrary point $(x,y)$, which will stay fixed. Consider a function $f(tx,ty)$ with parameter $t$. If we differentiate this function with respect to $t$ and then integrate, we obtain the original one back. In particular, if we look at its definite integral from $0$ to $1$ together with the condition $f(0,0)=0$, we have
>$$\begin{align}f(x,y)&=\int_{0}^{1}\frac{df(tx,ty)}{dt}dt\\ &=\int_{0}^{1}\left\{x \frac{\partial f}{\partial x}(tx,ty)+y \frac{\partial f}{\partial y}(tx,ty)\right\}dt\\ &=xg(x,y)+yh(x,y) \end{align}$$
>By [[Chain rule]]. Thus, we obtained two desired functions namely
>$$g(x,y)=\int_{0}^{1}\frac{\partial f}{\partial x}(tx,ty)dt,\quad h(x,y)=\int_{0}^{1}\frac{\partial f}{\partial y}(tx,ty)dt$$
>and by taking derivatives
>$$\frac{\partial f}{\partial x}(0,0)=g(0,0)+0\cdot \frac{\partial g}{\partial x}(0,0)+0\cdot \frac{\partial h}{\partial x}(0,0)=g(0,0)$$
>and
>$$\frac{\partial f}{\partial y}(0,0)=0\cdot \frac{\partial g}{\partial y}(0,0)+h(0,0)+0\cdot \frac{\partial h}{\partial y}(0,0)=h(0,0)$$
>respectively, we obtain the second condition.

>[!example]+ 
>
***
#### Keywords
- [[Function(mapping)]],
- [[Neighborhood in topological space]],
- [[Function derivative]],
- [[Riemann integral]],
- [[Definite integral]]
#### Possibly related
- 
***
#### Sources: