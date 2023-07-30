# Type of critical point is not dependent on coordinate system
***
###### tags: #Analysis/Multivariable 
***
>[!dsn]+ Direct strict note
>The property that $p_{0}$ is a non-degenerate critical point does not depend on choice of coordinates. The same is true for degenerate critical points.^[Yukio Matsumoto - "An introduction to Morse theory" p.8]

>[!proof]+
>Let $p_{0}$ be a non-degenerate critical point of a function $f$, that is $H_{f}(p_{0})\ne0$. Consider the new coordinate system $(X,Y)$ respective Hessian $\mathcal{H}_{f}(p_{0})$. By [[change of Hessian under coordinates change]] we know that
>$$\mathcal{H}_{f}(p_{0})= J^{t}(p_{0}) H_{f}(p_{0}) J(p_{0})$$
>and as determinant is multiplicative
>$$\det\mathcal{H}_{f}(p_{0})=\det J^{t}(p_{0})\det H_{f}(p_{0})\det J(p_{0})$$
>As the determinant of the Jacobian matrix satisfies
>$$\det J(p_{0})\ne0$$
>thus $\det\mathcal{H}_{f}(p_{0})\ne0$ and $\det H_{f}(p_{0})\ne 0$ are equivalent statements.

>[!example]+ 
>
***
#### Keywords
- [[Critical point of a function]],
- [[Change of coordinates]],
- [[Function(mapping)]],
- [[Hessian]],
- [[Jacobian matrix]],
- [[Determinant]]
#### Possibly related
- 
***
#### Sources: