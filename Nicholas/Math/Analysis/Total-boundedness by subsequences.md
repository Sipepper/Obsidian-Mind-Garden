# Total-boundedness by subsequences
***
###### tags: #Topology 
***
>[!dsn]+ Direct strict note
>Let $(U,d)$ be a metric space. If for any sequence $\{u_{n}\}\subset A$ we can choose a converging subsequence $\{u_{n_{k}}\}$ then $A$ is a totally bounded set.^[Fabio Botelho "Functional analysis and Applied Optimization in Banach Spaces" p.15]

>[!proof]+
>We prove by contradiction. Suppose that $A$ is not totally bounded. Then there exist $\varepsilon_{0}>0$ such that there is no $\varepsilon_{0}$-net with respect to $A$. Choose some $u_{1}\in A$; $\{u_{1}\}$ is not a $\varepsilon$-net, i.e. exist an element $u_{2}\in A$ such that 
>$$d(u_{1},u_{2})>\varepsilon_{0}$$
>Now $\{u_{1},u_{2}\}$ is not a $\varepsilon_{0}$-net for $A$ either, therefore exist an element $u_{3}\in A$ such that
>$$d(u_{1},u_{3})>\varepsilon_{0}\quad d(u_{2},u_{3})>\varepsilon_{0}$$
>Following the procedure above we obtain a sequence $\{u_{n}\}$ for which 
>$$d(u_{n},u_{m})>\varepsilon_{0}\quad m\ne n$$
>Obviously we cannot extract a converging subsequence.

>[!example]+ 
>
***
#### Keywords
- [[Metric space]],
- [[Convergence in metric spaces]],
- [[Totally bounded subset of a metric space]],
- [[Epsilon-net]],
#### Possibly related
- 
***
#### Sources: