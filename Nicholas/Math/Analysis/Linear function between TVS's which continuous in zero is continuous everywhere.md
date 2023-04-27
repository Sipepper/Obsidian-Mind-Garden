# Function between TVS's which continuous in zero is continuous everywhere
***
###### tags: #Topology #Algebra/Linear 
***
>[!dsn]+ Direct strict note
>Let $U,V$ be a topological vector spaces. Let $f:U\to V$ be a linear map continuous in $\theta$, then $f$ is continuous everywhere.^[Fabio Silva Botelho "Functional analysis and Applied Optimization in Banach Spaces" p.22]

>[!proof]+
>As $f$ is a linear map, then $f(\theta_{U})=\theta_{V}$. Because $f$ is continuous in $\theta_{U}$, by taking neighbourhood of zero $\mathcal{V}\subset V$,  there exist neighbourhood of zero $\mathcal{U}\subset U$ such that $f(\mathcal{U})\subset\mathcal{V}$.
>Therefore
>$$v-u\in\mathcal{U}\Rightarrow f(v-u)=f(v)-f(u)\in\mathcal{V}$$
>or 
>$$v\in u+\mathcal{U}\Rightarrow f(v)\in f(u)+\mathcal{V}$$
>which means that $f$ is continuous in point $u$. As $u$ was chosen arbitrarily, then $f$ is continuous everywhere, i.e. in every point.

***
#### Keywords
- [[Continuous mapping]],
- [[Topological vector space]],
- [[Linear map]],
- [[Neighborhood in topological space]]
#### Possibly related
- 
***
#### Sources: