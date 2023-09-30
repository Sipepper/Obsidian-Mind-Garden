# Homogeneous space under group action
***
###### tags: #Group_Theory #Geometry 
***
>[!dsn]+ Direct strict note
>The set $X$ is called a *homogeneous space under $G$* (for the action $\phi$) if $(G,X,\phi)$ is transitive.^[Marcel Berger - "Geometry 1" p.8].

>Let $X$ be homogeneous under $(G,X,\phi)$, and fix $x\in X$. Define $\theta:G\to X$ by $\theta(g)=g(x)$. Since $g(x)=h(x)$ is equivalent to $h^{-1}g\in G_{x}$, we can pass to a map $\underline{\theta}:G/G_{x}\to X$, where $G/G_{x}$ is the quotient set of $G$ by the equivalence relation $g\sim h\Leftrightarrow h^{-1}g\in G_{x}$:
>$$\begin{matrix}&G&\overset{p}\longrightarrow&G/G_{x}&\\&\qquad\theta\searrow&&\swarrow\underline{\theta}\\&&X\end{matrix}$$
>With $G/G_{x}$ not be a group, in general, as stabilizer may not be a normal subgroup of $G$.^[https://math.stackexchange.com/questions/2334732/is-stabilizer-subgroup-normal]

>If $G$ and $X$ are topological spaces and $\phi:G\times X\to X$ is a continuous map, the topological space $X$ is *not*, in general, homeomorphic to $G/G_{x}$ (with the quotient topology).
>>[!proof]+
>>

>[!example]+ 
>
***
#### Keywords
- [[Set]],
- [[Transitive group action on a set]],
- [[Group acting on a set]],
- [[Quotient set]],
- [[Function(mapping)]],
- [[Equivalence relation]],
- [[Group]],
- [[Stabilizer subgroup]],
- [[Normal subgroup]],
- [[Topological space]],
- [[Continuous mapping]],
- [[Homeomorphism]],
- [[Quotient topology]]
#### Possibly related
- [[Group coset]]
***
#### Sources: