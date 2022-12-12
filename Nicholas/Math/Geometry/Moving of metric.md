# Moving of metric
***
###### tags: #Geometry/Differential 
***
Let $\Omega$ be some open subset(region) of $\mathbb{R}^{n}$ on which we defined some metric(riemannian or pseudoriemannian), expressed in coordinates $x_{1},\dots,x_{n}$ by a non-degenerate symmetric matrix $g_{ij}=g_{ji}(x_{1},\dots,x_{n})$.^[Б.А. Дубровин, С.П.Новиков, А.Т.Фоменко - "Современная геометрия" с.38-39]

If we define a transformation $x_{i}=x_{i}(z_{1},\dots,z_{n})$, then in coordinates $z_{1},\dots,z_{n}$ metric described above will be expressed by matrix $g'_{ij}=g'_{ji}(z_{1},\dots,z_{n})$, where $$g'_{ij}=\frac{\partial x_{k}}{\partial z_{i}}g_{kl}\frac{\partial x_{l}}{\partial z_{j}}$$

>[!dsn] Direct strict note
>Transformation $x_{i}=x_{i}(z_{1},\dots,z_{n})$ is called a *moving* of a metric, or a *moving of space which preserves metric*, if $$g'_{ij}(z_{1},\dots,z_{n})=g_{ij}(x_{1}(z),\dots,x_{n}(z))$$

>[!example] 
>

>From definition we can conclude that moving of a metric is preserving a form of scalar product $(g_{ij})$.
#### Set of movings of a metric form a group
>[!dsn] Direct strict note
>All movings of a given metric forms a group under operation of composition.

>[!proof]
>Indeed, let $\phi$ and $\psi$ be two transformations which preserve metric, then they composition will also preserve metric. Same thing for inverse transformation. And identity transformation preserve metric by definition.

>Such group is called the *movings group of a metric*.
***
#### Keywords
- [[Открытое и замкнутое множества]],
- [[Евклидово пространство]],
- [[Замена координат]],
- [[Transformation of region of a finite dimensional space]],
- [[Матрица]],
- [[Риманова метрика]],
- [[Псевдориманова метрика]],
- [[Скалярное произведение]],
- [[Group]]
#### Possibly related
- 
***
#### Sources: