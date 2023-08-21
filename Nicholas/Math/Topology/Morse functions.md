# Morse functions
***
###### tags: #Topology/Differential/Morse_theory 
***
>[!dsn]+ Direct strict note
>Let $f:M\to\mathbb{R}$ be a smooth function on a surface $M$. If every critical point of $f$ is non-degenerate, then we say that $f$ is a *Morse function*.^[Yukio Matsumoto - "An introduction to Morse theory" p.16]

>[!example]+ 
>Consider the unit sphere $\mathbb{S}^{2}$ with the orthogonal coordinates $(x,y,z)$ in three-dimensional space $\mathbb{R}^{3}$; that is $\mathbb{S}^{2}$ is defined by the equation
>$$x^{2}+y^{2}+z^{2}=1$$
>Let $f:\mathbb{S}^{2}\to \mathbb{R}$ be a function on $\mathbb{S}^{2}$ which assigns to each point $p=(x,y,z)$ on $\mathbb{S}^{2}$ its third coordinate $z$.(in some sence it's a "height function"). Then $f$ is a Morse function.
>![[Pasted image 20230812224020.png]]
>In fact $f$ has two critical points; the north pole $p_{0}=(0,0,1)$ and the south pole $q_{0}=(0,0,-1)$.
>>[!proof]+
>>To show that $f$ is a Morse function, it is enough to prove that $p_{0}$ and $q_{0}$ are both non-degenerate. To do this, we compute Hessian of $f$ with respect to the local coordinate system $(x,y)$, namely
>>$$H_{f}(p_{0})=\begin{pmatrix}-\frac{1}{\sqrt{-x^{2}-y^{2}+1}}-\frac{x^{2}}{(-x^{2}-y^{2}+1)^{3/2}}&-\frac{xy}{(-x^{2}-y^{2}+1)^{3/2}}\\ -\frac{xy}{(-x^{2}-y^{2}+1)^{3/2}}&-\frac{1}{\sqrt{-x^{2}-y^{2}+1}}-\frac{y^{2}}{(-x^{2}-y^{2}+1)^{3/2}} \end{pmatrix}\Bigg|_{(0,0)}$$
>>and
>>$$H_{f}(q_{0})=\begin{pmatrix}\frac{1}{\sqrt{-x^{2}-y^{2}+1}}+\frac{x^{2}}{(-x^{2}-y^{2}+1)^{3/2}}&\frac{xy}{(-x^{2}-y^{2}+1)^{3/2}}\\ \frac{xy}{(-x^{2}-y^{2}+1)^{3/2}}&\frac{1}{\sqrt{-x^{2}-y^{2}+1}}+\frac{y^{2}}{(-x^{2}-y^{2}+1)^{3/2}} \end{pmatrix}\Bigg|_{(0,0)}$$
>>which evaluates to
>>$$\begin{pmatrix}-1&0\\0&-1 \end{pmatrix}\quad\text{and}\quad \begin{pmatrix}1&0\\0&1 \end{pmatrix}$$
>>respectively. With non-zero determinant.
***
#### Keywords
- [[Smooth function]],
- [[Functions on surfaces]],
- [[Critical point of a function]],
- [[Sphere]],
- [[Orthonormal basis]],
- [[Hessian]],
- [[Determinant]],
- [[Matrix]]
#### Possibly related
- 
***
#### Sources: