# Vector space
***
###### tags: #Algebra/Linear #Fundamental_math_objects  
***
>[!dsn] Direct strict note
> A set $V$ is called a *vector space* over field $\mathbb{F}$, where elements of this set are called *vectors* for which defined two algebraic operations $(+):V\times V\to V$ and multiplication by a scalar $(\cdot):\mathbb{F}\times V\to V$, satisfying following properties^[F.Botelho, Functional Analysis and Applied optimization in Banach Spaces с.3]: 
>1. $u+v=v+u,\forall u,v\in U$,
>2. $u+(v+w)=(u+v)+w,\forall u,v,w\in U$,
>3. Exists vector $\theta$ such that $u+\theta=u,\forall u\in U$,
>4. For all vectors $u\in U$ exist a unique vector, denoted as $-u$, such that $u+(-u)=\theta$,
>5. $\alpha\cdot(\beta\cdot u)=(\alpha\cdot\beta)\cdot u,\forall\alpha,\beta,\in\mathbb{F},u\in U$,
>6. $\alpha\cdot(u+v)=\alpha\cdot u+\alpha\cdot v,\forall\alpha\in\mathbb{F},u,v\in U$,
>7. $(\alpha+\beta)\cdot u=\alpha\cdot u+\beta\cdot u,\forall\alpha,\beta\in\mathbb{F},u\in U$,
>8. $1\cdot u=u,\forall u\in U$.


>[!example] 
>As an example we can take a vector space $\mathbb{R}^{2}$ which is a cartesian plane with "arrows" which we can add and multiply by a scalar.

#### Subspace
>[!dsn] Direct strict note
>A subset $W$ of vector space $V$ is a *subspace*, if:
>- If $w,w'\in W$, then $w+w'\in W$
>- If $w\in W$ and $c\in\mathbb{F}$, then $cw\in W$.
>- The zero vector $\theta$ is in $W$.

>Also $W\subset V$ is a subspace if any linear combination(span) of elements from $W$ is in $W$.^[Michael Artin - "Algebra, 2nd edition"]
***
#### Keywords
- [[Field]],
- [[Set]],
- [[Law of composition]],
- [[Cartesian product of sets]],
- [[Linear span]]
#### Possibly related
- [[Vector]]
***
#### Sources: