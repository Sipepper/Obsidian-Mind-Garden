# Geodesic path in metric space
***
###### tags: #Geometry  
***
>[!dsn] Direct strict note
>Let $(X,d)$ be a metric space. A *geodesic path* joining $x\in X$ to $y\in X$ is a map $c$ from a closed interval $[0,l]\subset\mathbb{R}$ to $X$ such that $c(0)=x$, $c(l)=y$ and $d(c(t),c(t'))=|t-t'|$ for all $t,t'\in[0,l]$.^[Martin R. Bridson, Andre Haefliger - "Metric spaces of non-positive curvature" c.]

The image $\alpha$ of $c$ is called a *geodesic segment* with endpoints $x$ and $y$.

>[!example] 
>

###### Different types of geodesics
1. >Let $I\subseteq\mathbb{R}$ be and interval. A map $c:I\to X$ is said to be a *linearly reparametrized geodesic* or a *constant speed geodesic*, if exists $\lambda$ such that $$d(c(t),c(t'))=\lambda|t-t'|\quad\forall t,t'\in I$$ c parametrizes its image *proportional to arc length*.
2. >A *geodesic ray* in $X$ is a map $c:[0,\infty)\to X$ such that $d(c(t),c(t'))=|t-t'|$ for all $t,t'\ge0$.
3. >A *geodesic line* in $X$ is a map $c:\mathbb{R}\to X$ such that $d(c(t),c(t'))=|t-t'|$ for all $t,t'\in\mathbb{R}$.
4. >A *local geodesic* in $X$ is a map $c$ from an interval $I\subset\mathbb{R}$ to $X$ with the property that for every $t\in I$ there exists $\varepsilon>0$ such that $d(c(t'),c(c''))=|t'-t''|$ for all $t',t''\in I$ with $|t-t'|+|t-t''|\le\varepsilon$.
***
#### Keywords
- [[Metric space]],
- [[Interval]],
- [[Open and closed subsets]],
#### Possibly related
- [[Regular curves, arc length and natural parametrization]]
***
#### Sources: