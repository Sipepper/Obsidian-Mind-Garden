# Direct product of groups
***
###### tags: #Group_Theory 
***
#### Finite case
>[!dsn] Direct strict note
>Let $G$ and $G'$ be the groups. Product set $G\times G'$, i.e. set of ordered pairs $(a,a')$,$a\in G$ and $a'\in G'$, with a componentwise multiplication 
>$$(a,a')(b,b')=(ab,a'b')$$
>has a group structure with $(e_{G},e_{G'})$ as a neutral element.
>>Group constructed in a such way is called the *direct product* of groups $G$ and $G'$.

>We can define a trivial homomorphisms which are called *projections*
$$
\begin{matrix}
G&&&&G \\ 
&\overset{i}{\searrow}&&\overset{p}{\nearrow} \\ 
&&G\times G'&& \\ 
&\underset{i'}{\nearrow}&&\underset{p'}{\searrow} \\ 
G'&&&&G'
\end{matrix}
$$
$$
i(x)=(x,1),\;i'(x')=(1,x'),\;p(x,x')=x,\;p'(x,x')=x'
$$
$$\ker(p)=1\times G'\qquad \ker(p')=G\times 1$$

>[!example] 
>Let $G=\mathbb{R}$, additive group of real numbers, and $G'=\mathbb{T}=\set{z\in\mathbb{C}:|z|=1}$, i.e. the *circle group*. Then the direct product $\mathbb{R}\times\mathbb{T}$ will consists of pairs $(a,e^{i\alpha})$ with the following composition law
>$$(a,e^{i\alpha})*(b,e^{i\beta})=(a+b,e^{i\alpha}\cdot e^{i\beta})$$  
>>Geometrically this direct product represents the "infinite tube" in space.

>Such multiplication and constructions above can easily be continued on any finite number of groups.
#### Case of an arbitrary cardinality
>[!dsn] Direct strice note
>Suppose that we have some family of groups $G_{\alpha}$, $\alpha\in I$, then by *direct product* of this family of groups we mean some subset
>$$\overline{\prod\limits_{\alpha\in I}}G_{\alpha}$$ 
>of functions from *box product* of groups with *finite support*. By a law of composition we take a composition of two such functions.
>A direct product is denoted as 
>$$\prod\limits_{\alpha\in I}G_{\alpha}$$

>For a finite number of groups we can view the direct product as *componentwise multiplication*.

>[!example]
>Let $C_{p^{\infty}}$ be the Prufer $p$-group, then the direct product of all such groups for all prime numbers $p$ will have the following closed form
>$$\prod_{p\;\text{prime}}C_{p^\infty}\cong\mathbb{Q}/\mathbb{Z}$$
>i.e. isomorphic to a quotient group $\mathbb{Q}/\mathbb{Z}$.
>
>>This is only true for the direct product, because in case of the box product, the element $0$ can have infinitely many representations except from $(0,0,\dots,0)$.

***
#### Keywords
- [[Group]],
- [[Декартово произведение групп]],
- [[Function(mapping)]],
- [[Мощность множества]],
- [[Homomorphism]],
- [[Ядро и область значений отображения]],
- [[Law of composition]],
- [[Product set]],
- [[Circle group]],
- [[Множество действительных чисел]],
- [[Множество]],
- [[Locally cyclic group]],
- [[Фактор группа]],
- [[Quasi-cyclic group]]
#### Possibly related
- 
***
#### Sources: